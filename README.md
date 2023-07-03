# Merge-Sort
Sort a given set of n integer elements using Merge Sort method and compute its time 
complexity. Run the program for varied values of n> 5000, and record the time taken to sort. 
Plot a graph of the time taken versus n. The elements can be read from a file or can be generated 
using the random number generator. Demonstrate using C++/Java how the divide-and-conquer 
method works along with its time complexity analysis: worst case, average case and best case.

# ALGORITHM
1.  If p<r 
2.  Then q → ( p+ r)/2 
3.  MERGE-SORT (A, p, q) 
4.  MERGE-SORT ( A, q+1,r) 
5.  MERGE ( A, p, q, r)

# Time Complexities:
Best Case Complexity: The merge sort algorithm has a best-case time complexity 
of O(n*log n) for the already sorted array.

Average Case Complexity: The average-case time complexity for the merge sort 
algorithm is O(n*log n), which happens when 2 or more elements are jumbled, i.e., 
neither in the ascending order nor in the descending order.

Worst Case Complexity: The worst-case time complexity is also O(n*log n), which 
occurs when we sort the descending order of an array into the ascending order.

Space Complexity: The space complexity of merge sort is O(n)
