
# Project Report: Continuous Control - DDPG DRL algorithm 

### Introduction

For this project, an intelligence agent is trained to control a double-joined arm to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible. After training for only 12 episode, the average score of the 20 agents reaches above 30.

### Algorithm
Deep Deterministic Policy Gradients (DDPG) is a policy-gradient actor-critic algorithm. It is off-policy and model-free. The Actor-Critic learning algorithm is applied to represent the policy function independently of the value function. The policy network that generate the action given an input state is known as the Actor; and the value network that generate the value giveninput state and action is known as Critic. The detailed algorithm is introduced as below two figures:
![results](actor-critic.png)
![results](DDPG.png)

### Model Architechture




Note that your project submission need only solve one of the two versions of the environment. 

### Hyperparameters

### Results
The recored of the training process is plotted as below:

![results](scores.png)

The trained agent can catch the motion of the balls very well.
![results](Reacher_trained_agent.gif)

### Further Improvements
