# Comparison Table

| Feature | Merge Sort | Quick Sort |
|---|---|---|
| Technique | Divide and merge | Divide and partition |
| Passes/partitions for this input | 3 merge passes | 5 partitions |
| Key comparisons in this execution | 17 | 16 |
| Best-case time | O(n log n) | O(n log n) |
| Average-case time | O(n log n) | O(n log n) |
| Worst-case time | O(n log n) | O(n²) |
| Additional space | O(n) | O(log n) average stack; O(n) worst stack |
| Stability | Stable | Not necessarily stable |
| Main strength | Predictable performance | Often efficient in-place sorting |
