basic Reinforcement learning repo.
source: https://www.kaggle.com/osbornep/-reinforcement-learning-from-scratch-in-python/
In this problem, we may throw from any position in the room but the probability of it is relative to the current distance from the bin and the direction in which the paper is thrown. Therefore the actions available are to throw the paper in any 360 degree direction or move to a new position to try and increase the probability that a throw made will go into the bin.

We first introduce the problem where the bin's location is known and can be solved directly with Value-Itearation methods before showing how RL can be used similarly to find the optimal policy if the probabilities are hidden in later notebooks.

Furthermore, we introduce the option to add control to the environment where, for example, we can punish the algorithm less for missed throws so that the algorithm will take higher risks.

Lastly, we demonstrate how the envrionment can be changed and, for example, may have walls blocking throws from certain positions.
