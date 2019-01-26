

# Project 3: Collaboration and Competition


## Project details:

![title](tennis.png)
Unity ML-Agents Tennis Environment


In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
This yields a single score for each episode.
The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.


## Getting started:
There are three files needed to train this agent, Tennis.ipynb, ddpg.py and model.py. The trained weights of 'Actor' and 'Critic' are saved in 96_96_actor.pth and 96_96_critic.pth respectively.

The main code, which dictate the interaction between Multi Agent DDPG and the environment, is in the Tennis.ipynb. 

ddpg.py defines the agent class

model.py defines the deep neural network models for both 'Actor' and 'Critic' neural networks.  


## Instructions:
1.Download all three files, Tennis.ipynb, ddpg.py and model.py

2.Execute the codes in Tennis.ipynb 
