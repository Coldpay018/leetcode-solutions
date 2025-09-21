# 0001. Two Sum (C++)

**Approach:** Hash map (`std::map<int,int>`) to store value → index.  
For each `nums[i]`, check if `target - nums[i]` exists in the map; if yes, return the pair of indices.

**Time:** O(n)  
**Space:** O(n)

**Edge cases:** duplicates; negative numbers.
