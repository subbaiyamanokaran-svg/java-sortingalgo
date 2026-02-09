# Merge Sort in Java

## 📌 Overview
This project implements the **Merge Sort** algorithm in Java. Merge Sort is a divide-and-conquer algorithm that divides an array into smaller parts, sorts them, and then merges them back together in sorted order.

---

## 🛠️ Features
- Recursive implementation of Merge Sort
- Sorts integer arrays in ascending order
- Efficient and stable sorting algorithm

---

---

## 🚀 How It Works
1. The array is divided into two halves.
2. Each half is sorted recursively.
3. The sorted halves are merged to produce the final sorted array.

---

## 📄 Code Explanation

### `mergeSort(int arr[], int l, int r)`
- Recursively splits the array.
- Sorts left and right subarrays.
- Calls `merge()` to combine them.

### `merge(int arr[], int l, int m, int r)`
- Merges two sorted subarrays:
  - Left: `arr[l..m]`
  - Right: `arr[m+1..r]`

### `main()`
- Defines the input array.
- Calls `mergeSort()`.
- Prints the sorted output.

---

## ▶️ Sample Input
```java
int arr[] = {38, 27, 43, 10};
10 27 38 43
