# Discrete-Modeling
1. Probability & Statistical Distributions
Simulations: Binomial, Poisson, Geometric, and Negative Binomial distributions.
Analytical vs. Simulated: Validating theoretical probabilities against large-scale randomized trials (10,000 to 100,000 iterations).
Applications: Quality control defect detection, network failure rates, and noisy channel bit-error rate (BER) models.
2. Random Number Generation
Custom Generators: Implementation of a Linear Congruential Generator (LCG) from scratch.
Continuous Distributions: Utilizing the Inverse Transform Method to convert uniform distributions into exponential variables for inter-arrival and service times.
3. Queuing Theory & Systems (M/M/1)
SimPy Modeling: Simulating single-server queuing systems including grocery store checkouts, bank tellers, and cellular network base stations.
Metrics: Calculating system utilization (
ρ
), average wait times in queue (
W
q
), time in system (
W
), and evaluating Little's Law.
4. Monte Carlo Simulations
Inventory Optimization: A 5-day bagel shop inventory model maximizing net profit against probabilistic customer demand and variable order sizes.
Job Scheduling: Multi-type job batching and processing time simulations over standard 8-hour operational constraints.
5. Digital Signal Processing (DSP) & LTI Systems
Convolution: Manual and built-in implementations of Linear and Circular convolution.
Fourier Transforms: Mathematical implementation of the Discrete Fourier Transform (DFT) from scratch, validated against NumPy's Fast Fourier Transform (FFT).
System Analysis: Continuous-to-discrete sampling and discrete-time LTI system decomposition (Cascade and Parallel forms).
