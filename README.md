# escape_room_q_learning
Implementation of Q-Learning, an off-policy temporal difference (TD) learning algorithm, for a simple escape room environment

## Environment

The environment is a one-dimensional room with a hidden switch. Uppon pressing the switch at location *a*, the room can be exited through a door at a different location *b*. Possible actions are left/right movement and a *press* action. Pressing has no effect unless the agent is located at the position of the hidden switch. At time *t*, the agent is rewarded with a reward of 1 if the room has been exited and -1 otherwise. The environment is completely deterministic.

## Algorithm

Q-Learning is a model-free algorithm to find the optimal policy in a Marco Decision Process (MDP). For more information refer to [Reinforcement Learning:
An Introduction, Sutton&Barto, 2014/2015](https://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf).

