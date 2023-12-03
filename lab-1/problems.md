# Coding Problems

`Number of problems : 2`</br>
`Time : 45 mins`</br>

### Problem 1 - Peak Finding

An array A is called a mountain array if it has a peak at index p such that:
`A[0] < A[1] < ... < A[k] > A[k + 1] > ... A[A.length - 1]`

Given a mountain array, return the peak value.</br>

> Example 1</br>
`Input: arr = [1, 3, 8, 13, 21, 18, 8]`</br>
`Output: 4` (Index 4 contains the peak element 21)</br>

### Problem 2 - Balanced Parentheses

Many algebraic expressions make use of paranthesis. Ex
`(3x + 2)y + 10, [(x + y)10 - {1 + (x / 9)}]`
These paranthesis maintain a valid order otherwise the expression cannot be computed and hence invalid. You are given a string only containing parantheses symbols,
`( ) { } [ ]`
You have to determine if the parantheses are balanced.

> Example 1</br>
`Input: (){}[]`</br>
`Output: True`</br>

> Example 2</br>
`Input: ({[]})`</br>
`Output: True`</br>

> Example 3</br>
`Input: ({[]}[]{()})`</br>
`Output: True`</br>

> Example 4</br>
`Input: {`</br>
`Output: False`</br>

> Example 5</br>
`Input: ()]`</br>
`Output: False`</br>