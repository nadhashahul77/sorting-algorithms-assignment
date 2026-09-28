# Final Conclusion

For the given 8 fixed-length integer IDs, both Merge Sort and Quick Sort produce the same sorted sequence:

102, 125, 147, 218, 275, 324, 389, 456

For this particular execution, Quick Sort performs 16 partition comparisons while the recorded Merge Sort merge passes use 17 comparisons. This is only an observation for the supplied input, not a general ranking.

For large fixed-length keys, the choice depends on the required properties. Merge Sort provides O(n log n) worst-case time and uses additional O(n) space. Quick Sort generally uses less auxiliary array space, but its worst-case time can become O(n²) depending on pivot selection.

Therefore, the appropriate method should be selected based on whether predictable worst-case performance, extra memory, stability, and pivot behavior are more important for the application.
