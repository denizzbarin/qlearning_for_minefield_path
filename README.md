# qlearning_for_minefield_path
The purpose of this study is to find a path from a predefined base state to some reward state where passing through certain states in between lead to penalty. Set states are two dimensional 10 grids in 
X-axis and 5 grid in Y-axis. The purpose is to obtain a policy such that the agent will travel from the first state to the last by finding the shortest path and without passing through the forbidden states 
which are called minefields. This will be achieved through by giving the final state a positive value and penalizing minefield states.

![Reward Image vs. Suggested Policy](https://github.com/denizzbarin/qlearning_for_minefield_path/blob/main/qlearning_minefield.png)
