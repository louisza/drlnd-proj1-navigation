
# DRLND Project 1: Navigation

### Introduction

This is my submission for the project 1 in the Udacity deep reinforcement learning nanao degree.
The project requires you to train an agent to collect yellow bananas and avoid blue bananas in an Uniqty environment.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

### Getting Started
The code was programmed in Python 3.6 in a [Jupyter](https://jupyter.org/) notebook with the following modules:
- [unityagents](https://github.com/Unity-Technologies/ml-agents)
- [torch](https://pytorch.org/)
- [numpy](http://www.numpy.org/)
- [matplotlib](https://matplotlib.org/)

Instructions for all the dependencies, [click here](https://github.com/udacity/deep-reinforcement-learning#dependencies)

There is no need to download Unity as an environment has been pre-prepared. Take note however that this environment is different to the default one.
Download the Unity environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

### Instructions

Clone the repository and follow the instructions in `Report.ipynb` to train the agent. Be sure to use the ocrrect kernel with all teh stated dependencies.
