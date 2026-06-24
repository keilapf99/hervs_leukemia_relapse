# HERVs in Pediatric Acute Lymphoblastic Leukemia Relapse

## Overview

This repository contains the code and processed data used to characterize the retrotranscriptome in pediatric acute lymphoblastic leukemia (ALL) and evaluate the potential association of human endogenous retroviruses (HERVs) with relapse.

The analyses were performed using bulk RNA-seq samples collected at diagnosis from pediatric ALL patients. Patients were subsequently classified according to relapse status during follow-up.

---

## Objectives

* Characterize HERV expression profiles in pediatric ALL.
* Identify transcriptional differences between patients who relapsed and those who did not relapse.
* Explore biological pathways associated with relapse.
* Infer transcriptional regulatory networks and master regulators associated with relapse.

---

## Cohort

The study includes pediatric ALL patients recruited through the Mexican Interinstitutional Group for the Identification of the Causes of Leukemia in Children (GMIICLN).

RNA sequencing was performed on diagnostic bone marrow samples, and patients were followed to determine relapse outcomes.

---

## Bioinformatic Workflow

1. Quality control of raw sequencing data.
2. Alignment of RNA-seq reads to the human reference genome.
3. Quantification of gene and HERV expression.
4. Data filtering and normalization.
5. Differential expression analysis.
6. Gene set enrichment analysis (GSEA).
7. Transcriptional network inference.
8. Master regulator analysis.

---

## Software and Tools

* FastQC
* MultiQC
* fastp
* STAR
* Telescope
* R
* DESeq2
* clusterProfiler
* ARACNe3
* NaRnEA

---

## Repository Structure

```text
data/        Processed input data
metadata/    Clinical and sample metadata
scripts/     Analysis scripts
results/     Output tables
figures/     Figures generated during the analysis
docs/        Additional documentation
```

---

## Data Availability

Raw sequencing data are not included in this repository.

Only processed and non-identifiable data required to reproduce the analyses are provided.

---

## Author

Keila PF

Master's Program in Biochemical Sciences
Universidad Nacional Autonóma de México (UNAM)

---

## Project Status

Ongoing summer research internship project.
