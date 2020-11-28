
## Udacity Deep Reinforcement Learning Nanodegree - Project 2: Continuous Control

# The Environment

![image](https://user-images.githubusercontent.com/6122185/100517119-83c92480-31ae-11eb-8217-5b56458a253a.png)


For this project, you will work with the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment.


# Below are the details of the Enviroment as per the official website mentioned:

Set-up: Double-jointed arm which can move to target locations.

Goal: The agents must move its hand to the goal location, and keep it there.

Agents: The environment contains 10 agent with same Behavior Parameters.

Agent Reward Function (independent):

  - +0.1 Each step agent's hand is in goal location.

Behavior Parameters:

  - Vector Observation space: 26 variables corresponding to position, rotation, velocity, and angular velocities of the two arm rigid bodies.

  - Vector Action space: (Continuous) Size of 4, corresponding to torque applicable to two joints.

  - Visual Observations: None.

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

# Goal of this project 

For this project, using the single agent, The task is episodic, and in order to solve the environment, your agent must get an average score of +30 over 100 consecutive episodes.

# Below is the training of the model

![results](https://user-images.githubusercontent.com/6122185/100519084-aca3e680-31bb-11eb-822d-8ed3bf71c390.png)


The environment is considered solved, when the average (over 150 episodes) of those average scores is at least +30. In the case of the plot above, the environment was solved at episode 150, since the average of the average scores from episodes 150 to 200 (inclusive) was greater than +30.

WE can still improve by tuning with the parameters.


