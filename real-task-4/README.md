# Core Task 4: Variational Lower Bound (VLB) and Loss Function
In this task, you will derive and implement the Variational Lower Bound (VLB) for training diffusion models. You will:
- Understand the ELBO (Evidence Lower Bound) formulation in diffusion models.
- Implement the loss function used for training.
- Compare different loss terms to understand their effect.

[ELBO Explained](https://xyang35.github.io/2017/04/14/variational-lower-bound/)
## Task Description
1. **Part 1: Implement the Variational Lower Bound (VLB) Loss**
    1. Compute KL divergence for intermediate diffusion steps.
    2. Compute Reconstruction Loss for real data.
2. **Part 2: Implement the Simplified Noise Prediction Loss**
    1. Use Mean Squared Error (MSE) loss on predicted noise.
    2. Compare with VLB-based training.

