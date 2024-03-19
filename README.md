# Clustering Algorithm

Single nucleotide polymorphism (SNPs) is a typical indicator of genetic variations in many human diseases. This can be identified by K-means clustering algorithms as an unsupervised learning algorithm. K-Means performs the division of objects into clusters that share similarities and are dissimilar to the objects belonging to another cluster. 

K-Means clustering is adapted to partition the genotype dataset into various clusters and all the genotype data falls into a unique collection of clusters for different runs.

Import a VCF file into R, convert it into a data.frame using the Pegas package, and change the data into binary data for K-means clustering.


If the factors are 0/1 only, have the dominance effect. If they are 0/1/2, it is additive (most common). It may be a 0 represents no SNP at a position. Or 0 represents both alleles are the reference allele and there is no alternative allele at the position? This would be the dominance effect.

