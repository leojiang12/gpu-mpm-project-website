# A GPU-Accelerated Implicit Material Point Method

**CMU 15-618: Parallel Computer Architecture and Programming — Fall 2026**

**Author:** Leo Jiang

**Project Website:** [GPU MPM Project](https://leojiang12.github.io/gpu-mpm-project-website/)

## Overview

This project aims to implement a GPU-accelerated implicit Material Point Method (MPM) solver using C++ and CUDA. The goal is to develop 2D and 3D implementations and analyze their performance characteristics compared to CPU baselines.

In particular, this project investigates several challenges of GPU parallelization:

- Irregular particle-grid memory accesses
- Atomic contention during particle-to-grid (P2G) transfers
- Parallel sparse Hessian assembly for implicit time integration
- GPU performance bottlenecks and problem-size scaling

The implementation will be developed independently, with performance profiling and experimentation used to explore possible GPU optimizations.

## Implementation

The project uses:

- **C++ / Eigen** for CPU reference implementations
- **CUDA** for GPU implementations
- **NVIDIA Nsight Systems and Nsight Compute** for GPU profiling

## Project Resources

- [Project Website](https://leojiang12.github.io/gpu-mpm-project-website/)
- [Project Proposal](https://leojiang12.github.io/gpu-mpm-project-website/proposal.pdf)

## References

[1] M. Gao, X. Wang, K. Wu, A. Pradhana, E. Sifakis, C. Yuksel, and C. Jiang, "GPU Optimization of Material Point Methods," *ACM Transactions on Graphics*, vol. 37, no. 6, Article 254, pp. 1–12, 2018.

https://doi.org/10.1145/3272127.3275044
