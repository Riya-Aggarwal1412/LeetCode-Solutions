**Question 1 :-** Given an array of integers and a target value, how can we find the indices of the two numbers that add up to the target?
🔍 **Example:**
Input: nums = [2, 7, 11, 15], target = 9
Output: Indices [0, 1] (because nums[0] + nums[1] = 9)

**Question 2:-** You are given a sorted array of integers, and your task is to remove the duplicates in-place, meaning you cannot use extra space for another array. You should ensure that each unique number appears only once, and the order of the unique elements remains unchanged.
Goal:
1. Return the number of unique elements (k) in the modified array.
2. Modify the array so that the first k elements contain the unique values.
3. The remaining elements beyond k don't matter.

**Question3:** 💡 Problem Breakdown: Remove Element (LeetCode) 💡<br>
Today’s challenge is about removing all occurrences of a specific value from an array, in-place. Here’s the task in simple terms:<br?
🔹 Input: An array of numbers and a specific value (let's call it val).<br>
🔹 Goal: Remove all occurrences of val from the array without using extra space (meaning you need to modify the array itself).<br>
🔹 Output: The number of elements remaining in the array after removing all instances of val.<br>

**Question4:** Given a sorted array of distinct integers and a target value, return the index if the target is found. If not, return the index where it would be if it were inserted in order.<br>
You must write an algorithm with O(log n) runtime complexity.

**Question 5:** You are given a large integer represented as an integer array digits, where each digits[i] is the ith digit of the integer. The digits are ordered from most significant to least significant in left-to-right order. The large integer does not contain any leading 0's.<br>
Increment the large integer by one and return the resulting array of digits.

**Question 6:** You have two sorted arrays: nums1 and nums2. Your job is to merge them into one sorted array, but the final result should be stored in nums1 🧩. To do this, start from the end of both arrays, compare the numbers, and place the largest one at the end of nums1 🔄. Keep going until all elements from nums2 are merged into nums1. Now, nums1 will have all the elements sorted in order! ✅

**Question 7:** Given a non-empty array of integers nums, every element appears twice except for one. Find that single one.<br>
You must implement a solution with a linear runtime complexity and use only constant extra space.<br>
**Example 1:** <br>
Input: nums = [2,2,1]<br>
Output: 1<br>

**Question 8:** Given an array nums of size n, return the majority element.<br>
The majority element is the element that appears more than ⌊n / 2⌋ times. You may assume that the majority element always exists in the array.<br>

**Question 9:** Given an integer array nums where every element appears three times except for one, which appears exactly once. Find the single element and return it.<br>

**Question 10:** Given an integer array nums, return true if any value appears at least twice in the array, and return false if every element is distinct.<br>
**Example 1:** <br>
Input: nums = [1,2,3,1]<br>
Output: true<br>
**Explanation:** <br>
The element 1 occurs at the indices 0 and 3.<br>
You must implement a solution with a linear runtime complexity and use only constant extra space.

**Question 11:** Given two integer arrays nums1 and nums2, return an array of their intersection. Each element in the result must be unique and you may return the result in any order.<br>
**Example 1:** <br>
Input: nums1 = [1,2,2,1], nums2 = [2,2]<br>
Output: [2]

**Question 12:** Given two integer arrays nums1 and nums2, return an array of their intersection. Each element in the result must appear as many times as it shows in both arrays and you may return the result in any order.<br>
**Example 1:** <br>
Input: nums1 = [1,2,2,1], nums2 = [2,2]<br>
Output: [2,2]

**Question 13:** Given an integer array nums and an integer k, return true if there are two distinct indices i and j in the array such that nums[i] == nums[j] and abs(i - j) <= k.<br>
**Example 1:** <br>
Input: nums = [1,2,3,1], k = 3 <br>
Output: true
