# Searching_Algorithms
The basic searching algorithms - linear search and binary search.


Linear Search : 
--------------------
a. This function accepts an array and a value

b. Loop through the array and check if the current array element is equal to the value

c. If it is, return the index at which the element is found

d. If the value is never found, return -1

Big O Complexity of linear search
----------------------------------------
Best Case - o(1)

Average Case - O(n)

Worst Case - O(n)

Binary Search
------------------------
a. Binary search is a much faster form of search

b. Rather than eliminating one element at a time, you can eliminate half of the remaining elements at a time

c. Binary search only works on sorted arrays!

Binary Search Pseudocode : 
-----------------------------
a. This function accepts a sorted array and a value

b. Create a left pointer at the start of the array, and a right pointer at the end of the array

c. While the left pointer comes before the right pointer:

d. Create a pointer in the middle

 	  i. If you find the value you want, return the index
	 
	  ii. If the value is too small, move the left pointer up
	
	 iii. If the value is too large, move the right pointer down
 
	  iv. If you never find the value, return -1
	  
Big O Complexity of linear search
----------------------------------------
Best Case - o(1)

Average Case - O(logn)

Worst Case - O(logn)
