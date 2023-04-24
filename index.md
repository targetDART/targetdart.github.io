---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: TargetDART
layout: page
---

## Description
TargetDART is a BMBF funded project which aims to support
exascale systems with a reactive and adaptive dynamic load balanc-
ing mechanism. The system architecture as well as corresponding
domain applications are becoming more and more complex. Together
with necessary means to reduce the energy consumption the variabil-
ity in execution time, even on the exact same system, can become
fairly large. By enabling adaptive and reactive dynamic load balanc-
ing across multiple nodes and GPUs, the impact of load imbalances
can be greatly reduced. The preceding [Chameleon project](http://www.chameleon-hpc.org/) could al-
ready show good results, while still disregarding offloading to GPUs.
With the current trend of exascale systems relying mostly on GPUs
for performance. This extension towards dynamic scheduling between
GPUs becomes necessary to efficiently utilize the target hardware with
large dynamic simulation, many of which make use of dynamic mesh
refinement, such as [HxaHyPE](https://www5.in.tum.de/forschung/exahype/) and [SeisSol](https://seissol.lrz.de/) . Both applications are
adapted with the developed TargetDART approach, in addition to a many smaller benchmarks.

## Goal
The goal of targetDART is a task-based approach for highly scalable simulation software based on MPI+OpenMP, which is able to handle unpredictable (both temporary and persistent) load imbalances on heterogeneous exascale systems by means of dynamic adaptive and
reactive distribution (especially redistribution/migration) of computing tasks between the nodes. In doing so, targetDART deliberately relies on the
de-facto programming standards MPI+OpenMP in order to achieve the widest possible applicability for existing simulation software. Exascale architectures are addressed, which combine several multicore processors with several accelerators (especially GPUs) on each compute node.
Task-oriented programming models are inherently adaptive, dynamic and reactive. The development and optimization of the task-based approach and the corresponding load-balancing methods is carried out in co-design with two exascale applications (SeisSol, ExaHyPE), for which in targetDART, reactive approaches for task distribution and migration are being developed. targetDART will thus improve the scalability and resource efficiency of the applications through improved load distribution.
Using the HPC standard programming models MPI and OpenMP as well as their implementations, the aim is to achieve a sustainable improvement for a large number of applications.

Do we have a logo for targetDART?
Preliminary:
<img src="assets/img/preliminary-logo.jpg" />

