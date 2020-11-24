# CS285 hw4

## Question 1

### Histrogram vs No Exploration
![q1](./run_logs/q1.png "Q1")

## Question 2

### RBF vs No Exploration
![q2](./run_logs/q2.png "Q2")

## Question 3

### EX2 vs No Exploration
![q3](./run_logs/q3.png "Q3")

## Question 4

### EX2 vs No Exploration
![q4](./run_logs/q4.png "Q4")

It can be seen that the setting where bonus weight is 0.001 requires longer iterations to surpass the baseline setting where no exloration strategy is used. High bonus weight of 0.001 encourages the agent to explore suboptimal states rather than exploiting the known optimal states. For the setting with small bonus weight, the agent is more greedy than the previous agent causing the performance to surpass the baseline setting after iteration 30.
