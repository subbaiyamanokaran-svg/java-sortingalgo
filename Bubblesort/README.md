#  Bubble Sort (Iterative & Recursive)

##  Introduction

Bubble Sort is a simple comparison-based sorting algorithm.  
It repeatedly compares adjacent elements in an array and swaps them if they are in the wrong order.

After each pass, the largest element moves to the end of the array.  
This process continues until the entire array is sorted.

---

#  Iterative Bubble Sort

## 🔹 How It Works

The iterative version uses loops to perform multiple passes over the array.

### Step-by-Step Process:

1. Start from the first element of the array.
2. Compare adjacent elements.
3. Swap them if the left element is greater than the right element.
4. Continue this process until the end of the array.
5. After one complete pass, the largest element is placed at its correct position.
6. Repeat the process for the remaining unsorted elements.
7. Stop when the array becomes fully sorted.

---

## 🔹 Optimization Technique

A boolean variable (commonly called `swapped`) is used:

- If no swaps occur during a pass, the array is already sorted.
- The algorithm terminates early.
- This improves performance in the best-case scenario.

---

## 🔹 Time & Space Complexity

- **Worst Case:** O(n²)
- **Average Case:** O(n²)
- **Best Case (Optimized):** O(n)
- **Space Complexity:** O(1)

The iterative version is memory-efficient because it does not use recursion.

---

#  Recursive Bubble Sort

## 🔹 How It Works

The recursive version follows the same logic as iterative bubble sort but replaces outer loops with recursive function calls.

### Step-by-Step Process:

1. Perform one full pass of bubble sort.
2. After the pass, the largest element moves to the end.
3. Recursively call the function for the first `n - 1` elements.
4. Continue until only one element remains (base case).
5. Stop when the array becomes sorted.

---

## 🔹 Optimization in Recursive Version

Similar to the iterative approach:

- If no swaps occur during a pass, recursion stops early.
- This avoids unnecessary recursive calls.

---

## 🔹 Time & Space Complexity

- **Worst Case:** O(n²)
- **Average Case:** O(n²)
- **Best Case (Optimized):** O(n)
- **Space Complexity:** O(n) (due to recursion stack)

Recursive version consumes additional memory because each recursive call adds a new frame to the call stack.

---

#  Comparison: Iterative vs Recursive Bubble Sort

| Feature | Iterative Bubble Sort | Recursive Bubble Sort |
|----------|----------------------|-----------------------|
| Approach | Uses loops | Uses recursion |
| Control Mechanism | Loop-based passes | Recursive function calls |
| Time Complexity | O(n²) | O(n²) |
| Best Case (Optimized) | O(n) | O(n) |
| Space Complexity | O(1) | O(n) |
| Memory Usage | Low | Higher (stack memory) |
| Practical Usage | Commonly used | Rarely used |
| Learning Purpose | Basic sorting understanding | Recursion concept learning |

---

#  Conclusion

Both iterative and recursive bubble sort follow the same core principle:

- Compare adjacent elements  
- Swap when necessary  
- Move the largest element to the end  

The difference lies in how the passes are managed:

- Iterative → Controlled using loops  
- Recursive → Controlled using recursive function calls  

In practical applications, the iterative version is preferred due to better memory efficiency.  
The recursive version is mainly useful for understanding recursion and academic learning.
