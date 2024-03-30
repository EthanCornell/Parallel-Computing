# Parallel Computing Projects
Parallel Computing Projects: Explore projects focusing on leveraging multiple processors or computers to perform computations simultaneously, improving efficiency and scalability in various applications.
This repository contains various parallel computing projects aimed at exploring different parallelization techniques and frameworks. Each project focuses on different aspects of parallel computing, ranging from distributed memory parallelism to shared memory parallelism and GPU acceleration. Below is a brief description of each project:

## 1. N-Body Simulation via MPI
This project implements an N-body simulation using the Message Passing Interface (MPI) paradigm. MPI enables distributed memory parallelism, allowing the simulation to be run across multiple compute nodes in a cluster. This approach is suitable for large-scale simulations requiring communication between different computing units.

## 2. N-Body Simulation via OpenMP
Similar to the MPI implementation, this project simulates N-body interactions, but it utilizes OpenMP for shared memory parallelism. OpenMP simplifies parallel programming for shared memory architectures like multi-core CPUs. The simulation is parallelized by distributing the workload across multiple threads within a single compute node.

## 3. Message-passing Parallelism
This project explores message-passing parallelism techniques using various frameworks and libraries. It includes implementations of classic parallel algorithms and applications using message passing models such as MPI, enabling efficient communication and synchronization between distributed computing units.

## 4. Shared Memory Parallelism
In contrast to message-passing parallelism, this project focuses on shared memory parallelism techniques. It includes implementations of parallel algorithms and applications optimized for multi-core architectures using frameworks like OpenMP or pthreads. Shared memory parallelism enables efficient utilization of resources within a single compute node.

## 5. A Simple CUDA Renderer
This project provides a simple CUDA renderer implemented using NVIDIA's CUDA parallel computing platform. CUDA allows developers to harness the computational power of NVIDIA GPUs for general-purpose parallel computing tasks. The renderer showcases GPU acceleration techniques for graphics rendering tasks.

## 6. Building A Task Execution Library from the Ground Up
This project involves the development of a task execution library designed to facilitate parallel task execution on distributed or shared memory architectures. The library abstracts away complexities of parallelism and provides a simple interface for managing parallel tasks efficiently.

## 7. Chat149 - A Flash Attention Transformer DNN
Chat149 is a deep neural network (DNN) architecture based on the Transformer model, optimized for sequence-to-sequence tasks such as natural language processing. The project focuses on leveraging parallel computing techniques, such as attention mechanism parallelism, to enhance the training and inference speed of the model.

## 8. Performance Analysis on a Quad-Core CPU
This project conducts performance analysis and optimization techniques on a quad-core CPU architecture. It involves profiling and benchmarking various parallel algorithms and applications to understand resource utilization, scalability, and bottlenecks on multi-core processors.

