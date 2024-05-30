---
title: "Shared data science infrastructure for genomics data"
collection: publications
permalink: /publication/2019-09-01-shared-data-science-infrastructure
excerpt: 'This paper discusses Boag, a shared data science infrastructure for efficiently processing and parsing large genomics data repositories.'
date: 2019-09-01
venue: 'BMC Bioinformatics'
paperurl: 'https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-2967-2'
citation: 'Bagheri, H., Muppirala, U., Masonbrink, R.E. et al. Shared data science infrastructure for genomics data. <i>BMC Bioinformatics</i> 20, 436 (2019). https://doi.org/10.1186/s12859-019-2967-2'
---

**Abstract**

**Background**: Creating a scalable computational infrastructure to analyze the wealth of information contained in data repositories is difficult due to significant barriers in organizing, extracting, and analyzing relevant data. Shared data science infrastructures like Boag are needed to efficiently process and parse data contained in large data repositories. The main features of Boag are inspired from existing languages for data-intensive computing and can easily integrate data from biological data repositories.

**Results**: As a proof of concept, Boa for genomics, Boag, has been implemented to analyze RefSeq’s 153,848 annotation (GFF) and assembly (FASTA) file metadata. Boag provides a massive improvement over existing solutions like Python and MongoDB by utilizing a domain-specific language that uses Hadoop infrastructure for a smaller storage footprint that scales well and requires fewer lines of code. We execute scripts through Boag to answer questions about the genomes in RefSeq. We identify the largest and smallest genomes deposited, explore exon frequencies for assemblies after 2016, identify the most commonly used bacterial genome assembly program, and address how animal genome assemblies have improved since 2016. Boag databases provide a significant reduction in the required storage of the raw data and a significant speedup in its ability to query large datasets due to automated parallelization and distribution of Hadoop infrastructure during computations.

**Conclusions**: In order to keep pace with our ability to produce biological data, innovative methods are required. The Shared Data Science Infrastructure, Boag, provides researchers greater access to efficiently explore data in new ways. We demonstrate the potential of the domain-specific language Boag using the RefSeq database to explore how deposited genome assemblies and annotations are changing over time. This is a small example of how Boag could be used with large biological datasets.
