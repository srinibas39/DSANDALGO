# Fundamentals

| S.No | Problem | Approach | Time Complexity | Space Complexity |
|------|---------|----------|-----------------|------------------|
| 1 | Linear Search | Simply search through the array and find the element. | O(n) | O(1) |
| 2 | Largest Element | Have a max then iterate over the array | O(n) | O(1) |
| 3 | Second Largest Element | Have 2 variable max and second max. | O(n) | O(1) |
| 4 | Maximum Consecutive Ones | Have count and max_count | O(n) | O(1) |
| 5 | Left Rotate an Array by one | Have a temp variable then swap the elements. | O(n) | O(1) |
| 6 | Left Rotate Array by K Places | Rotate the entire array<br>Rotate the 0 to n - k - 1<br>Rotate the n - k to n - 1 | O(n) | O(1) |

# Logic Building

| S.No | Problem | Approach | Time Complexity | Space Complexity |
|------|---------|----------|-----------------|------------------|
| 1 | Move Zeroes to End | swap the non zero element to the front use two pointer(use j as counter) | O(n) | O(1) |
| 2 | Remove duplicates from sorted array | use two pointers similar to move zeroes to end.(use j as counter) | O(n) | O(1) |
| 3 | Find missing number | use xor | O(n) | O(1) |
| 4 | Union of two sorted arrays | use two pointers , one point to each array and one point to the result array. | O(n + m) | O(1) |
| 5 | Intersection of two sorted arrays | use two pointers , in equal case add to result , otherwise inc pointers | O(n + m) | O(1) |

# Medium Problems

| S.No | Problem | Approach | Time Complexity | Space Complexity |
|------|---------|----------|-----------------|------------------|
| 1 | Majority Element - 1 | use hashmap or moore's voting algorithm | O(n) | O(n) / O(1) |
| 2 | Leader in an array | use max variable and iterate from the end | O(n) | O(1) |
| 3 | Rearrange array elements by sign | two pointers , use posIdx and negIdx | O(n) | O(1) |
| 4 | Print the matrix in spiral manner | 4 boundaries , top = 0;  left = 0 , right = n - 1 , bottom = m - 1; | O(m × n) | O(1) |
| 5 | Pascal's Triangle -1 (calculate row and column) | use the formula n - i / i + 1 --> Example: 4 * 3 / 1 * 2 | O(1) | O(1) |
| 6 | Pascal's Triangle -2 (Calculate entire row ) | prev * (r - i) / (i) | O(n) | O(n) |
| 7 | Pascal's Triangle -3 (print the entire triangle) | similar to pascal's triangle -2 but print the entire row | O(n²) | O(n²) |
| 8 | Rotate matrix by 90 degrees | Tranpose and reverse each row | O(n²) | O(1) |
| 9 | Two Sum | eleIndex + sort + two pointers | O(n log n) | O(n) |
| 10 | 3 Sum | Similar approach as two sum but with three pointers | O(n²) | O(1) |
| 11 | 4 sum | Exactly same as 3 sum but with four pointers | O(n³) | O(1) |
| 12 | Sort array of 0s, 1s and 2s | Dutch National Flag Algorithm | O(n) | O(1) |
| 13 | Kadane's Algorithm | 1 pointers , sum , msf , if sum < 0 then reset sum, follow up question could to return the subarray , when sum == 0 , then start = i | O(n) | O(1) |
| 14 | Next Permutation | find the dip element from the end , swap it with the next greater element , reverse the rest of the array , if dip is not found then reverse the entire array | O(n) | O(1) |

# Hard Problems

| S.No | Problem | Approach | Time Complexity | Space Complexity |
|------|---------|----------|-----------------|------------------|
| 1 | Majority Element-II | 2 pointers and moore's voting algorithm  | O(n) | O(1) |


