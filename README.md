README
Almost Sorted

Given an array of distinct integers, determine whether it can be sorted in ascending order using exactly one operation:

Swap two elements.
Reverse one contiguous subarray.
Approach
Create a sorted copy of the array.
Find all indices where the original array differs from the sorted array.
Try:
Swapping the first and last mismatched elements.
Reversing the entire mismatched segment.
If either operation produces the sorted array, print the corresponding operation.
If both are possible, choose swap.
Otherwise, print no.
Complexity
Time: O(n log n)
Space: O(n)
Example

Input:

6
1 5 4 3 2 6

Output:

yes
reverse 2 5

The subarray [5, 4, 3, 2] is reversed to obtain the sorted array.
