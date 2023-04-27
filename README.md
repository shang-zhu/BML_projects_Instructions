# BML_projects_Instructions

This is a repo providing instructions for BML class projects, designed by Shang Zhu (Advisor: Venkat Viswanathan)

Course string: 24786, CMU, 'Special Topics: Bayesian Machine Learning for Scientists and Engineers'

More about the class can be found [here](https://www.meche.engineering.cmu.edu/education/courses/24-786.html)

## Project Idea 1: Inverse Design for Airfoils 
(Credit to Varun Shankar, CMU)

We are trying to build ML surrogate for airfoil performance prediction, and create a generative model for airfoil images (GAN, VAE, Diffusion Models)

Data source: [here](https://github.com/ziliHarvey/CNN-for-Airfoil/tree/master/data/parsed_data) provides a labeled airfoil dataset.

In class demo on denoising diffusion models: in reference to [this](https://medium.com/mlearning-ai/enerating-images-with-ddpms-a-pytorch-implementation-cef5a2ba8cb1) post from Brian Pulfer. (Diffusion Models are really fun!)

## Project Idea 2: NeuralECM 
(Credit to Alexander Bills, CMU)

We are trying to fit equivalent circuit models with eVTOL discharging datasets, inside a differentiable framework (torchdiffeq, julia)

Julia implementation of neuralECM can be found [here](https://github.com/abillscmu/NeuralECM.jl) thanks for the efforts made by Alec!
