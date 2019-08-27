# Navigation - Unity ML-Agents

## Table of Contents
* Project description
* Goal
* Dependencies

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
