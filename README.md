The objective of this assignment is to study and compare the cache effects of Integer Matrix multiplication using the common naive algorithm and a Blocked matrix multiplication (Matrix multiplication with Cache blocking: a technique to improve cache performance by multiplying small blocks of matrix at a time)

The assignment has 2 parts:

Implemented two algorithms to perform matrix multiplication of two integer square matrices, one is the naive algorithm and the other is a blocking algorithm. 

Used Perf tool to measure different hardware metrics related to the cache hierarchy (Number of references, Number of misses, miss rate, etc in the L1i, L1d and L2 caches) of the two algorithms for different sizes of input matrices (128x128, 256x256, 512x512). Observed the effects of changing the block size in the blocking matrix multiplication algorithm and decided the ideal block size, Compared the two algorithms based on the metrics.
There is also another file gen_input.cpp which can be used to generate random inputs to the matrix multiplication program by providing the size of the matrix as input.
Given a report summarizing the results and my observations.
