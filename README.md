# C++ Problem Solving: Maximum Element Subset

## 📝 Problem Description
This repository contains an optimized solution for finding the maximum number of elements in a subset from a given array, such that the difference between the maximum and minimum elements in the subset is at most 5.

## 🚀 Algorithm & Methodology
The solution is implemented in **C++** and utilizes the following concepts:
* **Sorting:** The array is initially sorted in ascending order using `std::sort` ($O(n \log n)$ time complexity).
* **Two-Pointer Technique (Sliding Window):** A sliding window approach with two pointers (`i` and `l`) is used to maintain a valid subset where $a[i] - a[l] \le 5$. This achieves an efficient $O(n)$ traversal.
* **I/O Optimization:** Uses `ios_base::sync_with_stdio(false); cin.tie(nullptr);` for fast standard input/output operations.

## 💻 Source Code Structure
* **Language:** C++17 / C++20
* **Time Complexity:** $O(n \log n)$ due to the sorting step.
* **Space Complexity:** $O(n)$ for storing the vector elements.
