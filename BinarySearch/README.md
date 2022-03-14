# Binary Search

Binary Search is a searching algorithm used in a sorted array by repeatedly dividing the search interval in half. The idea of binary search is to use the information that the array is sorted and reduce the time complexity to O(Log n).

##### Binary Search Algorithm: The basic steps to perform Binary Search are:

1. Begin with an interval covering the whole array.
2. If the value of the search key is less than the item in the middle of the interval, narrow the interval to the lower half.
3. Otherwise, narrow it to the upper half.
4. Repeatedly check until the value is found or the interval is empty.

##### Formula for calculating the Middle element of an array.

``` int mid = low + (high – low)/2;