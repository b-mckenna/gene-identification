# Gene Identification

The purpose of this project is to identify specified genes in DNA. 

The first genes we'll identify are the 4R and7R variants of the drd4 dopamine receptor. 

## Dataset
We will use a reference chromosome from the National Library of Medicine. Specifically, the [Homo sapiens chromosome 1, GRCh38 reference primary assembly](https://www.ncbi.nlm.nih.gov/nuccore/CM000663.2?report=fasta)

## Process
1. Data Exploration
2. Convert txt to fasta filetype
3. Identify ORFs using orfipy (Python lib for finding open read frames (genes typically follow ORFs)
4. Search following codons for what matches 4R or 7R alleles
5. Take over the world!... by knowing who might have ADHD! 
