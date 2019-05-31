---
layout: default
title: Building a bioinformatics pipeline with SnakeMake
nav: false
---

# Building a bioinformatics pipeline with SnakeMake

**Instructor**: Brian McConeghy (UBC)

This course is an introduction to using the Snakemake workflow management system to create reproducible
and scalable bioinformatics pipelines. Workflows are written in Python and can be seamlessly scaled to
server, cluster, grid and cloud environments, without the need to modify the workflow definition. In this
course, we will be writing a Snakemake pipeline that takes DNA reads as input and runs basic QC on them,
maps them to a genome of interest, sorts them, indexes them, and calls genomic variants.

**Target audience**: bioinformatics

<!-- **Course plan**: -->

**Duration**: 3 hours

**Level**: intermediate

**Prerequisites**: Familiarity with Python, Bash, Bioinformatics tools.

**Laptop software**: All attendees will need to bring their laptops with wireless access and with a
remote SSH client installed (on Windows laptops we recommend <a
href="https://mobaxterm.mobatek.net/download.html" target="_blank">the free edition</a>; on Mac and Linux
laptops no need to install anything).

<!-- Reservation on Cedar - Per student: 8 CPUs (or 32, if that is reasonable; not sure how many students will -->
<!-- be attending), 32GB RAM, 10GB of disk space (potentially less, depends on the input files used – haven’t -->
<!-- decided this yet) -->
