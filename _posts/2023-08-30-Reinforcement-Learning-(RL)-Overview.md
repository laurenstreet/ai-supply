---
title: "Reinforcement Learning (RL) Overview"
permalink: /rl-overview/
date: 2023-08-30
classes: wide
---

In RL algorithms [[1]](https://mitpress.mit.edu/9780262039246/reinforcement-learning/), use is made of an agent that interacts with an environment by moving from one state to another through possible actions and is rewarded based on its actions.  The reward then motivates future actions (through a policy which maps one state to another), which are then rewarded, and so on until some threshold has been met. 

More specifically, RL algorithms are Markov decision processes defined by the set $$(\mathcal{S},\mathcal{A},\mathcal{P},\mathcal{R})$$.  Here, $$\mathcal{S}$$ defines all possible states that the agent can choose, $$\mathcal{A}$$ defines all possible actions to go from one state to another state, $$\mathcal{P}$$ defines the probability of transitioning from one state to another, and $$\mathcal{R}$$ defines the reward function for taken any given action.

In an RL algorithm, the possible states can be something like the points on a 2D spatial grid.  The policy which maps one state to another is commonly a neural network that takes a state as input and outputs a probability map for all possible actions.  The agent then chooses an action based on the policy and the next state is given some reward (obtained from the reward function).  The process is generally repeated some maximum number of transitions is made, or until a maximum reward is obtained.

For RL algorithms that utilize episodic learning, the transition from the initial state to the final state constitues a single episode with a given episode ending when some threshold is met (like a maximum number of transition steps or a maximum reward) and with multiple episodes occuring during a training session. In batch training, the policy is updated some number of times (called the batch size) during each episode.

The environments of an RL algorithm typically contain both a state space and the action space, with the state space representing all possible states that can be explored by the agent and the action space representing all possible actions the agent can take.  This is something that has implemented extensively in the world of RL, with many examples being available in, for example, the environments of the OpenAI gyn [[]]().  Many of these environments have been used to test and tune available algorithms in a repository of common RL algorithms, Stable Baselines3 [[]]().

The environment also contains definitions for transforming from one state to another given an input action, and the reward for a given state.  The agent's choice of action is typically based on a probability distribution, found as the output of a neural network.