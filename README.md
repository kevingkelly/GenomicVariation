# GenomicVariation
Evaluate tools and methods for examining statistical variation of the genome over a group of individuals

The source of data is the 1000 Genomes project (http://www.internationalgenome.org)

The approach is to select a target gene, for example amalayse or hemoglobin

Hemoglobin has known variations across the human population (e.g., sickle cell anemia, thassalemia)
Amalyse gene variations are the result of variation in human diets over evolution (amalyse is responsible for converting starches into sugars)

The expected result is that the general level of variation from individual is generally larger than the variation between groups of inviduals when the groups are defined through geographic origin (as in the 1000 Genomes project).  But I can imagine that for some genes this may not be the case and there may be strong geographic alignments.

This particular capability provides the basis for detection of cancer causing genes, understanding of genetic disease and personnel identification.

The scale of the problem is a result of the number of genes, their possible variations and the size of the population.  There are roughly 20k genes in the human genome, genes vary in length based on the protein being encoded but are on average 27k base pairs long (and up to 2M base pairs).  Base pairs are the nucleotides that make up DNA.  There are 4 options (ACGT) so they can be encoded in 2 bits.  Gene sequences vary in length from ~100 to > 30,000 base pairs depending on the sequencing technique.  There is a lot of apparently unused room on the human genome.  The total length of the human genome is 3 billion base pairs. Aligning sequences is like completing a long, single strand jigsaw puzzle with a billion overlapping pieces that have to be aligned to form the genome. And like most things in life the human genome operates with a considerable amount of variation between individuals, variation over time across and between populations and variation over time within individuals.

Because of the potential for issues related to processing private medical data and management of open data sets security controls can beocome extremely important when processing genomic data.

Reproducibilty and control of experiments using the Blue, Red and White team approach

3 tiered, BRW team approach with integrated blockchain for securing data and analysis.  Open source, cloud enabled
