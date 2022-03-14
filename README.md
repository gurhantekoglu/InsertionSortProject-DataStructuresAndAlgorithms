# InsertionSortProject-DataStructuresAndAlgorithms

**[22,27,16,2,18,6] -> Insertion Sort**

1. Write the stages of the above sequence according to the sort type.

```
0. [22,27,16,2,18,6] - n
1. [2,22,27,16,18,6] - n-1
2. [2,6,22,27,16,18] - n-2
3. [2,6,16,22,27,18] - n-3
4. [2,6,16,18,22,27] - 1
```

2. Write the Big-O notation.

```
Since n+(n-1)+(n-2)+...+1, Big-O notation is O(n^2).
```

3. Time Complexity: Average case: The number we are looking for is in the middle, Worst case: The number we are looking for is at the end, Best case: The number we are looking for is at the beginning of the series.

4. What case does the number 18 fall into after the array is sorted? Write.

```
Average case because after the series is sorted, the number 18 is in the middle.
```

**Write the first 4 steps of [7,3,5,8,2,9,4,15.6] according to Insertion Sort.**

```
0. [7,3,5,8,2,9,4,15.6] - n
1. [2,7,3,5,8,9,4,15,6] - n-1
2. [2,3,7,5,8,9,4,15,6] - n-2
3. [2,3,4,7,5,8,9,15,6] - n-3
4. [2,3,4,5,7,8,9,15,6] - n-4
...
```
