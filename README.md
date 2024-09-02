# Sargent Centre Summer School on Bayesian Optimization

This repository contains the code and slides associated with the Sargent Centre PSE Summer School on Bayesian Optimization held in September 2024. 

Below is a list of the material included in this repository:
- **Gaussian Processes: Theory, Background, and Recent Advances**
  - This set of slides provides a detailed overview of Bayesian modeling and how this perspective can be used to derive Gaussian processes (GP). It also provides a "deep dive" into the kernel function, which is the core object that imparts the important properties that make it a useful surrogate modeling tool in practice. Lastly, these slides discuss some important recent advances in GPs including how to deal with more complex data attributes such as high-dimensional inputs and input-dependent noise. 
- **Gaussian Processes: Hands-On Code Tutorial**
  - This Jupyter notebook (can be run in [Google Colab](https://colab.research.google.com/) provides several exercises related to Gaussian process modeling and regression using [PyTorch](https://pytorch.org/) and [GPyTorch](https://gpytorch.ai/). This includes writing functions to evaluate GP kernels and generate prior and posterior samples from GP from scratch. It also includes implementation of custom kernels in GPyTorch and an advanced modeling application to the monthly average atmospheric CO<sub>2</sub> concentration collected at the Mauna Loa Observatory in Hawaii.
    - NOTE: The solutions to each exercise are provided but it is recommended that you do not look at them in detail until after you have attempted the exercises.
- **Bayesian Optimization: Why and How?**
  - This set of slides provides an introduction to Bayesian optimization (BO) including the derivation of well-known acquisition functions (both improvement-based and information-theoretic), an overview of BO with black-box constraints, and some important practical considerations. 
- **Bayesian Optimization: Recent Advances**
  - The final set of slides focuses on some useful and important recent advances in BO including extensions to parallel evaluations, multi-objective problems, composite and network structures, optimization under uncertainty, and incorporating safety considerations. The last section describes some of the emerging research directions that I believe will have a big impact on BO in practice in the coming years. 
