# Types of Analyses

In most cases, a MiGA analysis involves finding the closest match(es) between a genome and genomes in a reference database.
The [MiGA home page](http://microbial-genomes.org/) presents four large square boxes titled **NCBI Prok**, **RefSeq**,
**Preproc**, and **Clades**. In addition there is a large horizontal box at the bottom of the page entitled **Environments**.
With the exception of Preproc, these selections represent the types of analyses you can make with MiGA. The difference between
NCBI Prok, RefSeq, and Environments has to do with what database is searched against. Clades is a special case in which genomes
are compared against a specific species only and offer higher intra-species resolution. Preproc is for processing input files like
raw reads into contigs, or genome quality evaluation, without searching any database.

## Preproc

**Preproc** stands for preprocessing. If you click on the **Upload genome or metagenome** button in the Preproc box, you can submit
raw or gzipped data in one of several formats and MiGA will attempt to assemble the reads into larger contigs and process these
assemblies. This process uses a series of freely available tools (many from the
[Enveomics Collection](http://enve-omics.ce.gatech.edu/enveomics)) to check quality, trim and match the reads.

Fill in the form, selecting the type of dataset and type of input from the pull-down menus. Select the files for upload by browsing
to them on your computer and click the **Upload new dataset** button at the bottom of the page.

If the input was a metagenomic dataset, users may now choose to bin the contigs into population genomes (bins) using a program outside
of MiGA, and then analyse the resulting bins using MiGA.

## RefSeq

The NCBI **RefSeq** database is a collection of taxonomically diverse, non-redundant and richly annotated sequences from high quality
closed genomes (reference datasets), 1,942 as of March 2018. By searching genomes against this database, users can begin to understand
their datasets. MiGA will identify closely related sequences which are annotated in the RefSeq database. Thus, RefSeq analysis is best
suited to identify the closest related high-quality available genomes.

## NCBI Prok

The **NCBI Prok** database contains approximately 11,000 genomes from the Prokaryotic section of the NCBI Genome database. These genomes
are from cultured microorganisms identified to species and are curated by the NCBI. This is the most comprehensive database available in
MiGA, and is recommended for analysis of complete or draft genomes of isolates and single cell amplification, and when the goal is to
classify the genome to the lowest rank possible. 

You may also choose this database to analyze binned genomes, sometimes termed population genomes. These are assembled from metagenomes
by binning, or grouping together longer contigs into sets which are hypothesized to be from the same organism. There are several
programs for accomplishing this, and we currently do not have a recommendation for which program to use.

## Clades

Clade Projects involve the analysis of genome sequences assigned to the same or closely related species in order to assess gene
content diversity and genetic relatedness among the genomes. That is, the genomes are compared among themselves to identify
orthologous groups of proteins and provide descriptive statistics on the distribution of genes within the clade such as the size of
the core gene set and the pangenome. Clade projects are ideal for micro-diversity and epidemiological studies, including plant and
animal pathogens. MiGA Online offers an expanding collection of Clade Projects including all (complete and draft) genomes of
*Bacillus cereus sensu lato*, *Marinobacter* spp, *Pelagibacter ubique*, and *Thaumarchaeota*. Developing new Clade Projects by
external users is not currently possible but will be added to MiGA Online in the future. In the meantime, you may request the staff
add your Clade Project to MiGA Online in the [Public Roadmap](http://roadmap.microbial-genomes.org/) or use the standalone version
of MiGA available at http://code.microbial-genomes.org/miga.

## Environments

MiGA also allows searching against collections of genomes, including unclassified genomes, from specific environments or studies.
The RefSoil collection is a subset of classified genomes from the RefSeq database that are associated with the soil environment.
Other collections like the Tara Ocean project MAGS are made up of unclassified genomes. The goal of searching a query genome against
these databases is not to precisely classify it, but rather to determine if the query genome has been seen before in these specialized
genome collections, and how similar it is to its closest match in these collections. Besides RefSoil and Tara Oceans MAGs collections
accessible from MiGA's home page, additional environmental and study collections are available by clicking on the **Projects** link
in the top navigation bar.
