This is the introduction to Deep Reinforcement Learning.

Here is some basic information about Stanford DRL course:

|Course Name|CS294: Deep Reinforcement Learning, Spring 2017|
|---|---|
|Teaching Apt|Stanford University|
|Instructor|Sergey Levine, John Schulman, Chelsea Finn|
|Course Material|http://rll.berkeley.edu/deeprlcourse|
|Chapter Name|Introduction to Deep Reinforcement Learning|
|Reference Materials|http://rll.berkeley.edu/deeprlcourse/docs/lec0.pdf|

# Why Deep Reinforcement Learning?
Deep means it can process more complex sensory input while reinforcement learning means it can choose complex actions. DRL is a method to solve complex problems with complex sensory.

# What can DL and RL do well now?
- Acquire high degree of proficiency in domains governed by simple, known rules.  >> Efficiency >> AlphaGo
- Learn simple skills with raw sensory input, given enough experience.  >> Transfer Learning
- Learn from imitating enough human-provides expert behaviors.    >> Imitation Learning

# What has proven challenging so far?
- Humans can learnig incredibly quickly while DRL methods are usually slow.
- Humans can reuse past knowledge whiel Transfer learning in DRL is an open problem.
- Not clear what the reward function should be
- Not clear what the role of prediction should be.

# What is Deep Reinforcement Learning?
Reinforcement learning is the interaction between agent and raw environment. The agent has its action towards the environment after observation. And then, the environment give award toward the action. The target for agent is to maximize the award by adapting actions.

DRL is reinforcement learning using neural network to approximate functions. includiing:
- Policies: select next action
- Value functions: measures goodness of state and state-action pairs
- Dynamic Models: predict next state and reward -----  is it means next action towards next state?

# Difference between RL and supervised learning
For reinforcement learning:
- You don't have full access to the function you are trying to optimize--must query it through interaction.
- Interacting with a stateful world: input xt depend on your previous actions.







