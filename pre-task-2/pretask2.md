# Task 2: Sampling from Probability Distributions
The goal of this task is to understand how to generate and visualize samples from different probability distributions, including Uniform, Gaussian (Normal), Exponential, and Laplace distributions. This will help build intuition about probability distributions and their applications in generative modeling.

## What is Sampling?
Sampling is the process of drawing random numbers from a probability distribution. This is essential in many areas of machine learning, especially in generative models, where we generate new data points based on learned distributions.

## Task Description
1. **Part 1: Generate and Plot 1D Samples from Different Distributions**
    1. Generate synthetic 1D samples from each distribution using NumPy.
    2. Plot histograms of the sampled data to visualize their distributions.
    3. Overlay theoretical probability density functions (PDFs) for comparison.
    4. Experiment with different parameters to see their effect on the distribution shape.
2. **Part 2: Compare Distributions**
    1. Plot all distributions on the same graph to compare their shapes.
    2. Analyze how different distributions behave for small vs. large parameter values.
3. **Part 3: Multidimensional Sampling**
    1. Extend the sampling process to 2D space for Gaussian and Uniform distributions.
    2. Visualize 2D distributions using scatter plots and contour plots.

## Guide
- Use `numpy.random.uniform()`, `numpy.random.normal()`, `numpy.random.exponential()`, and `numpy.random.laplace()` to generate data.
- Plot histograms using `matplotlib.pyplot.hist()`.
- Overlay theoretical PDFs using `scipy.stats`.

Upload your `.ipynb` notebook into this folder.