# Linear-Optimization (ISYE 6501)

This is a project regarding an example for linear optimization. It dealts with a diet data that contains food items with each price/serving and nutrient information. The optimization goal is to minimize the cost of 1 meal while maintaining the serving to have sufficient nutrients given that we have a daily minimum and maximum bounds for each nutrient. 

## Question 15.2
In the videos, we saw the “diet problem”. (The diet problem is one of the first large-scale optimization problems to be studied in practice. Back in the 1930’s and 40’s, the Army wanted to meet the nutritional requirements of its soldiers while minimizing the cost.) In this homework you get to solve a diet problem with real data. The data is given in the file diet.xls.

### 15.2.1
Formulate an optimization model (a linear program) to find the cheapest diet that satisfies the 
maximum and minimum daily nutrition constraints, and solve it using PuLP.  Turn in your code 
and the solution. (The optimal solution should be a diet of air-popped popcorn, poached eggs, 
oranges, raw iceberg lettuce, raw celery, and frozen broccoli. UGH!) 

### 15.2.2

Please add to your model the following constraints (which might require adding more variables) 
and solve the new model:  
### a. 
If a food is selected, then a minimum of 1/10 serving must be chosen. (Hint: now you will 
need two variables for each food i: whether it is chosen, and how much is part of the diet.  
You’ll also need to write a constraint to link them.)  
### b. 
Many people dislike celery and frozen broccoli. So at most one, but not both, can be selected.  
### c. 
To get day-to-day variety in protein, at least 3 kinds of meat/poultry/fish/eggs must be 
selected. [If something is ambiguous (e.g., should bean-and-bacon soup be considered 
meat?), just call it whatever you think is appropriate – I want you to learn how to write this 
type of constraint, but I don’t really care whether we agree on how to classify foods!]  
