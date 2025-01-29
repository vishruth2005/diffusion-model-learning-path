# Core Task 2: Reverse Diffusion Process
The goal of this task is to implement the Reverse Diffusion Process, which learns to remove noise step-by-step, gradually reconstructing the original image. This is the core principle behind Denoising Diffusion Probabilistic Models (DDPMs) and how they generate new images from pure noise.

You will train a neural network to predict and remove noise from a noisy image at each step, effectively learning the reverse diffusion process.

If we learn to predict noise, we can reverse the diffusion process to reconstruct an image from noise.
Once trained, we can sample new images starting from pure Gaussian noise.

## Task Description
1. **Part 1: Train a Neural Network to Predict Noise**
    1. Use a simple U-Net (or an MLP for simplicity) to estimate noise.
    2. Train it on noisy images and their corresponding noise values.
2. **Part 2: Implement the Reverse Diffusion Process**
    1. Use the trained network to progressively denoise images.
    2. Start from pure noise and reconstruct an image step-by-step.
3. **Part 3: Generate Images from Pure Noise**
    1. Start with a random Gaussian noise image.
    2. Apply the reverse diffusion process to generate new images.

