#  Insertion Sort in Java

This project demonstrates the **Insertion Sort algorithm** implemented in **Java**, including:

-  Iterative Insertion Sort  
-  Recursive Insertion Sort  

Insertion Sort is a simple and intuitive sorting technique, often compared to arranging playing cards in your hand.

---

##  What is Insertion Sort?

Insertion Sort builds the final sorted array **one element at a time**.

It works by:
- Taking one element from the unsorted part
- Comparing it with elements in the sorted part
- Shifting larger elements to the right
- Inserting the element in its correct position

The array is logically divided into:
- **Sorted part**
- **Unsorted part**

Initially:
- The first element is considered sorted
- The remaining elements are unsorted

---

#  Iterative Insertion Sort

##  Algorithm Steps

1. Start from the second element (index `1`)
2. Store the current element as `key`
3. Compare `key` with elements before it
4. Shift elements greater than `key` one position ahead
5. Insert `key` at the correct position
6. Repeat until the array is sorted

---

##  Time Complexity

| Case | Complexity |
|------|------------|
| Best Case (Already Sorted) | O(n) |
| Average Case | O(n²) |
| Worst Case (Reverse Order) | O(n²) |

---

##  Space Complexity

- **O(1)** (In-place sorting)
- No extra memory required

---

##  Advantages

- Simple to understand
- Efficient for small datasets
- Works well for nearly sorted arrays
- Stable sorting algorithm

---

#  Recursive Insertion Sort

Recursive Insertion Sort follows the same logic but uses **recursion** instead of loops.

Instead of iterating, the function:
- Sorts the first `n-1` elements recursively
- Then inserts the last element in its correct position

---

##  Algorithm Steps (Recursive)

1. Base Case:
   - If the array size is `0` or `1`, return (already sorted)

2. Recursive Case:
   - Recursively sort the first `n-1` elements
   - Store the last element as `key`
   - Shift elements greater than `key`
   - Insert `key` in its correct position

---

##  Time Complexity (Recursive)

| Case | Complexity |
|------|------------|
| Best Case | O(n) |
| Average Case | O(n²) |
| Worst Case | O(n²) |

---

##  Space Complexity (Recursive)

- **O(n)** due to recursive call stack
- Uses additional memory compared to iterative version

---

#  Iterative vs Recursive Comparison

| Feature | Iterative | Recursive |
|----------|------------|------------|
| Approach | Loop-based | Function recursion |
| Space Usage | O(1) | O(n) |
| Performance | Slightly faster | Slightly slower (recursion overhead) |
| Memory Efficient | Yes | No |
| Code Simplicity | Simple | Elegant but less efficient |

---

#  When to Use Insertion Sort?

- Small datasets
- Nearly sorted arrays
- Educational purposes
- When simplicity is preferred over performance

---

#  Conclusion

Insertion Sort is a foundational sorting algorithm that:

- Builds the sorted array gradually
- Is easy to understand and implement
- Has both iterative and recursive versions
- Is efficient for small or nearly sorted data

Although not suitable for large datasets, it is extremely important for understanding sorting fundamentals.
