# Udacity Deep Reinforcement Learning: Navigation Project

## The Environment
For this project, you will train an agent to navigate (and collect bananas!) in a large, square world.

<img src="banana.gif"/>

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

    0 - move forward.
    1 - move backward.
    2 - turn left.
    3 - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

## Note
The project environment already set up by Udacity is similar to, but not identical to the Banana Collector environment on the Unity ML-Agents GitHub page.

## Deep Q-Network (DQN) Algorithm 
Please be referenced to https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf for the primary idea of the algorithm.

The Udacity implementation of DQN can be found at dqn_agent.py, along with a simple neural net at model.py.

Please look over the Navigation notebook for how the DQN Agent can be trained & evaluated. 

