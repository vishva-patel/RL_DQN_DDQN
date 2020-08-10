# Project 2
## Implementing Value Function Approximation Algorithms - Deep Q Learning (DQN) and Double DQN (DDQN)

CSE4/510: Introduction to Reinforcement Learning

Fall 2019

Instructor: Alina Vereshchaka

Project 2 - Value Function Approximation

Due Date: Sunday, October 27, 11:59pm1


## Project Overview

The goal of the project is to explore OpenAI Gym environments and implement value function approximation
algorithms. In the first part of the project we will implement deep Q learning (DQN), following DeepMind’s
paper that explains how reinforcement learning algorithms can learn to play Atari from raw pixels. The
purpose of this project is to understand the effectiveness of deep neural networks as well as some of the
techniques used in practice to stabilize training and achieve better performance. We will train our networks
on two OpenAI gym environments. In the second part of the project we will implement an improvement to
the DQN algorithm, focusing on Double Deep Q-learning (DDQN) or Prioritized Experience Replay (PER).


## Part 1 [80 points] - Implementing and applying DQN
### 1.1 Implement DQN [40 points]

Implement DQN from scratch following DeepMind’s paper ([mnih2015human] and [mnih-atari-2013]). You
may use Keras/Tensorflow/Pytorch. Quesitons to discuss:

• What is the benefit of using experience replay?

• What is the benefit of the target network?

• What is one benefit of representing the Q function as q̂(s, w)?

### 1.2 Apply DQN to OpenAI Gym Environments [20 + 20 points]

Test your DQN algorithm on any TWO OpenAI Gym environments. Compare the results. Describe the
OpenAI Gym environments that you used (e.g. possible actions, states, agent, goal, rewards, etc). Provide
reward dynamics (average reward in t-steps).

OpenAI Gym suggested environments:

• CartPole

• Atari Breakout

• MsPacman

• MountainCar

• Space Invadors

## Part 2 [20 points] - Improving DQN

DQN had a lot of success in applications in various domains. Some improvements have also been done to the
vanilla (DQN) algorithm. In this part we will implement one of improved algorithms that is based on DQN.
Modify your DQN code from Part 1.1 to one of the improved version and apply it to ONE environment, that
was used in Part 1.2.

Algorithm, that built on top of vanilla DQN:

• Double DQN

• Dueling DQN

• Prioritized Experience Replay (PER)
