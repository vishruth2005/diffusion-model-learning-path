# Pre Task 4: Variational Autoencoders (VAEs)
The goal of this task is to understand Variational Autoencoders (VAEs), which are a type of generative model that learns latent space representations of data. You will implement a simple VAE using PyTorch to learn the latent space of a dataset, such as MNIST (you can use any dataset of your choice too).

- [VAEs Paper](https://arxiv.org/abs/1906.02691)
- [Cool VAE Implementations](https://github.com/AntixK/PyTorch-VAE)
- [KL Divergence](https://towardsdatascience.com/understanding-kl-divergence-f3ddc8dff254)

## Task Description
1. **Part 1: Implement the VAE Model**
    1. Build the Encoder network to output $𝜇$ and $log(𝜎^2)$.
    2. Implement the Reparameterization Trick to sample 𝑧.
    3. Build the Decoder network to reconstruct the input from 𝑧.
2. **Part 2: Train the VAE**
    1. Use the MNIST dataset for training (or any image dataset of your choice).
    2. Define the VAE loss function (reconstruction + KL divergence).
    3. Train the model and visualise the reconstruction results.
3. **Part 3: Latent Space Exploration**
    1. Visualise the latent space by projecting test data into it.
    2. Generate new samples by interpolating in the latent space. Interpolate between two points in the latent space to see smooth transitions between digits.
    3. Explore the latent space by visualising clusters corresponding to different digits (or classes).


