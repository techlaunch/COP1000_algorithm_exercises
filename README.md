# COP1000_algorithm_exercises
Challenging algorithm exercises 

1. Write a function that returns the largest element in a list.
2. Write function that reverses a list, preferably in place.
3. Write a function that checks whether an element occurs in a list.
4. Write a function that returns the elements on odd positions in a list.
5. Write a function that computes the running total of a list.
6. Write a function that tests whether a string is a palindrome.
7. Write three functions that compute the sum of the numbers in a list: using a for-loop, forEach and map.
8. Write a function on_all that applies a function to every element of a list. Use it to print the first twenty perfect squares. The perfect squares can be found by multiplying each natural number with itself. The first few perfect squares are 1*1= 1, 2*2=4, 3*3=9, 4*4=16. Twelve for example is not a perfect square because there is no natural number m so that m*m=12. (This question is tricky if your programming language makes it difficult to pass functions as arguments.)
9. Write a function that concatenates two lists. [a,b,c], [1,2,3] → [a,b,c,1,2,3]
10. Write a function that combines two lists by alternatingly taking elements, e.g. [a,b,c], [1,2,3] → [a,1,b,2,c,3].
11. Write a function that merges two sorted lists into a new sorted list. [1,4,6],[2,3,5] → [1,2,3,4,5,6]. You can do this quicker than concatenating them followed by a sort.
12. Write a function that rotates a list by k elements. For example [1,2,3,4,5,6] rotated by two becomes [3,4,5,6,1,2].
13. Write a function that computes the list of the first 100 Fibonacci numbers. The first two Fibonacci numbers are 1 and 1. The n+1-st Fibonacci number can be computed by adding the n-th and the n-1-th Fibonacci number. The first few are therefore 1, 1, 1+1=2, 1+2=3, 2+3=5, 3+5=8.
14. Write a function that takes a number and returns a list of its digits. So for 2342 it should return [2,3,4,2].
15. Write a function that takes a list of strings an prints them, one per line, in a rectangular frame. For example the list ["Hello", "World", "in", "a", "frame"] gets printed as:
```javascript
*********
* Hello *
* World *
* in    *
* a     *
* frame *
*********
```
16. Write function that translates a text to Pig Latin and back. English is translated to Pig Latin by taking the first letter of every word, moving it to the end of the word and adding ‘ay’. “The quick brown fox” becomes “Hetay uickqay rownbay oxfay”.
17. Write a program that outputs all possibilities to put + or - or nothing between the numbers 1,2,…,9 (in this order) such that the result is 100. For example 1 + 2 + 3 - 4 + 5 + 6 + 78 + 9 = 100.
18. Write a program that automatically generates essays for you.
19. Write a program that automatically converts English text to Morse code and vice versa.
20. Write a program that finds the longest palindromic substring of a given string. Try to be as efficient as possible!
21. Given two strings, write a program that efficiently finds the longest common subsequence.
22. Given an array with numbers, write a program that efficiently answers queries of the form: “Which is the nearest larger value for the number at position i?”, where distance is the difference in array indices. For example in the array [1,4,3,2,5,7], the nearest larger value for 4 is 5. After linear time preprocessing you should be able to answer queries in constant time.
23. Given two strings, write a program that outputs the shortest sequence of character insertions and deletions that turn one string into the other.
