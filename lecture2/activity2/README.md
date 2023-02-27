# Activities

## Task 1

Refer to the first [link](#links).

- Why is Algorithm Analysis Important?
Algorithm analysis refers to the analysis of the complexity of different algorithms and finding the most efficient algorithm to solve the problem at hand. It is important to decide to choose an algorithm that is more efficient and runs faster.
Analysis of algorithms is the determination of the amount of time and space resources required to execute it.
   -To predict the behavior of an algorithm without implementing it on a specific computer.
    -It is much more convenient to have simple measures for the efficiency of an algorithm than to implement the algorithm and test the efficiency every time a certain parameter in the underlying computer system changes.
    -It is impossible to predict the exact behavior of an algorithm. There are too many influencing factors.
    -The analysis is thus only an approximation; it is not perfect.
    More importantly, by analyzing different algorithms, we can compare them to determine the best one for our purpose.
- Explain the Big $O$ notation
Big-O notation signifies the relationship between the input to the algorithm and the steps required to execute the algorithm. It is denoted by a big "O" followed by an opening and closing parenthesis. Inside the parenthesis, the relationship between the input and the steps taken by the algorithm is presented using "n". It yells how fast an algorithm is.

- Compare `Linear`, `Logarithmic`, `Quadratic` and `Constant` complexities.
# Linear Complexity:- 
The complexity of an algorithm is said to be linear if the steps required to complete the execution of an algorithm increase or decrease linearly with the number of inputs. Linear complexity is denoted by O(n).
  ```python
def linear_algo(items):
     for item in items:
        print(item)

linear_algo([4, 5, 6, 8])
  ```

The complexity of the linear_algo() function is linear in the above example since the number of iterations of the for-loop will be equal to the size of the input items array. For instance, if there are 4 items in the items list, the for-loop will be executed 4 times.
Below the code for linear_algo plot where number of inputs on the x -axis and the number of steps on the y-axis.
```python

steps = []
def linear(n):
    return n
    
for i in range(1, 100):
    steps.append(linear(i))
    
plt.plot(steps)
plt.xlabel('Inputs')
plt.ylabel('Steps')
```



# Lograrithmic Complexity:- O(logn)

Some algorithms achieve logarithmic complexity, such as Binary Search. Binary Search searches for an element in an array, by checking the middle of an array, and pruning the half in which the element isn't. It does this again for the remaining half, and continues the same steps until the element is found. In each step, it halves the number of elements in the array.

When you can make assumptions about the incoming data, you can take steps that reduce the complexity of an algorithm. Logarithmic complexity is desireable, as it achieves good performance even with highly scaled input.

# Quadratic Complexity:- O(n²)

The complexity of an algorithm is said to be quadratic when the steps required to execute an algorithm are a quadratic function of the number of items in the input. Quadratic complexity is denoted as O(n²):
```python

def quadratic_algo(items):
    for item in items:
        for item2 in items:
            print(item, ' ' ,item2)

quadratic_algo([4, 5, 6, 8])
```

We have an outer loop that iterates through all the items in the input list and then a nested inner loop, which again iterates through all the items in the input list. The total number of steps performed is n*n, where n is the number of items in the input array.

# Constant Complexity:- O(C)

The complexity of an algorithm is said to be constant if the steps required to complete the execution of an algorithm remain constant, irrespective of the number of inputs. The constant complexity is denoted by O(c) where c can be any constant number.

Let's write a simple algorithm in Python that finds the square of the first item in the list and then prints it on the screen:


```python
def constant_algo(items):
    result = items[0] * items[0]
    print(result)

constant_algo([4, 5, 6, 8])
```
In the script above, irrespective of the input size, or the number of items in the input list items, the algorithm performs only 2 steps:

    -Finding the square of the first element
    -Printing the result on the screen.

Hence, the complexity remains constant.


## Task2

Refer to the first [link](#links).

- Write a simple algorithm in C++ that finds the square of the first item in a list and then prints it on the screen.
- What is the complexity of the algorithm?

## Task 3

Refer to the first [link](#links).

- Write a simple program that displays all items in a list to the console.
  ```python
   def linear_algo(items):
    for item in items:
        print(item)

   linear_algo([4, 5, 6, 8])
  ```

- What is the complexity of the algorithm?

## Task 4: : Individual, at home

Refer to this [pdf](./big_o.pdf):

- What is the difference between complexity and performance:
- Does complexity affects performance bor is it the other way around?
- Restate the formal definition of big $O$ in plain English

## Links

- [Big O Notation and Algorithm Analysis ](https://stackabuse.com/big-o-notation-and-algorithm-analysis-with-python-examples/)
- [Visualization](https://www.cs.usfca.edu/~galles/visualization/Search.html)
- [Big-O notation explained by a self-taught programmer](https://justin.abrah.ms/computer-science/big-o-notation-explained.html)
- [Big-O is easy to calculate, if you know how](https://justin.abrah.ms/computer-science/how-to-calculate-big-o.html)
- https://cpp.sh/
