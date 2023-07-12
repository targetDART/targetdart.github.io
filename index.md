---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: targetDART
layout: page
---

## Description
targetDART is a BMBF-funded project which aims to support
exascale systems with a reactive and adaptive dynamic load-balancing mechanism. System architectures as well as corresponding
domain applications are becoming more and more complex. Environmental effects, e.g. to limit the energy consumption of a cluster, leads to a comparably large variability in execution time, even on rather homogenous systems. By enabling adaptive and reactive dynamic load-balancing across multiple nodes and accelerators, the impact of the resulting load imbalance
can be greatly reduced. In the case of CPU-only simulations, the preceeding [Chameleon project](http://www.chameleon-hpc.org/) already achieved good results.
However, due to the current trend of exascale systems relying mostly on GPUs
for performance, it becomes necessary to extend the load-balancing approach towards dynamic scheduling to (and between)
GPUs as well. With that, the target hardware as a whole can be efficiently utilized for
large dynamic simulations, many of which make use of dynamic mesh
refinement, such as [ExaHyPE](https://exahype.eu/) and [SeisSol](https://seissol.org/). Both applications are
adapted with the developed targetDART approach, in addition to a many smaller benchmarks.

## Goal
The goal of targetDART is to provide task-based approach for highly scalable simulation software based on MPI+OpenMP which is able to handle unpredictable (both temporary and persistent) load imbalances on heterogeneous exascale systems. Task-oriented programming models are inherently adaptive, dynamic and reactive. Thus, targetDART focuses on dynamically-adaptive and reactive distribution of computing tasks between the nodes, especially including task redistribution and migration. It therefore addresses exascale architectures which combine several CPUs with multiple accelerators (especially GPUs) on each compute node. Furthermore, targetDART deliberately relies on the de-facto programming standards MPI+OpenMP in order to achieve the widest possible applicability for existing simulation software.
The development and optimization of the task-based approach and the corresponding load-balancing methods is carried out in co-design with two exascale applications (SeisSol, ExaHyPE), for which targetDART develops reactive approaches for task distribution and migration. Thus, targetDART plans to improve the scalability and resource efficiency for both applications through a better load distribution.
Beyond that, by the HPC standard programming models MPI and OpenMP as well as their implementations, the aim is to ultimately achieve a sustainable improvement for a large number of applications.

Do we have a logo for targetDART?
Preliminarily:
<img src="assets/img/preliminary-logo.jpg" />

