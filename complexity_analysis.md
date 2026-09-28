# Complexity Analysis

## Merge Sort
- Number of merge passes for n = 8: 3.
- Comparisons in the bottom-up execution trace: 4 + 6 + 7 = 17.
- Best-case time: O(n log n)
- Average-case time: O(n log n)
- Worst-case time: O(n log n)
- Additional space: O(n) for the temporary merge array.

## Quick Sort
Using the last element as the pivot:
- Number of actual partitions for this input: 5.
- Partition comparisons: 7 + 1 + 4 + 3 + 1 = 16.
- Best-case time: O(n log n)
- Average-case time: O(n log n)
- Worst-case time: O(n²)
- Recursion stack: O(log n) average/balanced case and O(n) in the worst case.

Note: Exact operation counts depend on the implementation and pivot strategy. The counts above are for the supplied programs and this particular input.
