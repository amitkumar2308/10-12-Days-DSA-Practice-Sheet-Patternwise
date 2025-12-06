# 📜 DSA MASTER SHEET
## Printable Quick Reference Card
### 10-20 LPA Interview Preparation

---

# 🔷 PATTERN TEMPLATES

## 1️⃣ TWO POINTERS
```cpp
// Opposite Direction
int left = 0, right = n - 1;
while (left < right) {
    if (condition) left++;
    else right--;
}

// Same Direction (Partition)
int slow = 0;
for (int fast = 0; fast < n; fast++) {
    if (condition) {
        swap(arr[slow], arr[fast]);
        slow++;
    }
}
```

## 2️⃣ SLIDING WINDOW
```cpp
// Variable Size Window
int left = 0, result = 0;
for (int right = 0; right < n; right++) {
    // Add arr[right] to window
    while (window_invalid) {
        // Remove arr[left] from window
        left++;
    }
    result = max(result, right - left + 1);
}

// Fixed Size Window
for (int i = 0; i < n; i++) {
    // Add arr[i]
    if (i >= k) {
        // Remove arr[i-k]
    }
    if (i >= k-1) {
        // Process window
    }
}
```

## 3️⃣ BINARY SEARCH
```cpp
// Standard Template
int left = 0, right = n - 1;
while (left <= right) {
    int mid = left + (right - left) / 2;
    if (arr[mid] == target) return mid;
    if (arr[mid] < target) left = mid + 1;
    else right = mid - 1;
}
return -1; // or left for insert position

// Binary Search on Answer
int left = minAnswer, right = maxAnswer;
while (left < right) {
    int mid = left + (right - left) / 2;
    if (isValid(mid)) right = mid;
    else left = mid + 1;
}
return left;
```

## 4️⃣ DFS / BFS
```cpp
// DFS Template (Recursion)
void dfs(int node, vector<bool>& visited) {
    visited[node] = true;
    for (int neighbor : adj[node]) {
        if (!visited[neighbor])
            dfs(neighbor, visited);
    }
}

// BFS Template
void bfs(int start) {
    queue<int> q;
    vector<bool> visited(n, false);
    q.push(start);
    visited[start] = true;
    while (!q.empty()) {
        int node = q.front(); q.pop();
        for (int neighbor : adj[node]) {
            if (!visited[neighbor]) {
                visited[neighbor] = true;
                q.push(neighbor);
            }
        }
    }
}
```

## 5️⃣ BACKTRACKING
```cpp
void backtrack(vector<int>& path, vector<int>& nums) {
    if (path.size() == nums.size()) {
        result.push_back(path);
        return;
    }
    for (int i = 0; i < nums.size(); i++) {
        if (used[i]) continue;
        path.push_back(nums[i]);
        used[i] = true;
        backtrack(path, nums);
        path.pop_back();     // Undo
        used[i] = false;     // Undo
    }
}
```

## 6️⃣ DYNAMIC PROGRAMMING
```cpp
// 1D DP Template
vector<int> dp(n+1, 0);
for (int i = 1; i <= n; i++) {
    dp[i] = max(dp[i-1], dp[i-2] + val[i]);
}

// 2D DP Template (LCS)
vector<vector<int>> dp(m+1, vector<int>(n+1, 0));
for (int i = 1; i <= m; i++) {
    for (int j = 1; j <= n; j++) {
        if (s1[i-1] == s2[j-1])
            dp[i][j] = dp[i-1][j-1] + 1;
        else
            dp[i][j] = max(dp[i-1][j], dp[i][j-1]);
    }
}
```

## 7️⃣ MONOTONIC STACK
```cpp
// Next Greater Element
stack<int> st;
vector<int> nge(n, -1);
for (int i = n-1; i >= 0; i--) {
    while (!st.empty() && st.top() <= arr[i])
        st.pop();
    if (!st.empty()) nge[i] = st.top();
    st.push(arr[i]);
}
```

---

# 🔷 COMPLEXITY CHEAT SHEET

| Operation | Time | Space |
|-----------|------|-------|
| Array access | O(1) | - |
| Binary Search | O(log n) | O(1) |
| Sorting | O(n log n) | O(n) |
| HashMap ops | O(1) avg | O(n) |
| Heap push/pop | O(log n) | O(n) |
| DFS/BFS | O(V + E) | O(V) |
| DP 1D | O(n) | O(n) |
| DP 2D | O(n×m) | O(n×m) |

---

# 🔷 TOP 20 MUST-KNOW PROBLEMS

