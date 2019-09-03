# Threshold-Sparse-Bayesian-algorithm
An better approximation algorithm than sequential threshold least squares and lasso algorithm.
Shen(Zhang et al., 2018) comes up with a threshold sparse Bayesian training method to increase the robustness of the model. The disturbances candidates, which correspond to smaller weights, will be removed through a manually set threshold, and then the model will re-estimate the weights iteratively until convergence. I used Matlab code to implement his algorithm.
