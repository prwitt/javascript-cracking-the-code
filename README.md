# Cracking the Coding Interview: JavaScript

Cracking the Coding Interview solutions in JavaScript.

1. [Chapter 1 - Arrays and Strings](#chapter-1-arrays-and-strings)

4. [Chapter 4 - Trees & Graphs](#chapter-4-trees-graphs)

9. [Chapter 9 - Recursion & Dynamic Programming](#chapter-9-recursion-dynamic-programming)

11. [Chapter 11 - Sorting](#chapter-11-sorting)





## Chapter 1 - Arrays and Strings

1.1 Implement an algorithm to determine if a string has all unique characters What if you can not use additional data structures?

1.2 Write code to reverse a C-Style String (C-String means that “abcd” is represented as five characters, including the null character).

1.3 Design an algorithm and write code to remove the duplicate characters in a string without using any additional buffer NOTE: One or two additional variables are fine An extra copy of the array is not.

FOLLOW UP

Write the test cases for this method.

1.4 Write a method to decide if two strings are anagrams or not.

1.5 Write a method to replace all spaces in a string with `‘%20’`.

1.6 Given an image represented by an NxN matrix, where each pixel in the image is 4 bytes, write a method to rotate the image by 90 degrees Can you do this in place?

1.7 Write an algorithm such that if an element in an MxN matrix is 0, its entire row and column is set to 0.

1.8 Assume you have a method isSubstring which checks if one word is a substring of another Given two strings, s1 and s2, write code to check if s2 is a rotation of s1 using only one call to isSubstring (i e , `“waterbottle”` is a rotation of `“erbottlewat”`).



## Chapter 4 - Trees & Graphs

4.1. Implement a function to check if a tree is balanced. For the purposes of this question, a balanced tree is defined to be a tree such that no two leaf nodes differ in distance from the root by more than one.

4.2 Given a directed graph, design an algorithm to find out whether there is a route between two nodes.

4.3 Given a sorted (increasing order) array, write an algorithm to create a binary tree with minimal height.

4.4 Given a binary search tree, design an algorithm which creates a linked list of all the nodes at each depth (i.e., if you have a tree with depth D, you’ll have D linked lists).

4.5 Implement a function to check if a binary tree is a binary search tree.

4.6 Write an algorithm to find the ‘next’ node (i.e., in-order successor) of a given node in a binary search tree where each node has a link to its parent.

4.7 Design an algorithm and write code to find the first common ancestor of two nodes in a binary tree. Avoid storing additional nodes in a data structure. NOTE: This is not necessarily a binary search tree.

4.8 You have two very large binary trees: T1, with millions of nodes, and T2, with hundreds of nodes. Create an algorithm to decide if T2 is a subtree of T1.

4.9 You are given a binary tree in which each node contains a value. Design an algorithm to print all paths which sum up to that value. Note that it can be any path in the tree - it does not have to start at the root.


## Chapter 9 - Recursion & Dynamic Programming


9.1. Write a method to generate the nth Fibonacci number.

OR 9.1. A child is running up a staircase with n steps, and can hop either 1 step, 2 steps, or 3 steps at a time. Implement a method to count how many possible ways the child can run up the staris.

9.2. Imagine a robot sitting on the upper left hand corner of an NxN grid. The robot can only move in two directions: right and down. How many possible paths are there for the robot?

FOLLOW UP

Imagine certain squares are “off limits”, such that the robot can not step on them. Design an algorithm to get all possible paths for the robot.

9.3. A magic index in an array `A[0...n-1]` is defined to be an index such that `A[i] = i`. Given a sorted array of distinct integers, write a method to find a magic index, if one exists, in array A.

FOLLOW UP: WHat if the values are not distinct?

9.4. Write a method that returns all subsets of a set.

9.5. Write a method to compute all permutations of a string.

9.6 Implement an algorithm to print all valid (e.g., properly opened and closed) combinations of n-pairs of parentheses.
EXAMPLE:
input: 3 (e.g., 3 pairs of parentheses)
output: `()()(), ()(()), (())(), ((()))`

9.7. Implement the “paint fill” function that one might see on many image editing programs. That is, given a screen (represented by a 2 dimensional array of Colors), a point, and a new color, fill in the surrounding area until you hit a border of that colour.

9.8. Given an infinite number of quarters (25 cents), dimes (10 cents), nickels (5 cents) and pennies (1 cent), write code to calculate the number of ways of representing n cents.

9.9. Write an algorithm to print all ways of arranging eight queens on a chess board so that none of them share the same row, column or diagonal.


## Chapter 11 - Sorting

11.1 You are given two sorted arrays, A and B, and A has a large enough buffer at the end to hold B. Write a method to merge B into A in sorted order.

11.2 Write a method to sort an array of strings so that all the anagrams are next to each other.

11.3 Given a sorted array of n integers that has been rotated an unknown number of times, give an `O(log n)` algorithm that finds an element in the array. You may assume that the array was originally sorted in increasing order.

EXAMPLE:

Input: find 5 in array `[15 16 19 20 25 1 3 4 5 7 10 14]`

Output: 8 (the index of 5 in the array)

11.4 If you have a 2 GB file with one string per line, which sorting algorithm would you use to sort the file and why?

11.5 Given a sorted array of strings which is interspersed with empty strings, write a method to find the location of a given string.

Example: find “ball” in `[“at”, “”, “”, “”, “ball”, “”, “”, “car”, “”, “”, “dad”, “”, “”]` will return 4
Example: find “ballcar” in `[“at”, “”, “”, “”, “”, “ball”, “car”, “”, “”, “dad”, “”, “”]` will return -1

11.6 Given a matrix in which each row and each column is sorted, write a method to find an element in it.

11.7 A circus is designing a tower routine consisting of people standing atop one another’s shoulders. For practical and aesthetic reasons, each person must be both shorter and lighter than the person below him or her. Given the heights and weights of each person in the circus, write a method to compute the largest possible number of people in such a tower.
EXAMPLE:
Input (ht, wt): `(65, 100) (70, 150) (56, 90) (75, 190) (60, 95) (68, 110)`

Output: The longest tower is length 6 and includes from top to bottom: `(56, 90) (60,95) (65,100) (68,110) (70,150) (75,190)`


