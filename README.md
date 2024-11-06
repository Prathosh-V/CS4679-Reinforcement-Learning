### Reinforcement-Learning
1. k-Armed Bandit for Movie Recommendation
   
This notebook demonstrates a k-armed bandit approach for recommending movies to users, using an epsilon-greedy strategy. Each movie is treated as an "arm," and the algorithm learns to balance exploration and exploitation by adjusting recommendations based on user feedback (e.g., clicks, watch time, or ratings).  

Key Features:
Epsilon-Greedy Exploration: Balances recommending high-reward movies (exploitation) with exploring new or lesser-known movies (exploration).
Reward Calculation: Simulates user engagement with binary rewards (clicks) or continuous feedback (watch time, ratings).
Performance Evaluation: Tracks the average reward over multiple recommendation rounds.  

2. MDP vs. Q-learning for Grid-Based Pathfinding
   
This notebook compares MDP-based Value Iteration and Q-learning in a grid-based environment where an agent must navigate from a starting point to a goal while avoiding obstacles. The grid is set up with random obstacles, and the agent learns an optimal path by evaluating and comparing both methods.  

Key Features:
Grid Environment Setup: A 10x10 grid (for computational simplicity) with randomly placed obstacles, a defined starting point, and a goal.
MDP (Value Iteration): Uses dynamic programming to find the optimal policy and value function for each state.
Q-learning: Employs a model-free, episodic approach where the agent learns from experience to approximate optimal policies.
Performance Comparison: Evaluates convergence speed in reaching the goal between MDP and Q-learning.
