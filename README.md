CIA1: Recommendation System

RL method used: K-arm bandit + Epsilon algorithm

Feedback loop:
- Class name: EpsilonGreedyBandit
- First initialization of:
a. the number of arms (k)
b. epsilon value for randomness 
c. count value of each action
d. action value for each action

- You select the actions starting with exploration till you reach the epsilon value. These actions are randomly selected.
- You then update the action values by adding it to the original reward using a formula: (reward - action value)/count of the action
- The recommendation is done by randomly selecting the actions. one action that is initialized by giving a high probability.

CIA2: MDP based RL agent
RL algorithms used: Q-learning, SARSA, Deep Q-Network

After use of the above 3 algorithms we benchmark these algorithms on the following properties:
- Convergence time
- Path length
- Reward
