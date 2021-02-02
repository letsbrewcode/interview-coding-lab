# Lab 3

## Rules</br>
1. Don't use IDE. Write psuedocode and/or code in a text editor that can support syntax highlighting but not more. You can use sublime or nodepad++.</br>
2. Don't execute your code till you are done. One of the main purpose of this exercise it to develop practice of writing code that is </br>
   - Syntactically correct</br>
   - works on testcases (This can be challenging)</br>
3. Once you are done writing code, copy it to an IDE and execute it. Check for what errors come during execution.</br>
4. Fix your code and repeat the process. Keep a count of number of mistakes that were made. Objective is to reduce these errors.</br>

### Number of questions: 2
### Time: 45 mins
</br>

## Problem 1

You are given two binary trees. You have to find out if the leaves of these two trees form a similar sequence.</br> For reference, consider following examples</br>

> Example 1 (Passing case)</br>
<img src="https://github.com/letsbrewcode/interview-coding-lab/blob/master/lab-3/resources/leaf-similar-trees-pass.png" width="700">

> Example 2 (Failing case)</br>
<img src="https://github.com/letsbrewcode/interview-coding-lab/blob/master/lab-3/resources/leaf-similar-trees-fail.png" width="500">

 - Write a method that returns True if the leaves of trees form same sequence, else it returns False
 - What is the time and space complexity of your code?

</br>
</br>

## Problem 2

Consider an array of length n consisting of numbers. Find a index of any number that is strictly greater than previous and next number. So essentially you have to return the index i 
where `arr[i - 1] < arr[i] < arr[i + 1]`. There may be many such numbers. In that case return the index of any such number.</br>

You can imagine the values outside the bounds of array as -\infty. So `arr[-1] = arr[n] = -\infty`

> Example 1</br>
`Input: arr = [1, 3, 2, 5, 7, 9, 8]`</br>
`Output: 1 or 5`</br>

> Example 2</br>
`Input: arr = [1, 3, 9, 13]`</br>
`Output: 3`</br>
