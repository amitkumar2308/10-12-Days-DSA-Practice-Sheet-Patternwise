# 🎯 Complete DSA Master Syllabus
## Pattern-Wise Interview Preparation Guide
**Target:** 10-20 LPA Product Companies | **Timeline:** 10-12 Days

---

## 📋 Table of Contents
1. [Arrays & Hashing](#1-arrays--hashing)
2. [Two Pointers](#2-two-pointers)
3. [Sliding Window](#3-sliding-window)
4. [Stack](#4-stack)
5. [Binary Search](#5-binary-search)
6. [Linked List](#6-linked-list)
7. [Trees](#7-trees)
8. [Graphs](#8-graphs)
9. [Dynamic Programming](#9-dynamic-programming)
10. [Backtracking](#10-backtracking)
11. [Greedy](#11-greedy)
12. [Heap / Priority Queue](#12-heap--priority-queue)

---

## 1. Arrays & Hashing
**Difficulty Progression:** Beginner → Intermediate → Advanced  
**Interview Frequency:** ⭐⭐⭐⭐⭐ (Very High)

### Must-Solve Problems (10)

- [ ] **Two Sum** - Easy  
  [LeetCode #1](https://leetcode.com/problems/two-sum/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Foundation for hash map usage, most asked problem

- [ ] **Contains Duplicate** - Easy  
  [LeetCode #217](https://leetcode.com/problems/contains-duplicate/)  
  *Tags: Blind 75, NeetCode 150*  
  **Why:** Basic hashing concept

- [ ] **Valid Anagram** - Easy  
  [LeetCode #242](https://leetcode.com/problems/valid-anagram/)  
  *Tags: Blind 75, NeetCode 150*  
  **Why:** Character frequency counting pattern

- [ ] **Group Anagrams** - Medium  
  [LeetCode #49](https://leetcode.com/problems/group-anagrams/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Advanced hashing with string manipulation

- [ ] **Top K Frequent Elements** - Medium  
  [LeetCode #347](https://leetcode.com/problems/top-k-frequent-elements/)  
  *Tags: Blind 75, NeetCode 150*  
  **Why:** Frequency counting + bucket sort pattern

- [ ] **Product of Array Except Self** - Medium  
  [LeetCode #238](https://leetcode.com/problems/product-of-array-except-self/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Prefix/suffix product pattern, no division constraint

- [ ] **Longest Consecutive Sequence** - Medium  
  [LeetCode #128](https://leetcode.com/problems/longest-consecutive-sequence/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** O(n) solution using hash set, tricky logic

- [ ] **Subarray Sum Equals K** - Medium  
  [LeetCode #560](https://leetcode.com/problems/subarray-sum-equals-k/)  
  *Tags: Top Interview*  
  **Why:** Prefix sum + hash map pattern (VERY IMPORTANT)

- [ ] **3Sum** - Medium  
  [LeetCode #15](https://leetcode.com/problems/3sum/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Combination of sorting + two pointers

- [ ] **4Sum** - Medium  
  [LeetCode #18](https://leetcode.com/problems/4sum/)  
  *Tags: Top Interview*  
  **Why:** Extension of 3Sum pattern

### Bonus Problems (3)
- [ ] **Encode and Decode Strings** - Medium [LeetCode #271](https://leetcode.com/problems/encode-and-decode-strings/)
- [ ] **Valid Sudoku** - Medium [LeetCode #36](https://leetcode.com/problems/valid-sudoku/)
- [ ] **Majority Element** - Easy [LeetCode #169](https://leetcode.com/problems/majority-element/)

---

## 2. Two Pointers
**Difficulty Progression:** Beginner → Intermediate → Advanced  
**Interview Frequency:** ⭐⭐⭐⭐⭐ (Very High)

### Must-Solve Problems (8)

- [ ] **Valid Palindrome** - Easy  
  [LeetCode #125](https://leetcode.com/problems/valid-palindrome/)  
  *Tags: Blind 75, NeetCode 150*  
  **Why:** Basic two pointer pattern

- [ ] **Two Sum II - Input Array Is Sorted** - Medium  
  [LeetCode #167](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)  
  *Tags: NeetCode 150, Top Interview*  
  **Why:** Classic two pointer on sorted array

- [ ] **3Sum** - Medium  
  [LeetCode #15](https://leetcode.com/problems/3sum/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Two pointers with outer loop

- [ ] **Container With Most Water** - Medium  
  [LeetCode #11](https://leetcode.com/problems/container-with-most-water/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Greedy two pointer approach

- [ ] **Remove Duplicates from Sorted Array** - Easy  
  [LeetCode #26](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)  
  *Tags: Top Interview*  
  **Why:** In-place modification pattern

- [ ] **Move Zeroes** - Easy  
  [LeetCode #283](https://leetcode.com/problems/move-zeroes/)  
  *Tags: Top Interview*  
  **Why:** Two pointer for partitioning

- [ ] **Trapping Rain Water** - Hard  
  [LeetCode #42](https://leetcode.com/problems/trapping-rain-water/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Advanced two pointer with height tracking

- [ ] **Sort Colors** - Medium  
  [LeetCode #75](https://leetcode.com/problems/sort-colors/)  
  *Tags: Top Interview*  
  **Why:** Dutch National Flag algorithm

### Bonus Problems (2)
- [ ] **Remove Nth Node From End of List** - Medium [LeetCode #19](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)
- [ ] **Palindrome Linked List** - Easy [LeetCode #234](https://leetcode.com/problems/palindrome-linked-list/)

---

## 3. Sliding Window
**Difficulty Progression:** Beginner → Intermediate → Advanced  
**Interview Frequency:** ⭐⭐⭐⭐⭐ (Very High)

### Must-Solve Problems (7)

- [ ] **Best Time to Buy and Sell Stock** - Easy  
  [LeetCode #121](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Single pass sliding window

- [ ] **Longest Substring Without Repeating Characters** - Medium  
  [LeetCode #3](https://leetcode.com/problems/longest-substring-without-repeating-characters/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Classic variable size window

- [ ] **Longest Repeating Character Replacement** - Medium  
  [LeetCode #424](https://leetcode.com/problems/longest-repeating-character-replacement/)  
  *Tags: Blind 75, NeetCode 150*  
  **Why:** Window with constraint (k replacements)

- [ ] **Permutation in String** - Medium  
  [LeetCode #567](https://leetcode.com/problems/permutation-in-string/)  
  *Tags: NeetCode 150*  
  **Why:** Fixed size window with frequency matching

- [ ] **Minimum Window Substring** - Hard  
  [LeetCode #76](https://leetcode.com/problems/minimum-window-substring/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Most challenging sliding window problem

- [ ] **Sliding Window Maximum** - Hard  
  [LeetCode #239](https://leetcode.com/problems/sliding-window-maximum/)  
  *Tags: NeetCode 150, Top Interview*  
  **Why:** Window + monotonic deque pattern

- [ ] **Find All Anagrams in a String** - Medium  
  [LeetCode #438](https://leetcode.com/problems/find-all-anagrams-in-a-string/)  
  *Tags: Top Interview*  
  **Why:** Fixed window with character frequency

### Bonus Problems (2)
- [ ] **Minimum Size Subarray Sum** - Medium [LeetCode #209](https://leetcode.com/problems/minimum-size-subarray-sum/)
- [ ] **Fruit Into Baskets** - Medium [LeetCode #904](https://leetcode.com/problems/fruit-into-baskets/)

---

## 4. Stack
**Difficulty Progression:** Beginner → Intermediate → Advanced  
**Interview Frequency:** ⭐⭐⭐⭐ (High)

### Must-Solve Problems (7)

- [ ] **Valid Parentheses** - Easy  
  [LeetCode #20](https://leetcode.com/problems/valid-parentheses/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Most basic stack problem

- [ ] **Min Stack** - Medium  
  [LeetCode #155](https://leetcode.com/problems/min-stack/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Stack with O(1) min operation

- [ ] **Evaluate Reverse Polish Notation** - Medium  
  [LeetCode #150](https://leetcode.com/problems/evaluate-reverse-polish-notation/)  
  *Tags: NeetCode 150, Top Interview*  
  **Why:** Stack for expression evaluation

- [ ] **Daily Temperatures** - Medium  
  [LeetCode #739](https://leetcode.com/problems/daily-temperatures/)  
  *Tags: NeetCode 150, Top Interview*  
  **Why:** Monotonic stack pattern (IMPORTANT)

- [ ] **Next Greater Element I** - Easy  
  [LeetCode #496](https://leetcode.com/problems/next-greater-element-i/)  
  *Tags: NeetCode 150*  
  **Why:** NGE pattern foundation

- [ ] **Largest Rectangle in Histogram** - Hard  
  [LeetCode #84](https://leetcode.com/problems/largest-rectangle-in-histogram/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Advanced monotonic stack

- [ ] **Generate Parentheses** - Medium  
  [LeetCode #22](https://leetcode.com/problems/generate-parentheses/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Backtracking with stack validation

### Bonus Problems (2)
- [ ] **Decode String** - Medium [LeetCode #394](https://leetcode.com/problems/decode-string/)
- [ ] **Simplify Path** - Medium [LeetCode #71](https://leetcode.com/problems/simplify-path/)

---

## 5. Binary Search
**Difficulty Progression:** Beginner → Intermediate → Advanced  
**Interview Frequency:** ⭐⭐⭐⭐⭐ (Very High)

### Must-Solve Problems (8)

- [ ] **Binary Search** - Easy  
  [LeetCode #704](https://leetcode.com/problems/binary-search/)  
  *Tags: NeetCode 150*  
  **Why:** Template for binary search

- [ ] **Search Insert Position** - Easy  
  [LeetCode #35](https://leetcode.com/problems/search-insert-position/)  
  *Tags: Top Interview*  
  **Why:** Binary search variant (lower bound)

- [ ] **Find First and Last Position of Element** - Medium  
  [LeetCode #34](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Lower and upper bound pattern

- [ ] **Search in Rotated Sorted Array** - Medium  
  [LeetCode #33](https://leetcode.com/problems/search-in-rotated-sorted-array/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Modified binary search (VERY IMPORTANT)

- [ ] **Find Minimum in Rotated Sorted Array** - Medium  
  [LeetCode #153](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Finding pivot in rotated array

- [ ] **Koko Eating Bananas** - Medium  
  [LeetCode #875](https://leetcode.com/problems/koko-eating-bananas/)  
  *Tags: NeetCode 150*  
  **Why:** Binary search on answer

- [ ] **Search a 2D Matrix** - Medium  
  [LeetCode #74](https://leetcode.com/problems/search-a-2d-matrix/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** 2D binary search

- [ ] **Median of Two Sorted Arrays** - Hard  
  [LeetCode #4](https://leetcode.com/problems/median-of-two-sorted-arrays/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Advanced binary search partition

### Bonus Problems (2)
- [ ] **Time Based Key-Value Store** - Medium [LeetCode #981](https://leetcode.com/problems/time-based-key-value-store/)
- [ ] **Find Peak Element** - Medium [LeetCode #162](https://leetcode.com/problems/find-peak-element/)

---

## 6. Linked List
**Difficulty Progression:** Beginner → Intermediate → Advanced  
**Interview Frequency:** ⭐⭐⭐⭐⭐ (Very High)

### Must-Solve Problems (9)

- [ ] **Reverse Linked List** - Easy  
  [LeetCode #206](https://leetcode.com/problems/reverse-linked-list/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Most fundamental LL operation (MUST KNOW)

- [ ] **Merge Two Sorted Lists** - Easy  
  [LeetCode #21](https://leetcode.com/problems/merge-two-sorted-lists/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Basic merge pattern

- [ ] **Linked List Cycle** - Easy  
  [LeetCode #141](https://leetcode.com/problems/linked-list-cycle/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Floyd's cycle detection

- [ ] **Linked List Cycle II** - Medium  
  [LeetCode #142](https://leetcode.com/problems/linked-list-cycle-ii/)  
  *Tags: Top Interview*  
  **Why:** Finding cycle start point

- [ ] **Remove Nth Node From End of List** - Medium  
  [LeetCode #19](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Two pointer technique

- [ ] **Reorder List** - Medium  
  [LeetCode #143](https://leetcode.com/problems/reorder-list/)  
  *Tags: Blind 75, NeetCode 150*  
  **Why:** Multiple operations combined

- [ ] **Add Two Numbers** - Medium  
  [LeetCode #2](https://leetcode.com/problems/add-two-numbers/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Digit manipulation with carry

- [ ] **Copy List with Random Pointer** - Medium  
  [LeetCode #138](https://leetcode.com/problems/copy-list-with-random-pointer/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Deep copy with hash map

- [ ] **Merge k Sorted Lists** - Hard  
  [LeetCode #23](https://leetcode.com/problems/merge-k-sorted-lists/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Heap + linked list combination

### Bonus Problems (2)
- [ ] **Intersection of Two Linked Lists** - Easy [LeetCode #160](https://leetcode.com/problems/intersection-of-two-linked-lists/)
- [ ] **Palindrome Linked List** - Easy [LeetCode #234](https://leetcode.com/problems/palindrome-linked-list/)

---

## 7. Trees
**Difficulty Progression:** Beginner → Intermediate → Advanced  
**Interview Frequency:** ⭐⭐⭐⭐⭐ (Very High)

### Must-Solve Problems (10)

- [ ] **Invert Binary Tree** - Easy  
  [LeetCode #226](https://leetcode.com/problems/invert-binary-tree/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Basic tree recursion

- [ ] **Maximum Depth of Binary Tree** - Easy  
  [LeetCode #104](https://leetcode.com/problems/maximum-depth-of-binary-tree/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** DFS/BFS foundation

- [ ] **Same Tree** - Easy  
  [LeetCode #100](https://leetcode.com/problems/same-tree/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Tree comparison pattern

- [ ] **Subtree of Another Tree** - Easy  
  [LeetCode #572](https://leetcode.com/problems/subtree-of-another-tree/)  
  *Tags: Blind 75, NeetCode 150*  
  **Why:** Nested tree comparison

- [ ] **Lowest Common Ancestor of BST** - Medium  
  [LeetCode #235](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** BST property usage

- [ ] **Binary Tree Level Order Traversal** - Medium  
  [LeetCode #102](https://leetcode.com/problems/binary-tree-level-order-traversal/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** BFS template (VERY IMPORTANT)

- [ ] **Validate Binary Search Tree** - Medium  
  [LeetCode #98](https://leetcode.com/problems/validate-binary-search-tree/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** BST validation with range

- [ ] **Kth Smallest Element in a BST** - Medium  
  [LeetCode #230](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Inorder traversal application

- [ ] **Construct Binary Tree from Preorder and Inorder** - Medium  
  [LeetCode #105](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Tree construction pattern

- [ ] **Binary Tree Maximum Path Sum** - Hard  
  [LeetCode #124](https://leetcode.com/problems/binary-tree-maximum-path-sum/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Complex recursion with global state

### Bonus Problems (3)
- [ ] **Diameter of Binary Tree** - Easy [LeetCode #543](https://leetcode.com/problems/diameter-of-binary-tree/)
- [ ] **Balanced Binary Tree** - Easy [LeetCode #110](https://leetcode.com/problems/balanced-binary-tree/)
- [ ] **Serialize and Deserialize Binary Tree** - Hard [LeetCode #297](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/)

---

## 8. Graphs
**Difficulty Progression:** Beginner → Intermediate → Advanced  
**Interview Frequency:** ⭐⭐⭐⭐⭐ (Very High)

### Must-Solve Problems (9)

- [ ] **Number of Islands** - Medium  
  [LeetCode #200](https://leetcode.com/problems/number-of-islands/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** DFS/BFS on grid (MOST ASKED)

- [ ] **Clone Graph** - Medium  
  [LeetCode #133](https://leetcode.com/problems/clone-graph/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Graph traversal with cloning

- [ ] **Pacific Atlantic Water Flow** - Medium  
  [LeetCode #417](https://leetcode.com/problems/pacific-atlantic-water-flow/)  
  *Tags: Blind 75, NeetCode 150*  
  **Why:** Multi-source DFS/BFS

- [ ] **Course Schedule** - Medium  
  [LeetCode #207](https://leetcode.com/problems/course-schedule/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Topological sort / cycle detection (IMPORTANT)

- [ ] **Course Schedule II** - Medium  
  [LeetCode #210](https://leetcode.com/problems/course-schedule-ii/)  
  *Tags: NeetCode 150, Top Interview*  
  **Why:** Topological ordering

- [ ] **Number of Connected Components** - Medium  
  [LeetCode #323](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/)  
  *Tags: Blind 75, NeetCode 150*  
  **Why:** Union-Find / DFS pattern

- [ ] **Graph Valid Tree** - Medium  
  [LeetCode #261](https://leetcode.com/problems/graph-valid-tree/)  
  *Tags: Blind 75, NeetCode 150*  
  **Why:** Graph properties validation

- [ ] **Rotting Oranges** - Medium  
  [LeetCode #994](https://leetcode.com/problems/rotting-oranges/)  
  *Tags: NeetCode 150*  
  **Why:** Multi-source BFS with time

- [ ] **Word Ladder** - Hard  
  [LeetCode #127](https://leetcode.com/problems/word-ladder/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** BFS on implicit graph

### Bonus Problems (2)
- [ ] **Surrounded Regions** - Medium [LeetCode #130](https://leetcode.com/problems/surrounded-regions/)
- [ ] **Accounts Merge** - Medium [LeetCode #721](https://leetcode.com/problems/accounts-merge/)

---

## 9. Dynamic Programming
**Difficulty Progression:** Beginner → Intermediate → Advanced  
**Interview Frequency:** ⭐⭐⭐⭐⭐ (Very High)

### Must-Solve Problems (10)

- [ ] **Climbing Stairs** - Easy  
  [LeetCode #70](https://leetcode.com/problems/climbing-stairs/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** DP foundation (Fibonacci pattern)

- [ ] **House Robber** - Medium  
  [LeetCode #198](https://leetcode.com/problems/house-robber/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** 1D DP pattern

- [ ] **House Robber II** - Medium  
  [LeetCode #213](https://leetcode.com/problems/house-robber-ii/)  
  *Tags: Blind 75, NeetCode 150*  
  **Why:** Circular array DP

- [ ] **Longest Palindromic Substring** - Medium  
  [LeetCode #5](https://leetcode.com/problems/longest-palindromic-substring/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Expand around center / DP

- [ ] **Palindromic Substrings** - Medium  
  [LeetCode #647](https://leetcode.com/problems/palindromic-substrings/)  
  *Tags: NeetCode 150*  
  **Why:** Counting palindromes

- [ ] **Coin Change** - Medium  
  [LeetCode #322](https://leetcode.com/problems/coin-change/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Unbounded knapsack (VERY IMPORTANT)

- [ ] **Longest Increasing Subsequence** - Medium  
  [LeetCode #300](https://leetcode.com/problems/longest-increasing-subsequence/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Classic LIS pattern

- [ ] **Partition Equal Subset Sum** - Medium  
  [LeetCode #416](https://leetcode.com/problems/partition-equal-subset-sum/)  
  *Tags: NeetCode 150*  
  **Why:** 0/1 knapsack

- [ ] **Unique Paths** - Medium  
  [LeetCode #62](https://leetcode.com/problems/unique-paths/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** 2D grid DP

- [ ] **Longest Common Subsequence** - Medium  
  [LeetCode #1143](https://leetcode.com/problems/longest-common-subsequence/)  
  *Tags: Blind 75, NeetCode 150*  
  **Why:** 2D DP on strings

### Bonus Problems (3)
- [ ] **Word Break** - Medium [LeetCode #139](https://leetcode.com/problems/word-break/)
- [ ] **Decode Ways** - Medium [LeetCode #91](https://leetcode.com/problems/decode-ways/)
- [ ] **Maximum Product Subarray** - Medium [LeetCode #152](https://leetcode.com/problems/maximum-product-subarray/)

---

## 10. Backtracking
**Difficulty Progression:** Beginner → Intermediate → Advanced  
**Interview Frequency:** ⭐⭐⭐⭐ (High)

### Must-Solve Problems (7)

- [ ] **Subsets** - Medium  
  [LeetCode #78](https://leetcode.com/problems/subsets/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Basic backtracking template

- [ ] **Subsets II** - Medium  
  [LeetCode #90](https://leetcode.com/problems/subsets-ii/)  
  *Tags: NeetCode 150*  
  **Why:** Handling duplicates

- [ ] **Combination Sum** - Medium  
  [LeetCode #39](https://leetcode.com/problems/combination-sum/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Backtracking with reuse

- [ ] **Permutations** - Medium  
  [LeetCode #46](https://leetcode.com/problems/permutations/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Permutation generation

- [ ] **Palindrome Partitioning** - Medium  
  [LeetCode #131](https://leetcode.com/problems/palindrome-partitioning/)  
  *Tags: NeetCode 150*  
  **Why:** Partition backtracking

- [ ] **Letter Combinations of a Phone Number** - Medium  
  [LeetCode #17](https://leetcode.com/problems/letter-combinations-of-a-phone-number/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Multi-choice backtracking

- [ ] **Word Search** - Medium  
  [LeetCode #79](https://leetcode.com/problems/word-search/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** 2D backtracking with visited tracking

### Bonus Problems (2)
- [ ] **N-Queens** - Hard [LeetCode #51](https://leetcode.com/problems/n-queens/)
- [ ] **Combination Sum II** - Medium [LeetCode #40](https://leetcode.com/problems/combination-sum-ii/)

---

## 11. Greedy
**Difficulty Progression:** Beginner → Intermediate → Advanced  
**Interview Frequency:** ⭐⭐⭐⭐ (High)

### Must-Solve Problems (6)

- [ ] **Maximum Subarray** - Medium  
  [LeetCode #53](https://leetcode.com/problems/maximum-subarray/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Kadane's algorithm (MUST KNOW)

- [ ] **Jump Game** - Medium  
  [LeetCode #55](https://leetcode.com/problems/jump-game/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Greedy reachability

- [ ] **Jump Game II** - Medium  
  [LeetCode #45](https://leetcode.com/problems/jump-game-ii/)  
  *Tags: NeetCode 150*  
  **Why:** Minimum jumps greedy

- [ ] **Gas Station** - Medium  
  [LeetCode #134](https://leetcode.com/problems/gas-station/)  
  *Tags: NeetCode 150, Top Interview*  
  **Why:** Circular array greedy

- [ ] **Hand of Straights** - Medium  
  [LeetCode #846](https://leetcode.com/problems/hand-of-straights/)  
  *Tags: NeetCode 150*  
  **Why:** Greedy grouping

- [ ] **Merge Intervals** - Medium  
  [LeetCode #56](https://leetcode.com/problems/merge-intervals/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Interval merging pattern (VERY IMPORTANT)

### Bonus Problems (2)
- [ ] **Non-overlapping Intervals** - Medium [LeetCode #435](https://leetcode.com/problems/non-overlapping-intervals/)
- [ ] **Meeting Rooms II** - Medium [LeetCode #253](https://leetcode.com/problems/meeting-rooms-ii/)

---

## 12. Heap / Priority Queue
**Difficulty Progression:** Beginner → Intermediate → Advanced  
**Interview Frequency:** ⭐⭐⭐⭐ (High)

### Must-Solve Problems (6)

- [ ] **Kth Largest Element in an Array** - Medium  
  [LeetCode #215](https://leetcode.com/problems/kth-largest-element-in-an-array/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Min heap for kth largest (IMPORTANT)

- [ ] **Last Stone Weight** - Easy  
  [LeetCode #1046](https://leetcode.com/problems/last-stone-weight/)  
  *Tags: NeetCode 150*  
  **Why:** Max heap basics

- [ ] **K Closest Points to Origin** - Medium  
  [LeetCode #973](https://leetcode.com/problems/k-closest-points-to-origin/)  
  *Tags: NeetCode 150, Top Interview*  
  **Why:** Heap with custom comparator

- [ ] **Task Scheduler** - Medium  
  [LeetCode #621](https://leetcode.com/problems/task-scheduler/)  
  *Tags: NeetCode 150*  
  **Why:** Heap with greedy scheduling

- [ ] **Find Median from Data Stream** - Hard  
  [LeetCode #295](https://leetcode.com/problems/find-median-from-data-stream/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Two heap pattern (IMPORTANT)

- [ ] **Merge k Sorted Lists** - Hard  
  [LeetCode #23](https://leetcode.com/problems/merge-k-sorted-lists/)  
  *Tags: Blind 75, NeetCode 150, Top Interview*  
  **Why:** Heap for k-way merge

### Bonus Problems (2)
- [ ] **Top K Frequent Words** - Medium [LeetCode #692](https://leetcode.com/problems/top-k-frequent-words/)
- [ ] **Reorganize String** - Medium [LeetCode #767](https://leetcode.com/problems/reorganize-string/)

---

## 📊 Summary Statistics

| Pattern | Must-Solve | Bonus | Total | Difficulty Mix |
|---------|-----------|-------|-------|----------------|
| Arrays & Hashing | 10 | 3 | 13 | 3E, 7M |
| Two Pointers | 8 | 2 | 10 | 3E, 4M, 1H |
| Sliding Window | 7 | 2 | 9 | 1E, 4M, 2H |
| Stack | 7 | 2 | 9 | 2E, 4M, 1H |
| Binary Search | 8 | 2 | 10 | 2E, 5M, 1H |
| Linked List | 9 | 2 | 11 | 3E, 5M, 1H |
| Trees | 10 | 3 | 13 | 4E, 5M, 1H |
| Graphs | 9 | 2 | 11 | 0E, 8M, 1H |
| Dynamic Programming | 10 | 3 | 13 | 1E, 9M |
| Backtracking | 7 | 2 | 9 | 0E, 7M |
| Greedy | 6 | 2 | 8 | 0E, 6M |
| Heap / Priority Queue | 6 | 2 | 8 | 1E, 4M, 1H |
| **TOTAL** | **97** | **27** | **124** | **20E, 68M, 9H** |

---

## 🎯 Coverage Analysis

✅ **Blind 75:** Fully integrated (all 75 problems included)  
✅ **NeetCode 150:** ~85% coverage (most important problems)  
✅ **Top Interview 150:** ~70% coverage (high-frequency problems)

---

**Last Updated:** December 2025  
**Target Companies:** Walmart, Swiggy, Zomato, Hotstar, Razorpay, PayU, Visa, PhonePe
