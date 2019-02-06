---
layout: default
title: For instructors
nav: true
---

# Instructor information

## Course requirements

1. All courses must have hands-on exercises for the attendees.
1. Whenever possible, courses must show examples on Compute Canada's national systems
   ([Cedar](https://docs.computecanada.ca/wiki/Cedar) or
   [Graham](https://docs.computecanada.ca/wiki/Graham)). For example, when demonstrating a workflow in a
   programming language, show the entire process (writing code, compiling it, and running a Slurm job) on
   Cedar or Graham, and not just inside the IDE on your laptop.
  - at the minimum, please show some examples on clusters
  - if applicable to your course, demonstrate scaling up to large problem sizes and many cores/nodes

If you need any help in porting your workflow to Cedar or Graham, please let the summer school organizers
know early on.

## Please let us know

1. your approximate course syllabus (you can always iterate on it later),
1. any information you would like to pass to attendees: what software they need to install on their
   laptop, prerequisites for this course, the level of difficulty (beginner / intermediate / expert), and
1. whether you need a reservation on Cedar or Graham to run student exercises, and in what configuration
   per each student, e.g., (2 MPI tasks) x (3 cores per task), or GPU requirements

Please check the online description of your course in the program and let us know if you want to add or
change anything.

## Using reservations on Cedar and Graham

To use the summer school reservations on the clusters, in addition to all other flags, you will need to
pass the following flags to Slurm:

* for CPU jobs:
~~~ {.bash}
--account=wgssubc-wa_cpu --reservation=wgssubc-wr_cpu
~~~

* for GPU jobs 
~~~ {.bash}
--gres=gpu:1 --account=wgssubc-wa_gpu --reservation=wgssubc-wr_gpu
~~~

All instructors, registered attendees with CC accounts, and all guest accounts have been added to the
reservations. If you need to add anyone else to a reservation, please contact Alex Razoumov.

## Recording and broadcasting

Some of this year's summer school courses will be recorded and broadcast to remote participants and to
the overflow room. If you do not agree to having your session recorded and broadcast, please let us know
in advance.
