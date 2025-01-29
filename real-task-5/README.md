# Core Task 5: Training a Basic Diffusion Model
In this task, you will train a basic diffusion model using the forward diffusion and reverse denoising processes. You will:
- Implement the full training loop for a diffusion model.
- Use a U-Net architecture for noise prediction.
- Generate new images by sampling from the trained model.

Diffusion Process: 
- Forward Process (Noise Addition): Gradually adds Gaussian noise to an image over T steps.
- Reverse Process (Denoising): Uses a neural network to predict and remove noise step by step.

## Task Description
1. **Part 1: Implement the Training Pipeline**
    1. Load dataset (MNIST or CIFAR-10).
    2. Define the U-Net model for noise prediction.
    3. Implement training loop with noise prediction loss.
2. **Part 2: Image Generation Using the Trained Model**
    1. Sample pure noise and apply reverse diffusion.
    2. Visualize generated images.

Try out different noise schedules too.