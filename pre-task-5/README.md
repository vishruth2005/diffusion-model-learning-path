# Pre Task 5: Denoising Autoencoders
The goal of this task is to understand Denoising Autoencoders (DAEs), a special type of autoencoder trained to remove noise from corrupted data.

A standard autoencoder tries to reconstruct the exact input. However, a denoising autoencoder is trained to reconstruct a clean version of a corrupted input.

## Task Description
1. **Part 1: Implement a Denoising Autoencoder**
    1. Build the Encoder to map input images to a compressed latent space.
    2. Build the Decoder to reconstruct images from the latent space.
    3. Add Gaussian noise to the input images before passing them to the network.
2. **Part 2: Train the Model**
    1. Use the MNIST dataset for training (or any dataset of your choice).
    2. Train the model using Mean Squared Error (MSE) loss.
    3. Evaluate the model by denoising test images.