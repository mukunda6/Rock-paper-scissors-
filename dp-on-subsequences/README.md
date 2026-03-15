# DP on Subsequences

This repository contains problems and solutions for the **Dynamic Programming on Subsequences pattern**.

This pattern appears frequently in coding interviews at product-based companies.

---

## DP on Subsequences Pattern

General structure:

- You decide **whether to pick or not pick an element**
- Recursive choice:
  
take = solve(index-1, target - arr[index])
notTake = solve(index-1, target)

return combine(take, notTake)

---

## Common Problems

1. Subset Sum Equal to Target
2. Partition Equal Subset Sum
3. Count Subsets With Sum K
4. Minimum Subset Sum Difference
5. Target Sum
6. Coin Change
7. Coin Change II
8. Unbounded Knapsack
9. Rod Cutting

---

## Complexity

Typical DP table:
