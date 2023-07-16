---
title: Software developed by the Depledge Lab
layout: default
group: software
---

<div class="row">

<h2><code style="color : orangered"><b>This page is under construction</b></code></h2>


<br>

#### Welcome to the ROCINANTE (Really Original Collection of Interesting NANopore Tools for research Endeavours):

<br>

#### [Detection of RNA modifications mediated by error rates (DRUMMER)](https://github.com/DepledgeLab/DRUMMER)

DRUMMER is designed to identify RNA modifications at nucleotide-level resolution on distinct transcript isoforms through the comparative analysis of basecall errors in Nanopore direct RNA sequencing (DRS) datasets.

<img class="img-fluid" src="/static/img/drummer.jpg" alt="overview of DRUMMER">

<br>


#### [Nanopore guided annotation of transcriptome architectures (NAGATA)](https://github.com/DepledgeLab/NAGATA)

NAGATA uses Nanopore direct RNA sequencing reads aligned to a genome to produce a transcriptome annotation. NAGATA functions by parsing read alignments (sorted BAM files) to identify Transcription Units (TUs) by internally converting BAM file into BED12 followed by numerically sorting "start" and "end" positions and then grouping alignments with similar "start" and "end" co-ordinates. This is performed on a row-by-row basis with a new TU defined only if the alignment co-ordinates of a given row differ from the previous row by greater than user-defined threshold (20 nt for transcription start sites (TSS), 50 nt for cleavage and polyadenylation sites (CPAS)).

<img class="img-fluid" src="/static/img/nagata.jpg" alt="schematic overviews of NAGATA">
