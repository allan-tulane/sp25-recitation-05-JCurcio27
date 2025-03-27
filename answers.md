# CMPS 2200 Reciation 5
## Answers

**Name:** Jaedan Curcio


Place all written answers from `recitation-05.md` here for easier grading.







- **1b.**
The runtime results of the qsort algorithm align with the expected results of an average 
quicksort algorithm, running slower than linear with an asymptotic bound of O(n log n).
The speed of this algorithm is dependent on how close to being sorted to begin with, with the best
case runtime (a nearly sorted list) being O(n log n), but the worst case being O(n^2) (a reverse-sorted)
list.



- **1c.**
Based on the results of my code, Tim sort runs much faster than both quicksort conditions, by an 
average of 10x. While both algorithms have an average runtime of O(n log n), Timsort's best case
and worst case time complexity (O(n) and O(n log n)) are both much faster than quicksort's best/worst
cases, which is a likely explanation for the results.