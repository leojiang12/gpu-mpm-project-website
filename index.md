**15-618: Parallel Computer Architecture and Programming**

**Authors:** Leo Jiang

## Overview

This project aims to implement a GPU-accelerated implicit Material Point Method (MPM) solver using C++ and CUDA. We plan to develop both 2D and 3D implementations and analyze their performance characteristics compared to CPU baselines. In particular, we will investigate the challenges of GPU parallelization, including irregular particle-grid memory accesses, atomic contention during particle-to-grid transfers, and sparse Hessian assembly during implicit time integration. Through performance profiling and experimentation, we aim to identify computational bottlenecks and explore potential optimizations to improve GPU performance and scalability.

## Project Documents

[Project Proposal (PDF)](project_prop.pdf)

Milestone Report — Coming Soon

Final Report — Coming Soon

## Implementation

The code can be found [here](https://github.com/leojiang12/gpu-mpm).

## Results

Performance measurements and visualizations will be added
as the project progresses.
