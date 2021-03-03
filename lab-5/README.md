# Coding Lab 5

`Number of problems : 2`</br>
`Time : 45 mins`</br>

### Problem 1
You are given an array prices where prices[i] is the price of a given stock on the ith day.
You want to maximize your profit by choosing a single day to buy one stock and choosing a different day in the future to sell that stock.
Return the maximum profit you can achieve from this transaction. If you cannot achieve any profit, return 0.

> Example 1</br>
`Input: prices = [7,1,5,3,6,4]`</br>
`Output: 5`</br>
Explanation: Buy on day 2 (price = 1) and sell on day 5 (price = 6), profit = 6-1 = 5.
Note that buying on day 2 and selling on day 1 is not allowed because you must buy before you sell.

### Problem 2
Implement a class called FreqStack which simulates the operation of a stack-like data structure.
FreqStack has two functions:
	- `push(int x)`, which pushes an integer x onto the stack.
    - `pop()`, which removes and returns the most frequent element in the stack.

If two elements have the same frequency then the element closest to the top of the stack is removed and returned.
>`Example 1`</br>
`Command            Stack          Result`</br>
`f = FreqStack()        []          []`</br>
`f.push(5)              []          [5]`</br>
`f.push(7)              []          [5,7]`</br>
`f.push(5)              []          [5,7,5]`</br>
`f.push(7)              []          [5,7,5,7]`</br>
`f.push(4)              []          [5,7,5,7,4]`</br>
`f.push(5)              []          [5,7,5,7,4,5]`</br>
`f.pop()                []          Return 5`</br>
`f.pop()                []          Return 7`</br>
`f.pop()                []          Return 5`</br>
`f.pop()                []          Return 4`</br>
