# Reinforcement Learning 
## Lectured by Deeplizard at 'https://www.youtube.com/channel/UC4UJ26WkceqONNF5S26OiVw' on February 2020
> Some adaptations implemented on display calls

## Description

This project is a result of learning lessons about reinforcement learning.
The objective of this study was to better understand how the reinforcement was calculated, and how to implement such usin pytorch.

The first example was of the frozen lake game where basically an agent should traverse a frozen lake full of holes in order to reach its goal. Here we can understand the basics of markovian decision process, environment mapping, rewards, policies, and the bellman equation. Also the dynamic programming structure that will help us out, the Q Table, where we store and update the rewards from each state to another based upon an action on a given state to another, i.e., the policy we want to optimize.

The second example is the cart pole game, where we need to balance a pole on a cart. Here deep neural networks were used to discover the optimal policy. Two were required due to the bellman's equation needing a current reward, and a target reward, i.e. two variables to optimize.

Very informative and interesting, thanks Deeplizard.

