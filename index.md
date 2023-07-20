---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: targetDART
layout: page
---

targetDART develops reactive and adaptive dynamic load-balancing mechanisms to mitigate variations in computational load and performance on heterogeneous exascale systems. 
targetDART builds on the preceeding [Chameleon project](http://www.chameleon-hpc.org/), which has realised dynamic task offloading for MPI+OpenMP applications on CPU-only systems, and extends the load-balancing approach towards dynamic scheduling to (and between)
GPUs as well. 
Lead applications in targetDART are based on the simulation software packages [ExaHyPE](https://exahype.org/) and [SeisSol](https://seissol.org/), which feature complex algorithms with dynamic load on (dynamically) adaptive meshes. 

## Project Goals
The overall goal of targetDART is to provide a task-based approach for highly scalable simulation software based on MPI+OpenMP which is able to handle unpredictable (both temporary and persistent) load imbalances on heterogeneous exascale systems. Task-oriented programming models are inherently adaptive, dynamic and reactive. Thus, targetDART focuses on dynamically-adaptive and reactive distribution of computing tasks between the nodes, especially including task redistribution and migration. It therefore addresses exascale architectures which combine several CPUs with multiple accelerators (especially GPUs) on each compute node. Furthermore, targetDART deliberately relies on the de-facto programming standards MPI+OpenMP in order to achieve the widest possible applicability for existing simulation software.
The development and optimization of the task-based approach and the corresponding load-balancing methods is carried out in co-design with two exascale applications (SeisSol, ExaHyPE), for which targetDART develops reactive approaches for task distribution and migration. Thus, targetDART plans to improve the scalability and resource efficiency for both applications through a better load distribution.
Beyond that, by the HPC standard programming models MPI and OpenMP as well as their implementations, the aim is to ultimately achieve a sustainable improvement for a large number of applications.

## Funding
targetDART is funded by the German Ministry of Research and Education (BMBF) as part of its SCALEXA initiative to develop new methods and technologies for exascale high performance computing. 

<img src="assets/img/preliminary-logo.jpg" />

