Dear Search Enthusiasts,

Welcome to this repository, which contains Julia code for benchmarking two hybrid (quantum-classical) search algorithms designed for scenarios where the number of solutions is unknown in advance.

The first algorithm, Particle-Guided Grover's Search (PGGS), is a hybrid approach that incorporates Particle Filtering—a Bayesian filtering technique—to make use of all failed attempts in the search process. This stands in contrast to traditional Grover-based methods, which typically ignore such feedback when the number of solutions is unknown.

A well-known classical adaptation by Boyer et al. (arXiv:quant-ph/9605034) introduced a method for selecting the number of Grover iterations by sampling from a pre-defined interval and expanding this interval exponentially upon failure. This approach was further developed and implemented by Cade et al. (arXiv:2203.04975v2), who referred to the resulting algorithm as QSearch, and used it to benchmark Grover's algorithm beyond the asymptotic regime.

In this work, we use QSearch as a baseline to evaluate the performance of PGGS. The provided code serves as the primary tool for conducting this comparative analysis.

The results of this benchmarking study are presented in Chapter 3 of the PhD thesis "Hybrid Quantum Search Algorithms", submitted to the University of Cologne.


