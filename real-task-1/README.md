# Core Task 1: Forward Diffusion Process
In this task, you will implement the Forward Diffusion Process, which is the core idea behind Denoising Diffusion Probabilistic Models (DDPMs). The goal is to progressively add Gaussian noise to images over multiple time steps, effectively destroying their structure. This process is the foundation of diffusion models, where a reverse process is later learned to generate new images.

- [DDPM Paper](https://arxiv.org/abs/2006.11239)
- [Implementation of Denoising Diffusion Probabilistic Models (DDPM) - Medium](https://towardsdatascience.com/diffusion-model-from-scratch-in-pytorch-ddpm-9d9760528946) - This article might help you for the upcoming tasks too!
## Task Description
1. **Part 1: Implement the Forward Diffusion Process**
    1. Select an image from MNIST or CIFAR-10.
    2. Define a schedule for noise levels over time steps.
    3. Apply progressive noise addition for multiple steps.
    4. Visualize how the image structure degrades over time.
2. **Part 2: Explore Different Noise Schedules**
    1. Try different schedules for $𝛼_t$ (e.g., linear, cosine).
    2. Compare how different schedules affect image corruption.