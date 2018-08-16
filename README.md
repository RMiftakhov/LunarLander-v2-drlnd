# LunarLander-v2-drlnd
The solution for the LunarLander-v2 gym environment. 
![LunarLander-gif](https://github.com/RMiftakhov/LunarLander-v2-drlnd/blob/master/LunarLander.gif)
The code is based on materials from Udacity Deep Reinforcement Learning Nanodegree Program.

## Project Details
The interaction with the environment is based on the following four discrete actions: 
1. do nothing
1. fire left orientation engine
1. fire main engine
1. fire right orientation engine.

The environment returns the state vector, where the first two comprises coordinates. The episode finishes if the lander crashes or comes to rest. LunarLander-v2 defines "solving" as getting an average reward of 200 over 100 consecutive trials. (https://github.com/openai/gym/wiki/Leaderboard)
The environment is solved by using Dueling Double DQN algorithm, where actions selection based on epsilon-greedy policy.

## Getting Started
In order to train the model or inference the computed weights, the following need to be installed:
* pytorch
* pybox2d 
* gym

## Instructions
Since the repository provides the jupyter notebook, follow the steps of execution. 
