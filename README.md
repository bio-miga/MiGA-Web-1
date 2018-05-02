# Introduction
 
**MiGA** stands for **Microbial Genome Atlas** and is designed to be the genome-equivalent of projects like the
Ribosomal Database Project (RDP) and SILVA. In addition to serving as a repository, MiGA provides data and tools
to classify and catalog microbial genomes and perform gene diversity analysis against publicly available reference
genomes.
 
MiGA takes variety of inputs to help its users make taxonomic inferences about their draft or whole genome sequences.
It uses a combination of the genome-aggregate Average Nucleotide Identity concept, or **ANI**, and the Average
Amino-acid Identity, **AAI**, to taxonomically classify a genomic sequence against the genome sequences in its
reference database. Part of MiGA’s strength lies in the >10,000 reference genomes that make up its database and an
efficient heuristic algorithm to search a query genome against all of these genomes. The reference database is
maintained in a way which allows it to be regularly updated and improved with minimal downtime. This ensures
consistently improved accuracy of classification without a large impact to its users.
 
MiGA also follows best practices in genomic analyses that allow input sequences to represent isolate genomes,
single-cell sequences, or metagenome-derived bins and contigs. These sequences can be searched against
**NCBI RefSeq** and **Prokaryotic Genomes** for classification or be used as input for a clade project. The
difference between and use cases for these different analyses are covered in subsequent sections of this document.
 
Users may also choose to explore an expanding base of environmental genomic data sets which can be used by beginners
to familiarize themselves with the inner workings of MiGA before submitting their own sequences or by microbial
ecologists interested in specific environments.
 
Although MiGA contains powerful taxonomic abilities, it is also meant to act as a robust database for a growing
number of genomes of uncultivated microbes using binning or single-cell techniques. The overarching goal is for
this database to act as a communal space for analysis and exploration of these known and unclassified genomes and
allow users to answer questions such as:

1.  Has my genome or single-cell been found previously in another sample or habitat?
2.  What is the closest relative and likely taxonomic affiliation of my query genome(s) against (named) species represented by isolates or previously identified uncultivated taxa?
3.  What sequence and gene-content distinguish my query genome from previously described taxa?
4.  Can I perform a high-resolution phylogenetic and gene-content analysis of my collection of (unpublished) genome sequences, including draft genomes and SAGs?
