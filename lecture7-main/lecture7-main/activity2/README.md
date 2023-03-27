# Activities

## Task 1

- Refer to the following link. Discuss the characteristics of Greedy approach:
    Optimal substructure property. 

    Minimization or Maximization of quantity is required.

    Ordered data is available such as data on increasing profit, decreasing cost, etc.

    Non-overlapping subproblems.

  https://www.geeksforgeeks.org/greedy-approach-vs-dynamic-programming/

## Task 2

- Explain how the code in `./src/fkp.cp`p works. Refer to the following link:
The code works for Fractional Knapsack Problem using Greedy Algorithm in which first calculate the ratio(value/weight) for each item. Then sort the items in the decreasing order of the ratio. 
Initialize res =0, curr_cap = given_cap.
Do the following for every item “i” in the sorted order:
If the weight of the current item is less than or equal to the remaining capacity then add the value of that item into the result
Else add the current item as much as we can and break out of the loop.
Return res
  https://www.geeksforgeeks.org/fractional-knapsack-problem/

## Task 3

- Explain how the code in `./src/asp.cpp` works. Refer to the following link:
  https://www.geeksforgeeks.org/activity-selection-problem-greedy-algo-1/

## Task 4: Individual (at home)

- Refer to the following link. Explain the differences between Greedy Algorithm and Dynamic Programming

Both are used for to solve optimization problems. But they have some differences. 
(1)In Greedy approach, we make choices that are best at the moment in the hope that will lead to global optimal solution.
In dynamic programming, we make decisions at every step considering current problem and solution to previuosly solved sub problem to calculate optimal solution.

(2) In Greedy approach, there is no such guarantee of setting Optimal solution. 
 In DP, it is guaranteed that it will generate an optimal solution as it considers all possible cases and then choose the best.

 (3) Greedy is faster. DP is generally slower.

 (4) Greedy: Fractional knapsack. DP: 0/1 knapsack problem.
  https://www.geeksforgeeks.org/greedy-approach-vs-dynamic-programming/

## Link(s)

- https://cpp.sh/
