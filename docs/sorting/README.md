Sorting
=======

Sorting is the process of rearranging a sequence of objects into some logical order.

- [Elementary Sorts](elementary.md)
- [Mergesort](mergesort.md)
- [Quicksort](quicksort.md)
- [Heapsort](heapsort.md)
- [Counting Sorts](counting.md)

| Name | Best case | Worst case | Stable? | In-place? |
|------|-----------|------------|---------|-----------|
| Insertion | $$ O(n) $$ | $$ O(n^2) $$ | Yes | Yes |
| Selection | $$ O(n^2) $$ | $$ O(n^2) $$ | No | Yes |
| Mergesort | $$ O(n\,\text{log}\,n) $$ | $$ O(n\,\text{log}\,n) $$ | Yes | No |
| Quicksort | $$ O(n\,\text{log}\,n) $$ | $$ O(n^2) $$ | No | Yes |
| Heapsort | $$ O(n\,\text{log}\,n) $$ | $$ O(n\,\text{log}\,n) $$ | No | Yes |

Stability is whether the sorting algoritm keeps the original order of elements that have the same key. For examplegiven this list of unsorted elements,

| Value | Key |
|-----|-------|
| Bob | 2 |
| Kate | 1 |
| Kevin | 3 |
| Varun | 4 |
| Natasha | 5 |
| Jason | 4 |

there are two possible outcomes: 

| Value | Key |
|-----|-------|
| Kate | 1 |
| Bob | 2 |
| Kevin | 3 |
| Varun | 4 |
| Jason | 4 |
| Natasha | 5 |

| Value | Key |
|-----|-------|
| Kate | 1 |
| Bob | 2 |
| Kevin | 3 |
| Jason | 4 |
| Varun | 4 |
| Natasha | 5 |

For a stable sorting algorithm, only the first outcome is correct. In the second outcome, while the keys sorted, the order of the values Jason and Varun are not maintained.
