# DRL-ContinousControl

### Background
This project is part of the second assignment of the Udacity Deep Reinforcement Learning Nanodegree. 

Here is a GIF of my trained agent: 
![](results/trained_reacher01092021.gif)

## Introduction
This project trains a double-jointed arm to move to target locations

Goal: Maintain its position at the target location for as many time steps as possible
Reward:
* +0.1 provided for each step that the agent's hand is in the goal location

(Instructions taken and modified from Udacity's original version found [here](https://github.com/udacity/deep-reinforcement-learning/tree/master/p2_continuous-control))

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

The task is episodic, and in order to solve the environment, your agent must get an average score of +30 over 100 consecutive episodes.

## Getting Started

1. Clone this repository: '<https://github.com/mgmendoza/DRL-ContinousControl.git>'

2. Follow the instructions specified in README of the [Deep Reinforcement Learning Nanodegree](https://github.com/udacity/deep-reinforcement-learning#dependencies) to set your python environment. The instructions will also help you install OpenAI gym, PyTorch, and ML-agents which are packages required to run the project.  

3. Download the environment from one of the links on the Getting Started section found [here](https://github.com/udacity/deep-reinforcement-learning/tree/master/p2_continuous-control))

4. Place the file in the DRLND GitHub repository, in the p2_continuous-control/ folder, and unzip (or decompress) the file.

## Instructions
Follow the instructions in Arm_ContinuousControl.ipynb to get started with training your own agent! 

You should be able to watch your robotic arms maintain position in their target locations. 
 
