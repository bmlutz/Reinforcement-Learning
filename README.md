# Reinforcement Learning
**Introduction to Reinforcement Learning Concepts:**

The basic idea of Reinforcement Learning is that an agent learns through its actions. 
For instance if the agent is a mouse and it finds a piece of cheese in its environment then it is rewarded but if it runs into a cat it is penalized.

In reinforcement learning there are two types of tasks: **Episodic** or **Continuous**

* **Episodic Tasks**: In this scenario we have a starting point and an ending point. This episode then contains a list of states, actions, rewards, and new states.
* **Continuous Tasks**: In this scenario there is no terminal point. The tasks continue forever and the agent learns simultaneously.

There are also two ways of learning which are **Monte Carlo** or **Temporal Difference (TD)** learning.

* **Monte Carlo** learning consists of collecting the rewards at the end of the episode and then calculating the maximum expected future reward.
* **TD** learning consists of estimating the reward at each step.

Let's go back to the mouse example for a second. Imagine an environment where the mouse's starting point is surrounded by infinite amounts of small crumbles of cheese and 
at the other end of the environment is a single very large chunk of cheese but this cheese is also next to a cat. In this scenario the mouse may choose not to explore 
the other end of the environment may exploit the fact that it can peacefully nibble on the available cheese in its immediate surroundings.

This scenario is referred to as the **Exploitation/Exploration** trade-off.

* **Exploration** is finding more information about the environment.
* **Exploitation** is exploiting known information to maximize the reward.

Now that we have touched on some of the main concepts of Reinforcment Learning we will discuss the approaches used to solve the Reinforcement Learning problem.
The three approaches are **Value-Based**, **Model-Based**, and **Policy-Based**.

* **Value-Based**: The goal is to optimize the value function which tells us the maximum expected future reward at each state.
* **Policy-Based**: In this approach we want to directly optimize the policy function without using a value function. The policy defines the agent's behavior at a given time.
* **Model-Based**: This involves modeling the behavior of the environment. 

Markov Property - the agent only needs the current state to make decisions (the past history of all states and actions is irrelevant).

Observiations Space:
* **State**: Complete description of the state of the world and no information is hidden.
* **Observation**: Partial view of the world with some information hidden.