| # | Problem | Pattern | Complexity |
|---|---------|---------|------------|
| 1 | Two Sum | Hash Map | O(n) |
| 2 | 3Sum | Two Pointers | O(n²) |
| 3 | Best Time Buy Sell Stock | Sliding Window | O(n) |
| 4 | Longest Substring No Repeat | Sliding Window | O(n) |
| 5 | Minimum Window Substring | Sliding Window | O(n) |
| 6 | Valid Parentheses | Stack | O(n) |
| 7 | Daily Temperatures | Monotonic Stack | O(n) |
| 8 | Binary Search | Binary Search | O(log n) |
| 9 | Search Rotated Array | Binary Search | O(log n) |
| 10 | Reverse Linked List | Two Pointers | O(n) |
| 11 | Linked List Cycle | Fast/Slow | O(n) |
| 12 | Merge k Sorted Lists | Heap | O(n log k) |
| 13 | Level Order Traversal | BFS | O(n) |
| 14 | Validate BST | DFS | O(n) |
| 15 | Number of Islands | DFS/BFS | O(m×n) |
| 16 | Course Schedule | Topological Sort | O(V+E) |
| 17 | Coin Change | DP | O(n×amount) |
| 18 | LCS | DP | O(n×m) |
| 19 | Subsets | Backtracking | O(2ⁿ) |
| 20 | Merge Intervals | Sorting | O(n log n) |

---

# 🔷 QUICK PATTERN RECOGNITION

| See This | Think This |
|----------|------------|
| "Sorted array" | Binary Search / Two Pointers |
| "Subarray/Substring" | Sliding Window / Prefix Sum |
| "Find all combinations" | Backtracking |
| "Shortest path" | BFS |
| "All paths / explore" | DFS |
| "K-th largest/smallest" | Heap |
| "Overlapping subproblems" | DP |
| "Intervals" | Sort + Merge |
| "Parentheses matching" | Stack |
| "Next greater element" | Monotonic Stack |

---

# 🔷 12-DAY QUICK PLAN

| Day | Topic | Key Problems |
|-----|-------|--------------|
| 1 | Arrays & Hashing | Two Sum, Subarray Sum K |
| 2 | Two Pointers | 3Sum, Container Water |
| 3 | Sliding Window | Min Window, Longest Substring |
| 4 | Binary Search | Search Rotated, Koko Bananas |
| 5 | Linked List | Reverse LL, Cycle Detection |
| 6 | Stack | Valid Parentheses, Daily Temp |
| 7 | Trees (Basic) | Level Order, Validate BST |
| 8 | Trees + Graphs | Max Path Sum, Num Islands |
| 9 | DP (1D) | House Robber, Coin Change |
| 10 | DP (2D) | LCS, Unique Paths |
| 11 | Backtracking + Heap | Subsets, Kth Largest |
| 12 | Revision + Mock | Full revision |

---

# 🔷 INTERVIEW DAY CHECKLIST

## Before Interview
- [ ] 8 hours sleep
- [ ] Light breakfast
- [ ] Warm-up: 1 Easy problem
- [ ] Review this sheet

## During Interview
1. **CLARIFY** (2 min) → Repeat problem, ask edge cases
2. **PLAN** (5 min) → Brute force → Optimize
3. **CODE** (15 min) → Clean, readable
4. **TEST** (5 min) → Walk through example
5. **COMPLEXITY** (1 min) → Time & Space

## If Stuck
- Think aloud
- Try smaller example
- Ask for hint politely
- Brute force is okay

---

# 🔷 EDGE CASES CHECKLIST

- [ ] Empty array/string
- [ ] Single element
- [ ] All same elements
- [ ] Negative numbers
- [ ] Integer overflow
- [ ] null/undefined inputs
- [ ] Already sorted
- [ ] Reverse sorted

---

# 🔷 MUST-KNOW DATA STRUCTURES

```cpp
// Vector
vector<int> v(n, 0);
v.push_back(x);
v.pop_back();

// HashMap
unordered_map<int, int> mp;
mp[key] = value;
if (mp.find(key) != mp.end())

// HashSet
unordered_set<int> s;
s.insert(x);
s.count(x); // 0 or 1

// Stack
stack<int> st;
st.push(x);
st.top();
st.pop();

// Queue
queue<int> q;
q.push(x);
q.front();
q.pop();

// Priority Queue (Max Heap)
priority_queue<int> maxH;
// Min Heap
priority_queue<int, vector<int>, greater<int>> minH;
```

---

# 🔷 SUCCESS FORMULA

```
Success = Patterns × Practice × Consistency
```

**Remember:**
- Patterns > Random Problems
- Understanding > Memorizing
- Calm > Panic
- Clean Code > Fast Code
- Progress > Perfection

---

**🚀 YOU'VE GOT THIS! 🚀**

---

*Print this sheet and review before your interview!*
