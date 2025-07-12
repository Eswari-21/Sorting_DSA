# Sorting_DSA

## Selection
Divides the input list into two parts: a sorted sublist and the remaining unsorted sublist. 
It repeatedly selects the minimum element from the unsorted sublist and swaps it with the first element of the unsorted sublist.
Time Complexity: O(n^2)
Space Complexity: O(1)

## Insertion
Builds the final sorted array one item at a time. It is much less efficient on large lists than more advanced algorithms such as quicksort, heapsort, or merge sort
Time Complexity: O(n^2) in the worst case, O(n) in the best case
Space Complexity: O(1)

## Bubble
Compares adjacent elements and swaps them if they are in the wrong order. The pass through the list is repeated until the list is sorted.
Time Complexity: O(n^2)
Space Complexity: O(1)

## Quick
A divide-and-conquer algorithm. It picks an element as a pivot and partitions the given array around the picked pivot.
Time Complexity: O(n log n) on average, O(n^2) in the worst case
Space Complexity: O(log n) on average, O(n) in the worst case

## Counting
A non-comparison-based sorting algorithm that sorts elements by counting the occurrences of each unique element in the input array.
Time Complexity: O(n + k), where k is the range of the input
Space Complexity: O(k)

## Radix
A non-comparison-based sorting algorithm that sorts numbers by processing individual digits.
Time Complexity: O(nk), where k is the number of digits
Space Complexity: O(n + k)

## Heap
A comparison-based sorting technique based on the Binary Heap data structure. It is similar to selection sort, where we first find the maximum element and place it at the end. We repeat the same process for the remaining elements.
Time Complexity: O(n log n)
Space Complexity: O(1)
