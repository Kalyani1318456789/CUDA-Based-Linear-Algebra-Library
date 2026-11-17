# CUDA-Based Linear Algebra Library

### GPU-Accelerated Matrix Computation using CUDA

**Course:** CS5658 – GPU Programming  
**Project:** Implementation of a Linear Algebra Library with Three Operations

## Overview

This project focuses on designing and implementing a GPU-based Linear Algebra Library using CUDA. It provides efficient implementations of three fundamental linear algebra operations: Matrix Multiplication, Matrix-Vector Multiplication, and Matrix Transpose.

Linear algebra operations are essential in scientific computing, machine learning, image processing, simulations, and engineering applications. As matrix dimensions increase, these computations require significant processing resources.

Graphics Processing Units (GPUs) offer massive parallel processing capabilities that can accelerate computationally intensive workloads. This project explores GPU parallelism by distributing computations across multiple CUDA threads.

## Key Features

- Implementation of three fundamental linear algebra operations.
- GPU acceleration using CUDA.
- Corresponding CPU implementations for performance comparison.
- Support for single-precision floating-point computations (FP32).
- Support for double-precision floating-point computations (FP64).
- Execution on NVIDIA A30 GPU hardware.
- Testing across matrices of different dimensions.
- Correctness validation of CPU and GPU implementations.
- Performance benchmarking and scalability analysis.

## Implemented Operations

### 1. Matrix Multiplication (GEMM)
Performs matrix-matrix multiplication to generate a resultant matrix. The implementation explores parallel computation of matrix elements using GPU threads.

### 2. Matrix-Vector Multiplication (GEMV)
Computes the product of a matrix and a vector using parallel GPU execution.

### 3. Matrix Transpose
Transforms a matrix by interchanging its rows and columns while preserving its elements.

## Hardware and Platform

- GPU: NVIDIA A30
- Execution Platform: Bhavani Cluster
- Programming Model: CUDA
- Programming Languages: C++ and CUDA C++

## Numerical Precision

The library supports two floating-point formats:

- **FP32:** Single-precision floating-point computation.
- **FP64:** Double-precision floating-point computation.

Both formats are evaluated to understand their computational performance and numerical behavior.

## Performance Evaluation

The CPU and GPU implementations are evaluated using different input matrix sizes.

The performance analysis focuses on:

- Execution time.
- CPU versus GPU performance.
- GPU speedup.
- Computational scalability.
- Correctness of numerical results.

## Project Objectives

1. Understand GPU-based linear algebra computations.
2. Design and implement a reusable linear algebra library.
3. Develop CPU and GPU implementations of all three operations.
4. Support FP32 and FP64 computations.
5. Execute experiments on NVIDIA A30 hardware.
6. Compare correctness and execution time.
7. Analyze GPU acceleration and scalability across different input sizes.

## Repository Structure

The repository organizes source code, testing infrastructure, benchmarks, documentation, and experimental results.

## Team Members

- Lokesh
- Jalla Charan
- Kemisetty Ashiel
- Yarlagadda Aashritha

## Course

CS5658 – GPU Programming

**Institution:** Indian Institute of Technology Palakkad

---

*This project is developed as part of the CS5658 GPU Programming course to explore parallel computing and GPU acceleration of fundamental linear algebra operations.*
