# Sorting_Visualizer

This web application demonstrates the workings of various sorting algorithms through visual representation..

Implemented algorithms:
1) Bubble sort: Iteratively compares adjacent elements and swaps them if they are in the wrong order.
Notes: Simple and easy to implement, but inefficient for large datasets.

2) Selection sort: Finds the minimum element from the unsorted portion and swaps it with the first unsorted element.
Notes: Simple, but performs consistently regardless of input data.

3) Insertion sort: Builds the final sorted array one item at a time by inserting each element into its correct position.
Notes: Efficient for small datasets or nearly sorted arrays.

4) Merge sort: Divides the array into halves, recursively sorts each half, and then merges them back together.
Notes: Efficient and stable, but requires additional space for merging.
5) Quick sort: Selects a pivot and partitions the array into two sub-arrays around the pivot, recursively sorting each sub-array.
Notes: Efficient and widely used, but can degrade to O(n^2) if not implemented carefully.\

Features:
1) Color-coded Visulization:
  1.1) Blue:default state
  1.2) Yellow: Elements being compared
  1.3) Red: Elements identified for movement as incorrect position
  1.4) Green: Element in correct positions
2) Controls: 
  2.1) Adjust visualization speed (6 levels)
  2.2) Set data size for sorting
  2.3) Generate new random data
3) Algorithm Analysis:
  3.1) Displays time and space complexities for each algorithm being visualized


