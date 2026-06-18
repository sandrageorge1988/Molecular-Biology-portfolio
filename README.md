# Technical Portfolio: Molecular Diagnostics & Biotechnology
Sandra George 
sandrageorge1988gmail.com | 0478904206 | Wyndham Vale, VIC  

---

## Executive Summary
Enthusiastic and detail-oriented Molecular Biotechnology professional holding a Master of Biotechnology. Equipped with strong technical literacy across wetlab sample preparation, high-throughput workflows, and downstream data analysis pipelines. 

## Portfolio Index
* [View Case Study: Molecular Diagnostic Pipeline Validation](./README.md)
* [View Technical Log: Automated Assay Troubleshooting & Calibration](./assay-troubleshooting-log.md)
---

## Technical Case Study: Molecular Diagnostic Pipeline Validation

Advanced Molecular Biotechnology / Postgraduate Laboratory Work
To simulate a clinical high-throughput diagnostic workflow by extracting nucleic acids, verifying quality thresholds, and utilizing bioinformatics pipelines to identify pathogenic mutations.

### 1. Wetlab Simulation & Pre-Analytical Quality Control


* **Nucleic Acid Extraction & Quantification:** Executed genomic DNA (gDNA) extraction protocols using column-based purification kits. Utilized UV-Vis Spectrophotometry (NanoDrop) to determine sample concentration and purity thresholds ($A_{260}/A_{280}$ ratios). 
* **Quality Gate Action:** Routinely monitored metrics to ensure sample purity met the optimal $1.8 - 2.0$ window, actively rejecting samples displaying signs of protein contamination or carryover salts to protect downstream enzyme activity.
* **Target Amplification (PCR Setup):** Formulated high-fidelity Polymerase Chain Reaction (PCR) master mixes to amplify targeted hypervariable regions. 
* **Troubleshooting Insight:** Encountered primer-dimer formation on initial agarose gel verification. Successfully resolved the baseline deviation by performing a gradient PCR to optimize annealing temperature ($T_m$), yielding distinct single bands without artifact interference.

### 2. High-Throughput Data Analysis & Quality Metrics

* **Raw Read Quality Verification:** Utilized platform modules to analyze raw sequencing files (`.fastq`). Reviewed Per-Base Sequence Quality scores to ensure data surpassed **Q30 thresholds** (representing a base-calling accuracy greater than 99.9%).
* **Sequence Alignment & Alignment Pipelines:** Aligned processed target sample files against reference human genomes ($hg38$) using the **NCBI BLAST** algorithm (BLASTn/BLASTp) to map sequence discrepancies, insertions, and deletions.

### 3. Variant Annotation & Clinical Interpretation
* **Database Cross-Referencing:** Cross-referenced mapped variant files against public genomic repositories including **ClinVar**, **cBioPortal**, and the **COSMIC** database.
* **Pathogenicity Classification:** Annotated identified single nucleotide variants (SNVs) to isolate somatic mutations, classifying functional consequences (e.g., distinguishing silent passenger mutations from pathogenic driver variants).

### 4. Compliance & Regulatory Mindset
* **Documentation & Audit Readiness:** Documented all master mix configurations, thermal profiles, and technical deviations inside structured laboratory logs following strict quality frameworks mirroring **ISO 15189 / NATA** compliance requirements.
