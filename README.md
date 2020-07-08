# Bayesian Naive Bayes model

## Goal

The aim of this project was to implement Naive Bayes classifier with means and standard deviations matrices treated as random variables. 

Subtasks:

- Prepare UCI WINE dataset 
- Get a priori parameters values from data
- Train model (latent radom variables) using Stochastic Variational Inference
- Visualize results

## Implementation details

Stochastic Variational Inference model was used with ELBO (Evidence Lower Bound of Kullback-Leibler Divergence) as error fucntion. 
Model was implemented using PyTorch in Jupyter Notebook.   


