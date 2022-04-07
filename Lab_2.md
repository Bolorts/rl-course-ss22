# Lab 2

In this second lab we implement the `policy iteration algorithm` that we saw in the lecture, in order to find the best policy for the `FrozenLake` environment.

### Task:
- Create a new file and use the slippery environment of `FrozenLake`, i.e. `env = gym.make("FrozenLake-v1", is_slippery=True)`
- Implemente the `policy iteration algorithm` that we saw in the lecture to finde the best policy.
Hint: You can access the transition probabilty matrix of the environemnt with `env.env.P` , all states with `env.env.nS` and all actions with `env.env.nA`.
