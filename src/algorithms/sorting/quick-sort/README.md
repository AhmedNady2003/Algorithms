# Quicksort



Quicksort is a divide and conquer algorithm.
Quicksort first divides a large array into two smaller 
sub-arrays: the low elements and the high elements.
Quicksort can then recursively sort the sub-arrays

The steps are:

1. Pick an element, called a pivot, from the array.
 
3. Partitioning: reorder the array so that all elements with 
values less than the pivot come before the pivot, while all 
elements with values greater than the pivot come after it 
(equal values can go either way). After this partitioning, 
the pivot is in its final position. This is called the 
partition operation.
1. Recursively apply the above steps to the sub-array of 
elements with smaller values and separately to the 
sub-array of elements with greater values.

Animated visualization of the quicksort algorithm.
The horizontal lines are pivot values.

![Quicksort](https://upload.wikimedia.org/wikipedia/commons/6/6a/Sorting_quicksort_anim.gif)
**Example:**
Given array = {40, 21, 8, 17, 51, 34}
Sorted array = {8, 17, 21, 34, 40, 51}
![Quicksort](https://assets-global.website-files.com/5d0dc87aac109e1ffdbe379c/6098e0ecedd39b2d866b18f7_UNUFjEGBUOFu7hddvEXMK5DEkeYLLMhWXdqzY5DBSl11pmM1-x-40H4AOiBhNUOoz2LWVKEJ1TrswXAlFp__MPQI83k8HhHwMwncGgzexxE89FcoqAgcorc95wQZZ0l3iMbmsSdh.png)

## Complexity


| Name                  | Best            | Average             | Worst               | Memory    | Stable    | Comments  |
| --------------------- | :-------------: | :-----------------: | :-----------------: | :-------: | :-------: | :-------- |
| **Quick sort**        | n&nbsp;log(n)   | n&nbsp;log(n)       | n<sup>2</sup>       | log(n)    | No        |  Quicksort is usually done in-place with O(log(n)) stack space |
___
## References

- [Wikipedia](https://en.wikipedia.org/wiki/Quicksort)
- [Interview Kickstart](https://www.interviewkickstart.com/learn/quick-sort)
- [YouTube EN](https://www.youtube.com/watch?v=SLauY6PpjW4&index=28&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)

