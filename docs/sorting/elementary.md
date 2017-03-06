Elementary Sorts
================

## Insertion Sort

*Invariant*: all sorted elements are in sorted order.

- Running time depends on ordering of elements (how sorted the array is)
- Best case: $$n-1$$ compares and $$0$$ swaps
- Worst case: $$~\frac{n^2}{2}$$ compares and $$~\frac{n^2}{2}$$ swaps

## Selection Sort

Find smallest unsorted element in array and replace with the first unsorted element.

1. Find smallest element in array and replace with first element.
2. Find second smallest element in array and replace with the second element.
3. Continue until entire array is sorted.

*Invariant*: all sorted elements are in the final position.

- Running time is insensitive to input
- Data movement is minimal: linear to size of array
