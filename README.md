# Merge Sort and Quick Sort Assignment

## Input
324, 125, 456, 218, 102, 389, 275, 147

## Contents
- `merge_sort.c` - C implementation of Merge Sort
- `quick_sort.c` - C implementation of Quick Sort
- `input_data.txt` - given input
- `output.txt` - execution results
- `trace_table.txt` - readable trace tables
- `trace_table_merge_sort.csv` - Merge Sort trace
- `trace_table_quick_sort.csv` - Quick Sort partition trace
- `complexity_analysis.md` - time and space complexity
- `comparison_table.md` - algorithm comparison
- `final_conclusion.md` - conclusion
- `report.md` - complete assignment report

## Compile and run

### Merge Sort
```bash
gcc merge_sort.c -o merge_sort
./merge_sort
```

### Quick Sort
```bash
gcc quick_sort.c -o quick_sort
./quick_sort
```

## Important note
The question image says to record the array "after each digit position is processed" under Merge Sort. Merge Sort does not process digit positions; it processes subarrays/runs. Therefore, the trace in this repository records the array after each Merge Sort pass (subarray-size 1, 2 and 4). If the intended algorithm was Radix Sort, the trace requirement would instead be based on digit positions.
