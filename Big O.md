# Big O
> Big O is the language metric we user to decribe the efficiency of algorithms.

**Time Complexity :** A way of showing how the runtime of a function increases as the size of input increases
- we are measuring the number of operations in time complexity , not actual running time
**Space Complexity:** the amount of the memory that some code used

**Types of Runtimes:**
- O(N)
- O(N<sup>2</sup>)
- O(2<sup>N</sup>)

## Big O Notations - Theta, Omega and Big O
Best case is Omega -its a complexity that is going to be less or equal to the best case
Average case is Theta -its a complexity that is within bounds of the worst and the best cases
Worst Case is Big O - its a complexity that is going to be less or equal to the worst case

## Runtime Complexities

### O(1)
- Constant Time Complexity alos called Order of one
- any given input , the execution will not change. it remains constant
- like simple add numbers like function
```python
def multiply(n):
  return n*n
```
### O(n)
- Linear time complexity
- time complexity will grow in direct proportion to the size of input data.
- 
