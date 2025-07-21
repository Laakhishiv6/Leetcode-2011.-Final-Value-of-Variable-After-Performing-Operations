# Leetcode-2011.-Final-Value-of-Variable-After-Performing-Operations
# Description
There is a programming language with only four operations and one variable X:

++X and X++ increments the value of the variable X by 1.
--X and X-- decrements the value of the variable X by 1.
Initially, the value of X is 0.

Given an array of strings operations containing a list of operations, return the final value of X after performing all the operations.

 # Solution
 Given:
 An array named operations which contains the operations to perform
 Operations:
++X and X++ increments the value of the variable X by 1.
--X and X-- decrements the value of the variable X by 1.

1. The initial value of the variable x is 0.
2. Loop through the array operations and read the operations.
3. If the operation is ++X OR X++ then increment the value by 1
4. If the operation is --X or X-- then decrement the value by 1
5. Return the final value of x.

Example 
Input: operations = ["++X","++X","X++"]
Output: 3
Explanation: 
Initially, X = 0.
++X: X is incremented by 1, X = 0 + 1 = 1.
++X: X is incremented by 1, X = 1 + 1 = 2.
X++: X is incremented by 1, X = 2 + 1 = 3.
