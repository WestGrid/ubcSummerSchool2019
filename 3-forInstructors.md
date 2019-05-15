---
layout: default
title: For instructors
nav: true
---

# Instructor information

We highly encourage all instructors to show demos and offer hands-on exercises on HPC systems, whether
real production or simulated clusters inside a VM. Please prepare your setup well before the school
begins: it is your own responsibility to make sure that in the class all attendees will be able to log in
and do the exercises on the cluster of your choice, and that this cluster has the necessary setup and
software.

## Cedar and Graham

For this summer school, we will have reservations and guest accounts on Cedar and Graham. On production
clusters, we prefer all attendees to use their own Compute Canada accounts during the school, however,
some attendees will not have accounts, hence guest accounts.

All real account holders will need to be added to the reservation. We will try to add all registrants
with confirmed accounts before the start of the school, but since we are working with partial
information, some attendees will need to be added on the fly during your course. The school organizers
will have to add them by hand. If you expect this, please coordinate with Alex Razoumov in advance.

Production clusters can be down for maintenance work (this has happened with us in the past with little
previous warning), the scheduler or one of the parallel file systems can be overwhelmed with too many
requests and thus not be available. In other words, a production system is not guaranteed to be available
for demos and training 24/7.

## Training cluster in an Arbutus VM

Instructors are free to set their own VMs emulating a Compute Canada cluster on Arbutus system. These VMs
are limited by your cloud account quotas, and Compute Canada / WestGrid staff have the same quotas as all
other users and cannot spin arbitrarily large VMs. A typical training VM would have 5-8 nodes, two
virtual CPUs and 3GB memory per node. Therefore, we discourage sharing these VMs between concurrent
courses, as irresponsible use in one session can render this VM unusable in the other. Instead, we
encourage instructors to set and maintain their own VMs which they can do with a Compute Canada account.

A training VM has many advantages:

1. You can set up a very large number of guest accounts, and you can reset the passwords at any time.
1. This training cluster will have Compute Canada's CVMFS software stack mounted, available via the same
   module environment as on our general-purpose clusters Cedar and Graham. Not all software will work,
   though, due to licensing limitations (Intel compiler) and hardware differences. Slurm, GNU
   compiler and a lot of other CVMFS-installed software will work.
1. You completely control the software stack and you can install anything as root.
1. You completely control the scheduler, can kill any offending jobs, can restart the scheduler, etc.

Please note that these training clusters does not have GPUs. If you need to run demos and/or hands-on
exercises on GPUs, you can use the production systems Cedar and Graham.

If you want to set up your own cluster, please contact Alex Razoumov well before the school.

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
