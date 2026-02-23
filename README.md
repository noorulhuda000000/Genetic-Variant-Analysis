Genetic Variant Annotation Assignment

Course: Special Topics in Bioinformatics
Student: Huda
Year: 2026

Project Goal

This assignment simulates a real-world genetic variant annotation workflow used in clinical and research bioinformatics labs.

For three selected genetic disorders, we:

Identified clinically relevant variants from ClinVar

Interpreted variant evidence and classifications

Retrieved phenotype information from OMIM

Visualized genomic context using UCSC Genome Browser

Created properly formatted VCF files

Documented all findings in Excel and GitHub

This workflow reflects how variant interpretation is performed in rare disease and clinical genomics analysis.

Diseases Selected

The following three genetic disorders were analyzed:

Cystic Fibrosis

Isolated Ectopia Lentis

Fibrodysplasia Ossificans Progressiva

Each disease includes one clinically relevant variant selected from ClinVar.

Overall Workflow

For each disease, the following steps were performed:

Selected a clinically relevant variant from ClinVar

Extracted variant details and classification

Reviewed available submissions and supporting studies

Retrieved phenotype information from OMIM

Visualized genomic location using UCSC Genome Browser

Created a VCF file simulating patient WES/WGS data

Verified clinical annotation using ClinVar

Documented findings in Excel

Organized results in a GitHub repository

Detailed Methodology
Step 1 — Variant Selection (ClinVar)

Searched each disease in ClinVar.

Selected a relevant pathogenic or clinically significant variant.

Extracted:

Gene name

HGVS nomenclature

Protein change

Chromosomal position (GRCh38)

rsID

Clinical significance

Associated condition

These details were entered into the Excel sheet.

Step 2 — Variant Interpretation

From the ClinVar record, the following were reviewed:

Number of submissions

Review status

Molecular consequence (missense, nonsense, etc.)

Published evidence

A summary explanation was written describing:

The molecular effect of the mutation

Its impact on protein structure/function

Supporting evidence for classification

This simulates manual variant interpretation.

Step 3 — Phenotype Analysis (OMIM)

The corresponding gene entry was searched in OMIM.

Phenotype information was reviewed.

Clinical features and inheritance pattern were summarized in the Excel phenotype field.

This step connects genotype to clinical presentation.

Step 4 — UCSC Genome Browser Analysis

Purpose: Visualize the variant in genomic context.

Steps performed:

Selected Human Genome assembly GRCh38.

Entered chromosomal coordinates.

Enabled tracks:

ClinVar

dbSNP

RefSeq Genes

Pathogenicity prediction tracks (AlphaMissense, RAVEL where applicable)

Captured screenshots showing variant position within gene.

Screenshots are stored in organized folders.

Step 5 — VCF File Creation

A Variant Call Format (VCF) file was manually created for each disease variant using the standard format:

##fileformat=VCFv4.2
##reference=GRCh38
#CHROM  POS  ID  REF  ALT  QUAL  FILTER  INFO

Each VCF file simulates how a variant would appear in real patient WES/WGS sequencing data.

Step 6 — ClinVar Annotation Verification

Each variant was queried using its rsID or genomic coordinates in ClinVar Variation Viewer to confirm:

Clinical significance

Associated disease

Supporting submissions

This step validates annotation accuracy.

📁 Repository Structure

The repository is organized as follows:

Assignment/
│
├── annotate/
│ └── (ClinVar annotation screenshots for all three diseases)
│
├── ucscgenomebrowser/
│ ├── Cystic_Fibrosis/
│ ├── Ectopia_Lentis/
│ └── Fibrodysplasia_Ossificans_Progressiva/
│ (UCSC screenshots inside each folder)
│
├── vcf/
│ ├── CF_variant.vcf
│ ├── EL_variant.vcf
│ └── FOP_variant.vcf
│
└── variant_data.xlsx

Screenshots are stored separately to maintain clarity and avoid cluttering the Excel sheet.

ACMG/AMP Interpretation

Variants were interpreted according to ACMG/AMP guidelines using available evidence such as:

Variant type (loss of function, missense, etc.)

Multiple clinical submissions

Published evidence

Computational pathogenicity predictions

Each variant was classified accordingly (e.g., Pathogenic, Likely Pathogenic, etc.) and documented in the Excel sheet.

Tools Used

ClinVar

OMIM

UCSC Genome Browser

Excel

Notepad (for VCF creation)

GitHub

Reproducibility

To reproduce this workflow:

Select three genetic disorders.

Identify clinically relevant variants in ClinVar.

Extract and document variant details.

Retrieve phenotype information from OMIM.

Visualize genomic location in UCSC Genome Browser.

Create VCF files in proper format.

Organize results in structured folders.

Conclusion

This assignment demonstrates a complete manual variant annotation workflow similar to procedures used in clinical genomics and rare disease research. It strengthens skills in database interpretation, genomic visualization, variant classification, and reproducible research documentation.
