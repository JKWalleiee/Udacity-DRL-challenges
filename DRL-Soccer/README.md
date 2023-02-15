[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135623-e770e354-7d12-11e8-998d-29fc74429ca2.gif "Trained Agent"
[image2]: https://user-images.githubusercontent.com/10624937/42135622-e55fb586-7d12-11e8-8a54-3c31da15a90a.gif "Soccer"


# Project 3: Collaboration and Competition

![Soccer][image2]

### Introduction

For this project, you will work with the ![soccer](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#soccer-twos) environment.

In this environment, two teams (each with a Striker/Goalie agent) compete against each other in the game of soccer. The agents can move laterally and vertically, and the strikers have the additional action of rotating left/right, resulting in 4 and 6 discrete actions for the Goalie and Striker, respectively.

The task is episodic, where each episode terminates when either 1) either team has scored a goal, or 2) the maximum time step has been reached. When a team scores a goal, they win, and when the maximum time step is reached, a draw occurs.

The goal of this task is to train a single team (eg. the red team) of agents to beat the opposing team (eg. the blue team) 95/100 times over a the previous 100 episodes. This requires the AI team to score 95/100 times -- draws are counted against the AI team.

The unity environment consists of 4 agents which have separate brains (models/optimizers), but can observe the states and actions of the other agents (on both their team and their opponent's team) and use this information during training time, but not during evaluation time.

### Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Soccer/Soccer_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Soccer/Soccer.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Soccer/Soccer_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Soccer/Soccer_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux_NoVis.zip) to obtain the "headless" version of the environment.  You will **not** be able to watch the agent without enabling a virtual screen, but you will be able to train the agent.  (_To watch the agent, you should follow the instructions to [enable a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md), and then download the environment for the **Linux** operating system above._)

2. Place the file in this repository, in the `DRL-Soccer/` folder, and unzip (or decompress) the file. 

### Instructions

Follow the instructions in `Soccer.ipynb` to get started with training your own agent!  
