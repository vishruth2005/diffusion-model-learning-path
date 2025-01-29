# Core Task 6: Efficient Sampling with DDIM
- Implement DDIM (Denoising Diffusion Implicit Model) sampling for faster image generation.
- Visualize the difference between standard diffusion sampling and DDIM sampling.

[DDIM Paper](https://arxiv.org/abs/2010.02502)

- Standard diffusion models (DDPMs) require thousands of steps to generate high-quality images.
- DDIM is an alternative sampling method that reduces the number of steps without losing quality.
- It removes the stochastic (random) part of DDPM and directly estimates clean images.
- This results in sharper images with fewer denoising steps.
- Unlike DDPM, which introduces randomness at each step, DDIM deterministically maps noise to an image in fewer steps.
## Task Description
1. **Part 1: Implement DDIM Sampling**
    1. Implement an efficient sampling function using DDIM.
    2. Try to generate images using fewer steps.
2. **Part 2: Compare DDPM vs. DDIM**
    1. Generate images using both DDPM and DDIM.
    2. Measure and compare inference time and image quality.
3. **Part 3: Visualize the Difference**
    1. Plot generated images from both models.
    2. Does DDIM achieve similar quality with fewer steps?