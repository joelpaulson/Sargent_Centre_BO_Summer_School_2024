# Sargent Centre Summer School on Bayesian Optimization

This repository contains the code and slides associated with the [Sargent Centre Process Systems Engineering](https://www.imperial.ac.uk/process-systems-engineering/) Summer School on Bayesian Optimization held at the Imperial College London in September 2024. 

Below is a list of the material included in this repository, which is meant to be viewed sequentially:
- **Gaussian Processes: Theory, Background, and Recent Advances**
  - This set of slides provides a detailed overview of Bayesian modeling and how this perspective can be used to derive Gaussian processes (GP). It also provides a "deep dive" into the kernel function, which is the core object that imparts the important properties that make it a useful surrogate modeling tool in practice. Lastly, these slides discuss some important recent advances in GPs including how to deal with more complex data attributes such as high-dimensional inputs and input-dependent noise. 
- **Gaussian Processes: Hands-On Code Tutorial**
  - This Jupyter notebook (which can be run in [Google Colab](https://colab.research.google.com/)) provides several exercises related to Gaussian process modeling and regression using [PyTorch](https://pytorch.org/) and [GPyTorch](https://gpytorch.ai/). This includes writing functions to evaluate GP kernels and generate prior and posterior samples from GP from scratch. It also includes implementation of custom kernels in GPyTorch and an advanced modeling application to the monthly average atmospheric CO<sub>2</sub> concentration collected at the Mauna Loa Observatory in Hawaii.
    - NOTE: The full solutions to each exercise are provided but it is recommended that you do not look at them in detail until after you have attempted the exercises.
- **Bayesian Optimization: Why and How?**
  - This set of slides provides an introduction to Bayesian optimization (BO) including the derivation of well-known acquisition functions (including both improvement-based and information-theoretic acquisitions), an overview of BO with black-box constraints, and some important practical considerations. 
- **Bayesian Optimization: Recent Advances**
  - The final set of slides provides a quick introduction to some important recent advances in BO including extensions to parallel evaluations, multi-objective problems, composite and network structures, optimization under uncertainty, and dealing with safety considerations. The last section of the presentation describes some of the emerging research directions that I believe could have a big impact on BO in practice in the coming years. 

Although I will not explicitly provide a BO code review/tutorial, I have previously put together some Jupyter notebooks related to using BoTorch to define and optimize acquisition functions at [this link](https://github.com/joelpaulson/Great_Lakes_PSE_Workshop_2023/blob/main/Module2/Module2_Acquisition_Functions.ipynb) and execute the full BO loop at [this link](https://github.com/joelpaulson/Great_Lakes_PSE_Workshop_2023/blob/main/Module3/Module3_BO_Loop.ipynb) (on a complex controller auto-tuning example). You may find some of the code snippets useful after going through the material covered in these presentations. 
