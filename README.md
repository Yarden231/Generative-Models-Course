# Generative Models Course: Assignments and Final Project

This repository contains assignments and the final project completed for the Deep Generative Models course (361.2.2370) at Ben-Gurion University of the Negev.

## Course Information

- **Course Title**: Deep Generative Models (361.2.2370)
- **Instructor**: Dr. Eliya Nachmani
- **Term**: Fall 2024

## Repository Contents

### Assignment 1: Normalizing Flows & Diffusion Models

This assignment focuses on the probabilistic framework underlying denoising diffusion models:

- **Conditional Diffusion Distribution**: Explores the mixing process and how to reverse it using Bayes' rule
- **Evidence Lower Bound (ELBO)**: Derives the KL divergence between multivariate Gaussian distributions and applies it to discrete diffusion modeling

### Assignment 2: Transformers

A deep dive into attention mechanisms and transformer architectures:

- **Attention Exploration**: Analysis of copying mechanisms, average computation, and permutation equivariance in self-attention
- **Multi-Headed Attention**: Examination of drawbacks in single-headed attention and benefits of multi-headed approaches

### Final Project: Speeding Discrete Diffusion Models Sampling

This project addresses the critical challenge of inference inefficiency in discrete diffusion models for natural language processing:

- **Problem**: Discrete diffusion models require hundreds or thousands of denoising steps for high-quality output, making them computationally expensive
- **Solution Approach**: Initially proposed using Byte Latent Transformer (BLT) with Simple and Effective Masked Diffusion Language Models (MDLM)
- **Architecture**: Combined entropy-based patching with latent discrete diffusion for more efficient sequence generation
- **Methodology Change**: Later transitioned to a Multi-Flow architecture to leverage multimodal conditioning for accelerated inference
- **Experiments**: Implementation of baseline MDLM with loss and validation tracking, followed by preliminary Multi-Flow testing
  
## Contributors

- Yarden Cohen
- Oriya Sheetrit
- Noam Klainer
- Ohad Kiperman

