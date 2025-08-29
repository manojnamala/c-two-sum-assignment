# c-two-sum-assignment
c++ solution for two-sum array 

# Assignment for C++ Two-Sum

## 📘 Problem Statement
Given an array of integers `nums` and an integer `target`, return the indices of the two numbers which add up to the target.

- You may assume that each input would have exactly one solution.
- You may not use the same element twice.
- You can return the answer in any order.

### Example 1
**Input:** `nums = [2,7,11,15], target = 9`  
**Output:** `[0,1]`  
**Explanation:** Because `nums[0] + nums[1] == 9`, we return `[0, 1]`.

### Example 2
**Input:** `nums = [3,2,4], target = 6`  
**Output:** `[1,2]`

### Example 3
**Input:** `nums = [3,3], target = 6`  
**Output:** `[0,1]`

---

## 📌 Constraints
- `2 <= nums.length <= 10^4`  
- `-10^9 <= nums[i] <= 10^9`  
- `-10^9 <= target <= 10^9`  
- There exists only one valid answer.  

---

## 🖥️ How to Compile and Run

1. Make sure you have a **C++ compiler** installed (like `g++`).  
   - On Linux/Mac: Already included or install via package manager.  
   - On Windows: Install **MinGW** or use **Visual Studio Code** with C++ extension.  

2. Compile the program:
   ```bash
   g++ two_sum.cpp -o two_sum
