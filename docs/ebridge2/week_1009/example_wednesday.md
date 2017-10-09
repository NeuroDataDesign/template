This is an example of what you would have in your issue by Wednesday after class for feedback. The examples here are a continuation from the Monday example.

Ex1: Estimation of parameters for SBM

Goal: Assume fMRI and DWI data can be effectively modelled by an SBM where community 1 are the ipsilateral connections, and community 2 are the contra-lateral connections. Determine the probability of a difference in connectivity between the ipsi-lateral connections and contra-lateral connections.

Basic Simulation: simulate 2 communities of data representing the ipsi-lateral connections with probability p and contra-lateral connections, with probability q. Varying p-q, determine the power of a t-test.

Application to real data: estimate the parameters of SBM for diffusion and functional connectomes. Compare the p-value for the diffusion and functional connectomes.

Ex2: Exploratory plots for fMRI

Plot 1: Plot the timeseries signal, an [n x t] array, as a function of time. Show one line per region-of-interest in the timeseries (n lines total). 

Plot 2: Plot the fMRI connectome, an [n x n] matrix. Intensity of each pixel will be the correlation strength, and the [i, j] coordinate represents the correlation between the i, j timeseries.

Plot 3: ...
