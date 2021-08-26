# DSA - Python
    - Data structures and algotithms in Python
## Data structures
> Data stuctures are different ways of organizing data on your computer that can be used effectively.

## Algorithm
> Set of steps to accomplish a task
- Set of rules for a computer program to accomplish a task
### Good algorithm 
- Correctness 
- Efficiency

## Importance of DSA
- Data structures refers to the way we organize information on computer/data 
- Algorithm is  steps we need to in order to get the output correctly and efficienly.

## Type of data structure
- 2 Basic DS
    - **Primitive** 
        - Built-in, Provide by Programming Language
        - Integer
        - Float 
        - Character
        - String
        - Boolean
    - **Non-Primitive**
        - User-defined DS ,
        - it's Derived from primitive data types by combining two or more primitive DS
        - Subdivided as,
            - **Linear**
                - the data items arranged in memory in a linear , sequential manner
                - Either static or dynamic
                - **Static**
                    > sizes and structures associated memory locations are fixed, at compile time
                    - Array
                - **Dynamic**
                    > Associated memory locations change.
                    - Linked List
                    - Stack
                    - Queue
            - **Non-linear**
                > The data item is connected to  several other items , they are not organized squentially.
                - Possible for a data item to connected with more than one data items.
                - Graph 
                - Tree

## Types of algorithm
- Simple Recursive algorithms
    - Recursive - Function calls itself
- Divide and conquer algorithms
    - Divide the problem into smaller algoriths of the same type, and solve these subproblems recursively
    - Combine the solutions to the subproblems into a solution to the original problem
    - Traditionally, an algorithm is called divide and  conquer - if it contains atleast two recusive calls
    - Examples
        - Quick sort
        - Merge sort 
- Dynamic programming algorithms
    - Work based on memoization(?),
    - To find the best solution
    - these algorithms remembers the past results use them to find new results.
    - Generally used for optimization probelms.
    - Goal is to find the best solution among multiple solutions.
- Greedy algotithms
    - Also, for finding best solution
    - Works in phases
    - at each phases we take the best we can without worring about future consequences.
    - We hope that by choosing a local optimum solution at each step ,  we will end up at a global optimum solution.

- Brute force algorithms
    - It simply tries all possibilities until a satisfactory solution is found.

- Randomized algorithms
    - Use a random number at least once during the computation to make a decision.

## Recursion
> it's a way of solving a probelm by having a function calling itself.
- it's a method of solving a problem where the solution depends on the solution to the smaller instance of same probelm.
- such probelms can be solved by iteration as well.
- Real-life example Russian Doll
- Properties: 
    - Performing the same opration multiple times with different inputs
    - In  every step we try smaller inputs to make the problem smaller.
    - Base condition is needed to stop recursion, otherwise infinite loop wil occur.
> A programmer's wife tells him as he leaves the house: " While you're out, buy some milk."
He never returns home and the universe runs out of milk.

```python
def openRussianDoll(doll):
    if doll === 1: #Base condition
        print('All dolls are opened')
    else:
        openRussianDoll(doll-1) # Recursion
```

### Why Recursion
- Recursive thinking is really important in programming and it helps you break down big probelms into smaller ones and easier to use
- Recursive solution can be simpler to read than - iterative one
- Recusion used all the  time every language , every field
- easy to write compare to iterative(loops) code
- we can use all the place Recursion over iterative - because some situations  iteration fast

#### When to choose recursion?
- If you can divide the problem inti simialr problems
- (important) subproblems must be similar
    -  Design an algorithm to  compute nth(?)...
    - Write code to  list the n...
    - implement a method to compute all.
    - pratice(Pratice more you know)
- The prominent usage of recursion in DS like trees and graphs.
- Used in many algorithms
    - DnC (Divide and conquer)
    - greedy 
    - dynamic programming

### How recusion work?
- 2 conditions
    - A conditions where method calls itself with samller values.
    - Exit from infinite loop.

```python
def recursionMethod(parameters):
    if exit from condition satisfied: #base condition
        return somevalue # break from loop
    else:
        recursionMethod(modified Parameter)
```
