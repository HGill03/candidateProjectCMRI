# Instructions

The objective of this small exercise is to identify the number of rare variants in the provided VCF file. We provide two input files:

  * `NA12878.chr21.slice.vcf.gz`: A small slice of a sample's VCF that we would like to filter for rare variants.
  * `gnomad.chr21.slice.vcf.gz`: A small slice of population frequencies in VCF format from gnomAD v4.1.0. The overall population frequency for each variant can be found in the INFO/AF VCF field.

Both VCF files are for the GRCh38 reference genome.

Using the above files, please write a Python script that determines how many variants in `NA12878.chr21.slice.vcf.gz` have a gnomAD population allele frequency of less than `0.01`. You are free to use common bioinformatics tools, but please wrap them inside a single Python script. 
