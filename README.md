Genetic Variant Annotation Assignment

Course: Special Topics in Bioinformatics
Students: Amna Zulfiqar, Maryam Ashraf, Noor ul Huda
Year: 2026

Project Overview

This project was designed to simulate a real-world genetic variant annotation workflow similar to what is performed in clinical genomics and research laboratories.

The goal was to manually investigate and interpret clinically relevant variants associated with selected genetic disorders using publicly available bioinformatics databases and tools.

For each disorder, we identified a representative variant and performed a complete annotation workflow, including clinical interpretation, phenotype analysis, genomic visualization, and VCF file generation.

Disorders Analyzed

The following genetic disorders were included in this study:

Cystic Fibrosis

Isolated Ectopia Lentis
Marfan syndrome
Fibrodysplasia Ossificans Progressiva(rare)
Alkaptonuria(rare)
Galactosialidosis(rare)

For each disorder, one clinically relevant variant was selected from ClinVar for detailed analysis.

Workflow Summary

For each selected variant, the following steps were completed:

Identified a clinically significant variant in ClinVar

Extracted detailed variant information

Reviewed clinical submissions and supporting evidence

Retrieved phenotype data from OMIM

Visualized genomic location using UCSC Genome Browser

Created a properly formatted VCF file

Verified annotation accuracy using ClinVar

Documented all findings in the provided Excel sheet

This structured workflow reflects the typical steps involved in variant interpretation and rare disease analysis.

Step 1 – Variant Selection (ClinVar)

Each disorder was searched in ClinVar to identify a pathogenic or clinically significant variant.

The following details were recorded:

Gene name

HGVS nomenclature (cDNA and protein change)

Chromosomal position (GRCh38)

rsID (if available)

Variant type (missense, deletion, etc.)

Clinical significance

Review status

Associated condition

These details were entered into the Excel sheet for structured documentation.

Step 2 – Variant Interpretation

The full ClinVar record for each variant was reviewed carefully.

We examined:

Number of submissions

Level of review status

Molecular consequence

Supporting literature and evidence

A concise explanation was written summarizing:

The biological impact of the mutation

Its effect on protein structure or function

Evidence supporting its pathogenic classification

This step reflects how variants are manually interpreted in clinical genomics.

Step 3 – Phenotype Information (OMIM)

The corresponding gene entry was searched in OMIM to understand the associated phenotype.

Key clinical features and inheritance patterns were summarized in the Excel phenotype section.

This step connects the molecular variant to its clinical presentation.

Step 4 – UCSC Genome Browser Visualization

Each variant was visualized in the UCSC Genome Browser using the GRCh38 human genome assembly.

Relevant tracks enabled included:

ClinVar

dbSNP

RefSeq Genes

Pathogenicity prediction tracks (AlphaMissense and RAVEL, where applicable)

Screenshots were captured showing the genomic context of each variant and stored in organized folders within the repository.

Step 5 – VCF File Creation

For each variant, a Variant Call Format (VCF) file was manually created using the standard VCFv4.2 format.

Each file includes:

File format declaration

Reference genome version

Chromosome number

Genomic position

Variant ID

Reference and alternate alleles

Filter and information fields

These files simulate how the variants would appear in actual patient WES or WGS data.

Step 6 – ClinVar Verification

Each variant was rechecked using ClinVar Variation Viewer by searching via rsID or genomic coordinates.

This step confirmed:

Clinical significance

Associated disease

Supporting clinical submissions

This ensured consistency and annotation accuracy.

ACMG/AMP Classification

Variants were interpreted according to ACMG/AMP guidelines using available evidence such as:

Type of mutation

Published studies

Multiple independent clinical submissions

Computational prediction scores

Based on this evidence, each variant was classified appropriately (e.g., Pathogenic or Likely Pathogenic) and recorded in the Excel sheet.

Repository Organization

The repository is structured as follows:

Assignment/
│
├── annotate/ (ClinVar verification screenshots)
├── ucscgenomebrowser/ (UCSC screenshots organized by disease)
├── vcf/ (VCF files for each variant)
└── assignment#2(solved)final.xlsx

This structure ensures clarity and reproducibility.

Tools Used

ClinVar

OMIM

UCSC Genome Browser

Microsoft Excel

Text editor (for VCF creation)

GitHub

Conclusion

This assignment demonstrates a complete manual variant annotation workflow similar to those used in clinical genomics and rare disease research.

Through this project, we gained hands-on experience in:

Variant database interpretation

Genotype–phenotype correlation

Genomic visualization

Clinical classification using ACMG/AMP guidelines

Research documentation and reproducibility

The workflow reflects practical bioinformatics skills relevant to both research and clinical settings.
