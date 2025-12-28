# Genome Viewer – Gene Visualization Tool

A Java-based graphical application for visualising genomic data using GTF and FASTA files.

## Features
- Load gene annotation tables (GTF)
- View nucleotide sequences (FASTA)
- Highlight exons for selected genes
- Visualise gene structure
- Compute basic genomic statistics

## System Requirements
- Java Development Kit (JDK) 17 or later
- Any OS supported by Java
- NetBeans IDE (recommended)

## Installation & Setup
1. Ensure Java 17+ is installed
2. Open the project folder in NetBeans
3. Run the project from NetBeans or using:


## Usage
### Load GTF
- File → Load GTF
- Select a `.gtf` file
- Gene data is parsed and populated in the table

### Load FASTA
- File → Load FASTA
- Supports `.fa` and `.fasta`
- Multi-FASTA files are supported

### Visualisation
- Select a gene from the dropdown
- Highlight exons in sequence view
- Visualise gene structure graphically

## Statistics
- Average exon length
- Exon count per gene
- Longest and shortest genes
- GC content
- FASTA sequence length
