### Bubble Sort works by:

Repeatedly stepping through the list

Comparing adjacent elements

Swapping them if they are in the wrong order
After each pass, the largest element “bubbles up” to the end of the array.

### Optimization Used

A boolean variable swapped is used:

If no swaps occur in a pass → the array is already sorted

The algorithm terminates early, saving time

This reduces unnecessary passes in best-case scenarios.

### Algorithm (Step-by-Step)

Start from the first element of the array

Compare adjacent elements

Swap if the left element is greater than the right

Repeat for remaining unsorted elements

If no swap occurs in a pass → stop the algorithm