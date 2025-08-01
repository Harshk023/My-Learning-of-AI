# My-Learning-of-AI
Learning tracker | AI JOurney


# 🐍 DSA in Python – Week 2: Searching & Sorting

This repository contains my *Week 2 DSA in Python learning plan*.  
Focus: *Searching and Sorting Algorithms* with day-wise practice.

---

## 📅 Day-wise Plan

### *Day 1 – Linear Search*
*Learn:*
- Concept of linear search
- Time complexity: O(n)

*Practice:*
- [ ] Search an element in an array  
- [ ] Count occurrences of an element  
- [ ] Find index of first occurrence

******CODE******
"""
🔹 Linear Search Algorithm
-----------------------------------
✅ Time Complexity: O(n) - we may have to check all elements in the worst case
✅ Space Complexity: O(1) - no extra space is required

👉 Approach:
   1. Traverse the list element by element.
   2. Compare each element with the target.
   3. If found, return the index.
   4. If not found, return -1.
"""

# Function to perform Linear Search
def linear_search(arr, target):
    for index in range(len(arr)):
        # Check if current element matches the target
        if arr[index] == target:
            return index  # Return the index where target is found
    return -1  # Target not found

# Example usage
if __name__ == "__main__":
    arr = [10, 25, 30, 45, 50]  # Sample list
    target = int(input("Enter the number to search: "))
    
    result = linear_search(arr, target)
    
    if result != -1:
        print(f"✅ Element found at index {result}")
    else:
        print("❌ Element not found in the list.")

---

### *Day 2 – Binary Search*
*Learn:*
- Binary search on sorted arrays
- Iterative & recursive approach
- Time complexity: O(log n)

*Practice:*
- [ ] Find first and last occurrence of an element  
- [ ] Count of a number in sorted array  
- [ ] Search in rotated sorted array (optional)

******CODE******
"""
🔹 Linear Search Algorithm
-----------------------------------
✅ Time Complexity: O(n) - we may have to check all elements in the worst case
✅ Space Complexity: O(1) - no extra space is required

👉 Approach:
   1. Traverse the list element by element.
   2. Compare each element with the target.
   3. If found, return the index.
   4. If not found, return -1.
"""

# Function to perform Linear Search
def linear_search(arr, target):
    for index in range(len(arr)):
        # Check if current element matches the target
        if arr[index] == target:
            return index  # Return the index where target is found
    return -1  # Target not found

# Example usage
if __name__ == "__main__":
    arr = [10, 25, 30, 45, 50]  # Sample list
    target = int(input("Enter the number to search: "))
    
    result = linear_search(arr, target)
    
    if result != -1:
        print(f"✅ Element found at index {result}")
    else:
        print("❌ Element not found in the list.")



---

### *Day 3 – Bubble Sort*
*Learn:*
- Swapping adjacent elements until sorted
- Time complexity: O(n²)

*Practice:*
- [ ] Sort array in ascending order  
- [ ] Sort array in descending order

---

### *Day 4 – Selection Sort*
*Learn:*
- Find the smallest element and place it first
- Time complexity: O(n²)

*Practice:*
- [ ] Sort array in ascending order  
- [ ] Sort array in descending order

---

### *Day 5 – Insertion Sort*
*Learn:*
- Insert elements into their correct position
- When insertion sort is better than bubble/selection

*Practice:*
- [ ] Sort array in ascending order  
- [ ] Insert an element in a sorted array

---

### *Day 6 – Time Complexity & Practice*
*Learn:*
- Big O analysis of all algorithms
- Compare linear vs binary search

*Practice (Solve 5 problems):*
1. Find missing number in an array  
2. Find peak element in an array  
3. Kth smallest element  
4. Merge two sorted arrays (without extra space)  
5. Check if array is sorted

---

### *Day 7 – Revision + Mini Project*
*Do:*
- Revise all search & sort algorithms
- Solve at least 5 problems on *LeetCode / CodeStudio*

*Mini Project Idea:*
- Create a Python program where a user enters numbers,
  and you *sort them and search an element* with chosen algorithm.

---

### 📌 Author
*Harsh Popat* – Learning DSA in Python | CSE @ IIIT Kota
