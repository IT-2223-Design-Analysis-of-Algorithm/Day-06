# Day-06

# 🔍 MATLAB Search Algorithms

## 📘 Project Overview

This MATLAB script explores fundamental **searching techniques** on arrays. It demonstrates:

1. ✅ **Linear Search**
2. ⏱️ **Time Complexity Insight using `tic/toc`**
3. 🔎 **Binary Search (Efficient Search)**

Each method shows how to locate a **target element** in an array and informs the user whether it's found or not — along with its index.

---

## 🚀 Features

### 1. Linear Search

- Sequentially scans each element.
- Stops when the target is found.
- Prints the **index** if found, otherwise a message.
- Example:
  ```matlab
  arr = [3, 5, 7, 9, 11, 13];
  target = 9;
🧠 Learning Outcomes
Understand how search algorithms work.

Compare linear vs binary search performance.

Use MATLAB's tic/toc to measure execution time.

Apply conditional logic and loop structures effectively.

▶️ How to Run
Save the script (e.g., search_algorithms.m).

Open MATLAB.

Run the file:

matlab
Copy
Edit
>> search_algorithms
Modify target values to test different scenarios.

📈 Performance Insight
Search Type	Best Case	Worst Case	Time Complexity
Linear Search	O(1)	O(n)	Simple but slow for large data
Binary Search	O(1)	O(log n)	Fast but requires sorted data

