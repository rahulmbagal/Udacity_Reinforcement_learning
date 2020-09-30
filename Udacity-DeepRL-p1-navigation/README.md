## Project Details


We will train an agent that navigate and collect babanas in the enviroment.

# Reward:
+1 reward = if agent collect a yellow Banana 
-1 reward = if agent collect blue Banana


# State Space:
There are 37 dimensions in which agent can move with velocity along with ray-based perception of objects around agent's forward direction.

# Actions:
Four discrete actions are available,

0 - move forward.
1 - move backward.
2 - turn left.
3 - turn right.

Python notebook:

The code is written in python in the Navigation.ipynb notebook. 

Github location is :
https://github.com/rahulmbagal/Udacity_Reinforcement_learning/tree/master/Udacity-DeepRL-p1-navigation

Two Techniques implemented:

with Double DQN
and with Dueling Double DQN


# With Double DQN:

Below are the scores of each iterations average score of Episodes:

Episode 100	Average Score: 1.87
Episode 200	Average Score: 7.70
Episode 300	Average Score: 11.69
Episode 400	Average Score: 12.19
Episode 471	Average Score: 13.00
Environment solved in 371 episodes!	Average Score: 13.00

![image 1](https://user-images.githubusercontent.com/6122185/94677177-1e85be00-033a-11eb-841c-1b27aa123a62.png)

# With Dueling Double DQN:

Below are the scores of each iterations average score of Episodes:

Episode 100	Average Score: 3.23
Episode 200	Average Score: 9.72
Episode 300	Average Score: 12.97
Episode 305	Average Score: 13.01
Environment solved in 205 episodes!	Average Score: 13.01

![image 2](https://user-images.githubusercontent.com/6122185/94677408-77555680-033a-11eb-8e78-ac4e269c1915.png)

We stop the iterations once the curve is almost flat and there is no further updates in the scores 


# Getting Started:

Note: below contain is copies from the references [click here](https://github.com/udacity/deep-reinforcement-learning/tree/master/p1_navigation#getting-started)

Download the environment from one of the links below. You need only select the environment that matches your operating system:

You need only select the environment that matches your operating system:
- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/VisualBanana_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/VisualBanana.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/VisualBanana_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/VisualBanana_Windows_x86_64.zip)


(For Windows users) Check out this link if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

(For AWS) If you'd like to train the agent on AWS (and have not enabled a virtual screen), then please use this link to obtain the environment.

Place the file in the DRLND GitHub repository, in the Udacity_Reinforcement_learning/Udacity-DeepRL-p1-navigation, and unzip (or decompress) the file.


