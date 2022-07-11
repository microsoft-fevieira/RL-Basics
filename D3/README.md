## **Dyna-Q to drop the passenger**

The motive is to train an agent using Dyna-Q to navigate a taxi responsibly. It must pick up the passenger and drop at a specified location.  

<img src='https://github.com/siddarth-c/RL-Basics/blob/main/D3/Figs/taxi.gif' width='400'>


[Taxi - Gym](https://www.gymlibrary.ml/environments/toy_text/frozen_lake/ "Taxi - Gym")


## Dyna-Q

This is a model-based indirect RL technique. Following is the algorithm:

<img src='https://github.com/siddarth-c/RL-Basics/blob/main/D3/Figs/2022-07-10-21-46-23.png' width='800'>

## Results

With just 5 planning steps, the algorithm converges quicker than the naive version. Following are 2 graphs that illustrates the same.

<img src='https://github.com/siddarth-c/RL-Basics/blob/main/D3/Figs/G1.png' width='600'>
<img src='https://github.com/siddarth-c/RL-Basics/blob/main/D3/Figs/G2.png' width='600'>

The tabular 1-step Q learning algorithm takes almost 100 episodes longer to learn the policy learnt by Dyna-Q.

### But naturally, a question arises: How much planning is too much planning?

<img src='https://github.com/siddarth-c/RL-Basics/blob/main/D3/Figs/G3.png' width='600'>
<img src='https://github.com/siddarth-c/RL-Basics/blob/main/D3/Figs/G4.png' width='600'>

From the last graph, it is understood that 25 steps is sufficient to learn the policy in an optimal manner.
