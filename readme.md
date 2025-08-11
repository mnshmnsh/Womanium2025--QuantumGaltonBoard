# Quantum Walks & Monte Carlo Project | WISER 2025 x NNL
Quantum Walks and Monte Carlo
-----------------------------

Explore how quantum circuits can simulate complex systems through a Galton Box-style Monte Carlo problem, an approach relevant to high-dimensional challenges like particle transport and quantum systems.

This project builds on the foundations of the Quantum Fourier Transform and its potential for exponential speed-up over classical methods.​​

​The problem statement is based on the [Universal Statistical Simulator.](https://arxiv.org/abs/2202.01735) which uses quantum circuits to simulate a Galton Box (Plinko) game. This is representative of a Monte Carlo problem, which is sometimes used as a PDE solution method for high-dimensional problems with complex interactions (e.g., particle transport, quantum systems).  

01.

### Challenge Duration & Key Dates

1.  5 weeks
    
2.  Teams start working on July 1, 2025
    
3.  Teams submit their challenge solutions on August 10, 2025
    

02.

### Team guidelines

1.  Max. Team size - 3
    
2.  All team participants must be enrolled in Womanium & WISER 2025 Quantum Program.
    
3.  Everyone is eligible to participate in this challenge and win awards.
    
4.  Best participants get selected for QSL fellowships
    

03.

### Quantum hardware & platform

1.  Participants may use any quantum SDK or platform of their choice.
    
2.  Participants should use an all-to-all sampler for noiseless quantum simulations.
    
3.  Participants may use any quantum hardware for noise-model simulations. 
    

04.

### Challenge deliverables

1.  Review the paper, and any related resources to learn how to implement quantum Galton boards. Prepare a summary of your understanding in a well structured 2-pager document. 
    
2.  Using the 1- and 2-layer Galton Box code as a starting point, write a general algorithm that generates a circuit for any number of layers. Run and verify that the output is a Gaussian distribution. You may use any quantum SDK and platform for your implementation.
    
3.  Modify the function so that it obtains a different target distribution. Use a noiseless all-to-all sampler:
    
    *   Exponential distribution
        
    *   Hadamard quantum walk
        
4.  Using a noise model of real hardware, come up with an optimized implementation of this problem for the previous distributions. The challenge is to maximize the accuracy and number of board layers. You may use any quantum hardware noise model for your simulations
    
5.  Compute the distances between the obtained distributions and the target distributions, accounting for stochastic uncertainty.
    

05.

### Judging Criteria

1.  The submissions must be in an easy-to-access, and well-structured format.
    
2.  All participants must complete Tasks 1), 2) and 3) to be eligible for project certificates. 
    
3.  The best accuracy and attempt at Tasks 4) and 5) would be given the most weight. Finalists for QSL fellowships will be decided on the basis of highest cumulative scores from all the tasks, Technical Merit, Novelty, Communication and Presentation Skills.