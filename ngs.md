---
layout: default
title: Next-Generation Sequencing
nav: false
---

# Next-Generation Sequencing

**Instructor**: Phillip Richmond and Oriol Fornés (UBC)

In this workshop we will explore a few different forms of short-read sequencing datasets including
ChIP-sequencing and ATAC-sequencing, and where to find them.  We will demonstrate how to map and
visualize the data against the reference genome, and perform downstream operations such as peak
calling. Data will be mapped with the tool BWA, converting formats using samtools, and downstream
enrichment/peak calling performed with MACS2.

**Target audience**: bioinformatics

<!-- **Course plan**: -->

**Duration**: 3 hours

**Level**: beginner / intermediate / expert

Intermediate for following along, beginners are welcome but encouraged to take notes if not confident
with the command line.

**Prerequisites**: Ideally, you should already know Python and the Linux command line (intermediate /
proficient). Please use the time before the summer school to find and review basic online Python and bash
tutorials. You should also have some knowledge of the human reference genome and have some exposure to
genomics, and have a working knowledge of interacting with Cedar compute cluster (SLURM, ssh).

**Laptop software**: All attendees will need to bring their laptops with wireless access and with a
remote SSH (remote login) and SCP/SFTP (remote file transfer) client installed. On Windows laptops we
recommend <a href="https://mobaxterm.mobatek.net/download.html" target="_blank">the free edition of
MobaXterm</a>; on Mac and Linux laptops no need to install ssh/scp/sftp. Please also install IGV from
https://software.broadinstitute.org/software/igv/download.

Not required but ideal: capacity to mount cedar drives onto local desktop
(https://www.westgrid.ca/support/sshfs_file_transfer).

<!-- Software: -->
<!-- - BWA: already on cedar -->
<!-- - MACS2: works with local install, would be nice to have on main system as module though -->

<!-- Reservation: -->
<!-- - per-student 8 CPUs w/ 4G RAM/CPU for the 3 hour session -->
