I used A* search method. 

For heuristic function, i used manhattan distance and write a function which is calc_manhattan. 

For path cost, the step number is used.

## How its working?

Everything happens in a while loop.

When the solution is equal to the goal, the loop ends. 

The algorithm starts with the initial state.

The available actions for the initial state is found and the states after taking these action are found.

The costs are found for the next steps and added to the states_list.

States_list is sorted by the costs and the next state is chosen by looking for the least cost.

The available actions found for this new state and goes like this.