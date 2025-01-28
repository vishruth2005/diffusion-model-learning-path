# Pre Task 1: Understanding Gaussian Distributions
The goal of this task is to understand and visualise Gaussian (Normal) distributions in both one-dimensional (1D) and two-dimensional (2D) space. This will help in building intuition about probability densities, mean, variance, and how data is distributed in a normal distribution.

## What is a Gaussian Distribution?
The Gaussian distribution, also known as the Normal distribution, is a fundamental probability distribution in statistics and machine learning. It is defined by two parameters:

- **Mean (μ)**: Determines the center of the distribution.
- **Standard deviation (σ)**: Controls the spread of the distribution.

![Normal Distribution Function]("diffusion-model-learning-path\images\normal.png")

## Task Description
1. **Part 1: Implementing a 1D Gaussian Distribution**
    1. Generate synthetic 1D Gaussian data using NumPy.
    2. Plot the histogram of the generated data to visualize its distribution.
    3. Overlay the probability density function (PDF) of the Gaussian distribution.
    4. Experiment with different values of mean (μ) and standard deviation (σ) to observe how the distribution changes.
2. **Part 2: Implementing a 2D Gaussian Distribution**
    1. Generate synthetic 2D Gaussian data using NumPy’s multivariate_normal function.
    2. Plot the data points as a scatter plot.
    3. Visualize the 2D Gaussian distribution as a contour plot and a 3D surface plot.
    4. Experiment with different mean vectors and covariance matrices to understand their effects on the shape of the distribution.

## Guide
- Use `numpy.random.normal(mean, std_dev, size)` to generate random numbers from a Gaussian distribution.
- Plot a histogram using `matplotlib.pyplot.hist()`.
- Overlay the theoretical PDF using `scipy.stats.norm`.pdf().
- Use `numpy.random.multivariate_normal(mean, covariance, size)` to sample from a 2D Gaussian distribution.

Upload your `.ipynb` notebook within this folder with the task solution.