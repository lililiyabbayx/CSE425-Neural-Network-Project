# CSE425-Neural-Network-Project

# Discrete Variational Autoencoders (DVAE) with MLP and CNN

This repository contains an implementation of Discrete Variational Autoencoders (DVAE) with categorical latent variables. The goal is to compare two architectures  a fully-connected (MLP) model and a convolutional neural network (CNN) and study the effect of using discrete latent variables instead of the traditional continuous Gaussian latent space.

## Overview

Variational Autoencoders (VAEs) are deep generative models that learn latent representations by maximizing the Evidence Lower Bound (ELBO). Most VAEs use a continuous Gaussian latent space, but discrete latent variables can offer advantages such as interpretability and a better inductive bias for clustered or categorical data.  

This project:
- Implements a DVAE with categorical latents using Gumbel-Softmax reparameterization.
- Trains both MLP- and CNN-based encoder/decoder architectures.
- Evaluates reconstruction performance via ELBO.
- Analyzes the latent space using t-SNE and UMAP+KMeans.
- Reports clustering metrics: Silhouette, NMI, ARI.


