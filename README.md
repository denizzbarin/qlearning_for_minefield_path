# Q-LEARNING FOR FINDING SHORTEST MINEFIELD PATH
The purpose of this study is to find a path from a predefined base state to some reward state where passing through certain states in between lead to penalty. Set states are two dimensional 10 grids in 
X-axis and 5 grid in Y-axis. The purpose is to obtain a policy such that the agent will travel from the first state to the last by finding the shortest path and without passing through the forbidden states 
which are called minefields. This will be achieved through by giving the final state a positive value and penalizing minefield states.

![Reward Image vs. Suggested Policy](https://github.com/denizzbarin/qlearning_for_minefield_path/blob/main/qlearning_minefield.png)

As the first image shows above, the purpose is to navigate through $(4,0)$ to $(0,9)$. The final state gives a reward of $1000$ and states highlighted in black penalizes by $-100$. The rest of the states are neutral. The second image shows the path of optimal policy. See the $.ipynb$ notebook for further details.
