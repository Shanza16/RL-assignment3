# Reinforcement Learning Assignment 3
This project implements a simple GridWorld environment to compare Sarsa and Q-learning reinforcement learning algorithms. The agent starts from a blue square and tries to reach one of the black terminal squares while avoiding the red penalty states. Moving into a red square causes a large penalty and resets the agent to the start, while other moves have a small negative reward.

Both algorithms use an epsilon-greedy policy for exploration and exploitation balance.

## Contents
- Custom GridWorld environment
- SARSA (on-policy) algorithm
- Q-learning (off-policy) algorithm
- Visualization of trajectories
- Episode reward plots

  ##  Requirements
  - numpy
  - matplotlib
 
   ## How to Run
 - Upload the notebook or Python script to Google Colab.

- Install any missing packages with !pip install numpy matplotlib if needed.

- Run the cells to train the agents and visualize results.
  
