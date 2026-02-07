# Selection Sort (Java)

## 📌 What is Selection Sort?
Selection Sort is a **simple comparison-based sorting algorithm**.  
It works by **repeatedly selecting the smallest element** from the unsorted part of the array and placing it at the correct position in the sorted part.

The array is divided into:
- **Sorted part** (left side)
- **Unsorted part** (right side)

---

## 🧠 Basic Idea (Easy to Remember)
1. Assume the **first element is the minimum**
2. Compare it with all remaining elements
3. Find the **actual minimum**
4. **Swap** it with the first element
5. Move to the next position
6. Repeat until the array is sorted

---

## 🪜 Algorithm (Step-by-Step)

1. Start from index `0`
2. Find the smallest element in the unsorted array
3. Swap it with the element at the current index
4. Move the boundary of the sorted array by one
5. Repeat for `n - 1` passes

---

## 🔢 Example

### Input
64 25 12 22 11


### Pass-wise Execution
- Pass 1 → Minimum = 11 → Swap with 64  
  `11 25 12 22 64`
- Pass 2 → Minimum = 12  
  `11 12 25 22 64`
- Pass 3 → Minimum = 22  
  `11 12 22 25 64`
- Pass 4 → Minimum = 25  
  `11 12 22 25 64`

### Output
11 12 22 25 64