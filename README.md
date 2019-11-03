# Notes

General-purpose notes regarding my learning paths on programming / tech related stuff.

# November - 2019

- 02-11
    - Solved the [No Idea](https://www.hackerrank.com/challenges/no-idea/problem) problem. Tried with sets intersections. Failed. Had to read the problem again. First array could contain duplicates and I turned it into a set. Rewrote it. Time: ~15 min
    - Reviewing the [Big O](./BigO.md) notation.
    - Implemented the [all_unique_chars.py](https://github.com/biancarosa/CtCI/blob/master/all_unique_chars.py) to solve problem 1.1 on CtCI (pg 90) that asks for a implementation of finding all unique chars on a string without using further data structures. Used my own poor hash table implementation. Time: ~15min.
- 03-11
    - Solved the [Merge The Tools](https://www.hackerrank.com/challenges/merge-the-tools/problem) problem. Used a deque and checked unique values in it. Time: ~10 min.
    - Implemented the [check_permutations.py](https://github.com/biancarosa/CtCI/blob/master/check_permutations.py) to solve problem 1.2 on CtCI (pg 90) that asks for a implementation of checking if a string is a permutation of another. Did it with plain old strings in O(n log n) time. My implementation is O(n), the two sorts are 2*(n log n). The complexity is on the sorting.
    - Implemented the [urlify.py](https://github.com/biancarosa/CtCI/blob/master/urlify.py) to solve problem 1.3 on CtCI (pg 90) that asks for a method that substitutes spaces on a string for a %20. Time: ~20min.