---
layout: post
title:      "Consider Time Complexity When Coding Solutions"
date:       2018-12-12 22:12:27 +0000
permalink:  consider_time_complexity_when_coding_solutions
---


Time complexity is essentially is just a way to describe the amount of time that it takes to run an algorithm.  And an algorithm is just a defined sequence of steps to solve a problem.  Time complexity is expressed with what is called Big O notation.  There are a multitude of ways to express this specifically, but for the sake of brevity, I’ll only touch on the three most common, and typically the easiest to understand.  Those three are constant time O(1), linear time O(n), and quadratic time O(n^2).

Constant time 0(1), is the ideal solution, as the inputs don’t affect the time it takes to solve the problem.  Although it’s a best case scenario, it isn’t possible with every problem.  An example of this would be a problem where you have to sum all numbers between 1 and n.  The obvious answer would be to use a for loop to iterate through and keep a running total of all the iterations, and then return the total after the loop completes.  However, this isn’t the most efficient solution.  

This solution would be expressed as O(n), or linear time.  In a linear method, the time complexity grows proportionally to the input.  Which could be represented graphically by a line that is roughly 45 degrees.  To solve the aforementioned problem in constant time O(1), you would use the following mathematical formula, assuming that n = 5; return (n *(n+1)) * 2, which would return 15.  This is considered constant time because regardless of the input, the machine still completes the same number of steps.  

This is an important concept to consider in formulating your solutions because if you have a large sized input, you need to make sure the system has the resources to complete the algorithm, so efficiency really must be considered.  

In summary, if the problem can be solved with a mathematical formula, then that is ideal.  If you need to iterate to solve the problem, than single for loops will result in a linear time solution.  The least efficient of the three is quadratic, and that is any solution that incorporates a nested loop.  So in short, avoid nested iterations altogether if possible.  
