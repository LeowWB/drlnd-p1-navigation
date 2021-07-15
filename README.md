[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Project 1: Navigation

### Introduction

This project involves training an agent to navigate (and collect bananas!) in a large, square world.  

![Trained Agent][image1]

### Project Details

**Task Type**: Episodic

**State Space**: 37-dimensional, containing the agent's velocity and ray-based perception of objects around agent's forward direction

**Action Space**: 4 discrete actions as follows:
- **`0`** - move forward
- **`1`** - move backward
- **`2`** - turn left
- **`3`** - turn right

**Rewards**: +1 for collecting a yellow banana; -1 for collecting a blue banana

**Solve Requirement**: Average score of +13 over 100 consecutive episodes

### Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

2. Follow the instructions [here](https://github.com/udacity/deep-reinforcement-learning#dependencies) to setup the DRLND repository and to install the necessary dependencies.

    (_For Windows users_) Please use Windows 10.

3. Place the file in the DRLND GitHub repository, in the `p1_navigation/` folder, and unzip (or decompress) the file. 

4. Copy all files from the `src/` directory of this repository, into the `p1_navigation/` folder of the DRLND GitHub repository.

### Instructions

1. Navigate to the `p1_navigation/` directory of the DRLND repository.
2. Execute `jupyter notebook` and open `Navigation.ipynb`.
3. To train an agent from scratch, simply run the code cells in sections 1 through 3.
4. To test the trained agent and visualize its performance and behavior, run the code cell in section 4.
5. When done, close the environment by running the code cell in section 5.
