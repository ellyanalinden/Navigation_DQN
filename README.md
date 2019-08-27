# Navigation - Unity ML-Agents

## Table of Contents
* Project description
* Goal
* Dependencies
* How to start

## Project description
In this project, I used the environment from [Unity-ML](https://github.com/Unity-Technologies/ml-agents). 
The agent is trained to navigate (and collect bananas) in a large, square world.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collection a blue banana.
The goal is to collect as many as yellow bananas as possible while avoiding blue bananas.

The state has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction.
The agent has to learn how to best select actions. Four actions are available, corresponding to:
  * 0 - move forward
  * 1 - move backward
  * 2 - turn left
  * 3 - turn right

## Goal
The agent must get an average score of +13 over 100 consecutive episodes.

## Dependencies
* Python 3.6
* Numpy ("pip install numpy"
* [PyTorch](https://pytorch.org/)
* [Unity-ML agents](https://github.com/Unity-Technologies/ml-agents)

## How to start
1. Clone this repo
2. In this notebook, the environment is imported by running cell No.2. To run this project locally, one must build their own environment.
   Below is the link to create local environment:
   * [Windows 10](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation-Windows.md)
   * [Mac, Unix](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md)
3. Execute each cells in this notebook. The average score per 100 episodes will be shown after agent training is completed. 
