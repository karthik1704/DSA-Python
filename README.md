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
    - Primitive 
        - Provide by Programming Language
        - Integer
        - Float 
        - Character
        - String
        - Boolean
    - Non-Primitive
        - User-defined DS ,
        - it's Derived from primitive data types by combining two or more primitive DS
        - Subdivided as,
            - Linear
                - the data items arranged in memory in a linear , sequential manner
                - Either static or dynamic
                - Static
                    > sizes and structures associated memory locations are fixed, at compile time
                    - Array
                - Dynamic
                    > Associated memory locations change.
                    - Linked List
                    - Stack
                    - Queue
            - Non-linear
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