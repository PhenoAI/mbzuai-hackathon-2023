# 14 - human genetics

The Human Phenotype Project collects genomic variation data on all its participants. The genomic data together with the Human Phenotype Project  deep-phenotypes allows to investigate the progression of disease, and to explore personalized treatments. We genotype millions of positions by low-pass sequencing combined with imputation using gencove platform technologies. Genotype imputation is a process of statistically inferring unobserved genotypes using known haplotypes in a population. The performance of Gencove genotype imputation is very high ( accuracy > 98% ) (Wasik et al. 2021). 

The information is stored in a number of statistics parquet files:
- `main.parquet`: sample metadata, including QC statistics, paths to PLINK variant files (raw and post-QC), and principal components (PCs).
- `variant_qc.parquet`: variant QC statistics.
- `relatives/plink_ibs.parquet`: IBS calculated by PLINK for pairs of participants.
- `relatives/king_kinship.parquet`: King kinship coefficients for pairs of participants.

And a PLINK text file `pca/eigenvec.var` containing the principal component loadings.