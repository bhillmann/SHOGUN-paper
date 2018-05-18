---
author-meta:
- Benjamin Hillmann
date-meta: '2018-05-18'
keywords:
- metagenomics
- microbiome
- taxonomy
- profiling
lang: en-US
title: 'SHOGUN: Accurate, scalable microbiome quantification'
...






<small><em>
This manuscript
([permalink](https://bhillmann.github.io/SHOGUN-paper/v/f9b3cd521a73c888c92e33a515920bfcdec573ac/))
was automatically generated
from [bhillmann/SHOGUN-paper@f9b3cd5](https://github.com/bhillmann/SHOGUN-paper/tree/f9b3cd521a73c888c92e33a515920bfcdec573ac)
on May 18, 2018.
</em></small>

## Authors



+ **Benjamin Hillmann**<br>
    ![ORCID icon](images/orcid.svg){height="13px" width="13px"}
    [0000-0003-4276-1329](https://orcid.org/0000-0003-4276-1329)
    · ![GitHub icon](images/github.svg){height="13px" width="13px"}
    [bhillmann](https://github.com/bhillmann)<br>
  <small>
     Computer Science and Engineering, University of Minnesota
  </small>



## Abstract {.page_break_before}

SHOGUN is a software pipeline for simultaneous taxonomic and functional abundance profiling of metagenomics datasets with Bayesian redistribution of ambiguous mapping. The pipeline is built in a modular fashion so that it may be run in its entirety or indivual parts may be flexible allowing for user creation of a reference database and selection of the alignment tool that best fits a given users data and computational resources. The package allows users to efficiently go from quality-controlled sequences to abundance profiles consistently and accurately, enabling reproducible metagenomic sequencing research.

## Introduction

Example figure reference, Figure {@fig:shogun_schematic}B shows that quality controlled reads are aligned against the reference database. Adding another line for watchdog. Another watchdog change with removing the symbolic link. Hellow world. Still having conflicts. Why are there still conflicts? Still having conflicts?



 ![(a) Raw reads from the sequencing machine are demultiplexed into individual samples. Then, each read is quality controlled with by removing adapters, low quality bases and contaminates such as host reads. Optionally, the read pairs can be stitched. (b) The quality-controlled reads are aligned against a database of known genomes to identify each read's most likely source taxon. (c) The taxa that are hit are filtered out and summarized at a specific level. These processing steps include last common ancestor assignment, genome coverage analysis, and redistribution of reads to a specific taxonomic level. (d) After the taxonomic prediction is set, the full functional repertoire of genes is directly observed through a bag-of-genes approach or predicted through a per microbe approach](images/taxonomic_profiler.png){#fig:shogun_schematic width=100%}

## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
