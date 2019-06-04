---
layout: default
title: Introduction to databases on Cedar
nav: false
---

# Introduction to databases on Cedar

**Instructor**: Wolfgang Richter and Ata Roudgar (Compute Canada and SFU)

**Course plan**:

1. Short introduction to SQL on Cedar Databases
  - why databases
  - frontends
  - basic commands
1. Overview of the two database servers on Cedar: cedar-mysql-vm (MariaDB MySQL v.10.2) and
   cedar-pgsql-vm (PostgreSQL v.10.1 with PostGIS v.2.4)
1. Deeper dive into PostgreSQL on Cedar
  - how to get a Postgres account and database on the server for your research
  - how to use the _psql_ client from the Compute Canada headnode to interactively issue SQL commands or
    simply pipe in a set of commands to be executed
  - using a scripting language such as Python to access Postgres
  - tips on optimizing your SQL commands; importance of creating indexes; explain a long running command
    to see where it can be optimized

**Target audience**: general

**Duration**: 3 hours

**Level**: beginner

**Prerequisites**: This is an introductory course, no previous experience is required. We will provide
guest accounts on Cedar cluster.

**Laptop software**: All attendees will need to bring their laptops with wireless access and with a
remote SSH client installed (on Windows laptops we recommend <a
href="https://mobaxterm.mobatek.net/download.html" target="_blank">the free edition of MobaXterm</a>; on
Mac and Linux laptops no need to install anything).

**Background information**: The database services in WestGrid are now offered through high-performance
database MySQL and Postgres servers on Cedar and Graham. Here is the
<a href="https://docs.computecanada.ca/wiki/Database_servers" target="_blank">official documentation</a>.
