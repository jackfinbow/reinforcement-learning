# Reinforcement Learning Algorithms
A collection of Jupyter notebooks to demonstrate the implementation of different reinforcement learning algorithms, including temporal-difference methods such as Q-learning, and dynamic programming methods such as value iteration.

## Q-learning
Uses Q-learning to solve a small 5x5 gridworld environment containing gold and a bomb.

## Value Iteration
Uses the above gridworld environment to first compare implementations of value iteration on a deterministic and stochastic environment. The stochastic environment is then expanding to contain two pieces of gold that the agent must collect, thus requiring a much larger state space to iterate through.

## Racetrack
Used a racetrack environment where the agent had to control a car to find the optimum policy for driving around a corner. Project includes implementations using on-policy first-visit Monte Carlo, Sarsa, and Q-learning, with a comparison between their learning curves. Also includes an implementation of Watkins's Q(&lambda;) with a comparison to Q-learning.
