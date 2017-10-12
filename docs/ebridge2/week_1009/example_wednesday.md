This is an example of what you would have in your issue by Session 2 (usually Wednesday) BEFORE class for feedback. The examples here are a continuation from the Monday examples. Eric/Jovo will go through these and provide feedback by Thursday. 

# Estimation of parameters for SBM

- *Goal*: Assume fMRI and DWI data can be effectively modelled by an SBM where community 1 are the ipsilateral connections, and community 2 are the contra-lateral connections. Determine the probability of a difference in connectivity between the ipsi-lateral connections and contra-lateral connections.
- *Basic Simulation*: simulate 2 communities of data representing the simulated ipsi-lateral connections with probability p and contra-lateral connections, with probability q. Varying p-q, determine the power of a t-test. Show one line per number of observations, n, of each connection type. 
- *Application to real data*: estimate the parameters of SBM for diffusion and functional connectomes. Compare the p-value for the diffusion and functional connectomes.
- *Importance*: This goal is critical to our Sprint 0 goal, as it will be featured in the NDMG paper.

# Exploratory plots for fMRI

- *Plot 1*: Plot the timeseries signal, an [n x t] array, as a function of time. Show one line per region-of-interest in the timeseries (n lines total). 
- *Plot 2*: Plot the fMRI connectome, an [n x n] matrix. Intensity of each pixel will be the correlation strength, and the [i, j] coordinate represents the correlation between the i, j timeseries.
- *Plot 3*: ...
- *Importance*: This goal is critical to our Sprint 1 goal, as it will be the first iteration of the visualizations we use in our top-10 plots.
