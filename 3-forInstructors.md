---
layout: default
title: For instructors
nav: true
---

# Instructor information

All summer school attendees will have guest accounts on our training cluster in a virtual machine on
Arbutus system. This training cluster will have Compute Canada's CVMFS software stack mounted, available
via the same module environment as on our general-purpose clusters Cedar and Graham. Not all software
will work, though, due to licensing limitations (Intel compiler) and hardware differences. Slurm, GNU
compiler and a lot of other CVMFS-installed software will work. We encourage you to test your workflow
early and let us know about any problems. For access to the cluster, please contact Alex Razoumov.

Please note that this cluster does not have GPUs. If you need to run demos and/or hands-on exercises on
GPUs, please let us know. You can run GPU demos on Cedar and Graham, but many attendees will not have
Compute Canada accounts to log in to these production systems.

## Course requirements

1. All courses must have hands-on exercises for the attendees.
1. Whenever possible, courses must show examples on our training cluster. For example, when demonstrating
   a workflow in a programming language, show the entire process (writing code, compiling it, and running
   it in a Slurm job) on the cluster, not just inside the IDE on your laptop.
  - at the minimum, please show some examples on the cluster
  - if applicable to your course, demonstrate scaling up to large problem sizes and many cores/nodes

If you need any help in porting your workflow to the training cluster, please let the summer school
organizers know early on.

## Please send to us

1. your approximate course syllabus (you can always iterate on it later),
1. any information you would like to pass to attendees: what software they need to install on their
   laptop, prerequisites for this course, the level of difficulty (beginner / intermediate / expert), and
1. if using significant cluster resources, what hardware configuration you need per each student, e.g.,
   (2 MPI tasks) x (3 cores per task)

Please check the online description of your course in the program and let us know if you want to add or
change anything.

<!-- ## Using reservations on Cedar and Graham -->

<!-- To use the summer school reservations on the clusters, in addition to all other flags, you will need to -->
<!-- pass the following flags to Slurm: -->

<!-- * for CPU jobs: -->
<!-- ~~~ {.bash} -->
<!-- --account=wgssubc-wa_cpu --reservation=wgssubc-wr_cpu -->
<!-- ~~~ -->

<!-- * for GPU jobs  -->
<!-- ~~~ {.bash} -->
<!-- --gres=gpu:1 --account=wgssubc-wa_gpu --reservation=wgssubc-wr_gpu -->
<!-- ~~~ -->

<!-- All instructors, registered attendees with CC accounts, and all guest accounts have been added to the -->
<!-- reservations. If you need to add anyone else to a reservation, please contact Alex Razoumov. -->
