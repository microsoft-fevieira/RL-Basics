## About

**Cliff Walking using SARSA and Q Learning**

Our goal is to find a policy that takes the agent from *S* to *G*. More information on this environment could be found [here](https://www.gymlibrary.ml/environments/toy_text/cliff_walking/ "here")

![](https://github.com/siddarth-c/RL-Basics/blob/main/D1/Figs/CliffWalking.png)

------------


## Observation

Following are the policies learnt by SARSA and Q Learning.
![](https://github.com/siddarth-c/RL-Basics/blob/main/D1/Figs/Policy%20Learnt.png)

Note that while SARSA takes a longer but safer route, Q learning takes the optimal path. This could be attributed to Q Learning's off-policy learning. SARSA approaches convergence allowing for possible penalties from exploratory moves, whilst Q-learning will ignore them. 

![](https://github.com/siddarth-c/RL-Basics/blob/main/D1/Figs/Graph.png)

Though Q Learning learns the optimal policy, due to the random actions taken due to epsilon greedy, its online performace is poor.
