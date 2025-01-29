# Pre Task 3: Markov Chains and Stochastic Processes
The goal of this task is to understand [Markov Chains](https://brilliant.org/wiki/markov-chains/), transition matrices, and stochastic processes by implementing and visualizing simple Markov processes in Python. This knowledge is fundamental for understanding diffusion models, as they involve Markov processes to transform data into noise and vice versa.

Markov Chains are a core concept in diffusion models, where they describe how data is gradually transformed into noise and then recovered. Learning how probability distributions evolve in Markov Chains is essential for understanding the forward and reverse processes in diffusion models.

## Task Description
1. **Part 1: Implement a Simple Markov Chain**
    1. Define a small system with 3 states (e.g., A, B, C).
    2. Construct a transition probability matrix.
    3. Simulate a Markov process by randomly transitioning between states over multiple steps.
    4. Plot the evolution of state probabilities over time.
2. **Part 2: Compute the Stationary Distribution**
    1. Find the [stationary distribution](https://brilliant.org/wiki/stationary-distributions/) by iterating the transition matrix.
    2. Compare the result with the analytical solution.

## Guide
- Choose a transition matrix that ensures each row sums to 1.
- Represent states as labels (e.g., "A", "B", "C").
- Start from an initial state and transition according to probabilities.
- Store the state history and visualize how states evolve.
- For computing stationary distribution, tterate matrix multiplication until probabilities stabilise.