# ⚡ Quick Sort in Java

This project demonstrates the implementation of the **Quick Sort algorithm** using **Java**.

Quick Sort is a **Divide and Conquer** algorithm that efficiently sorts elements by partitioning the array around a pivot.

---

## 📌 What is Quick Sort?

Quick Sort works by:

- Selecting a **pivot element**
- Partitioning the array into:
  - Elements **less than pivot**
  - Elements **greater than pivot**
- Recursively applying the same process to subarrays

---

## 🔄 How It Works

### 1. Partition Function
- Chooses the **last element as pivot**
- Rearranges the array so:
  - Smaller elements → left side
  - Larger elements → right side
- Places pivot in its **correct sorted position**

---

### 2. Quick Sort Function
- Recursively sorts:
  - Left subarray (elements < pivot)
  - Right subarray (elements > pivot)

---

## 🧠 Algorithm Steps

1. Pick a pivot element  
2. Partition the array around the pivot  
3. Recursively sort left and right subarrays  
4. Combine results (sorted in-place)

---

## 📊 Time Complexity

| Case         | Complexity   |
|--------------|-------------|
| Best Case    | O(n log n)  |
| Average Case | O(n log n)  |
| Worst Case   | O(n²)       |

---

## 💾 Space Complexity

- **O(log n)** (recursive stack space)

---

## ⚙️ Features

- In-place sorting (no extra memory required)
- Efficient for large datasets
- Uses recursion and partitioning logic

---

## ▶️ Example

**Input:**
[10, 7, 8, 9, 1, 5]


**Output:**
1 5 7 8 9 10