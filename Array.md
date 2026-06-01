# Fundamentals

| Problem | Approach |
|---------|----------|
| Linear Search | Simply search through the array and find the element. |
| Largest Element | Have a max then iterate over the array |
| Second Largest Element | Have 2 variable max and second max. |
| Maximum Consecutive Ones | Have count and max_count |
| Left Rotate an Array by one | Have a temp variable then swap the elements. |
| Left Rotate Array by K Places | Rotate the entire array<br>Rotate the 0 to n - k - 1<br>Rotate the n - k to n - 1 |

# Logic Building

| Problem | Approach |
|---------|----------|
| Move Zeroes to End | swap the non zero element to the front use two pointer(use j as counter) |
| Remove duplicates from sorted array | use two pointers similar to move zeroes to end.(use j as counter) |
| Find missing number | use xor |
| Union of two sorted arrays | use two pointers , one point to each array and one point to the result array. |
| Intersection of two sorted arrays | use two pointers , in equal case add to result , otherwise inc pointers |

# Medium Problems

| Problem | Approach |
|---------|----------|
| Majority Element - 1 | use hashmap or moore's voting algorithm |
| Leader in an array | use max variable and iterate from the end |
| Rearrange array elements by sign | two pointers , use posIdx and negIdx |
| Print the matrix in spiral manner| 4 boundaries , top = 0;  left = 0 , right = n - 1 , bottom = m - 1; |
| Pascal's Triangle -1 (calculate row and column) | use the formula n - i / i + 1 --> Example: 4 * 3 / 1 * 2|
| Pascal's Triangle -2 (Calculate entire row ) | prev * (r - i) / (i) |
| Pascal's Triangle -3 (print the entire triangle) | similar to pascal's triangle -2 but print the entire row |
| Rotate matrix by 90 degrees | Tranpose and reverse each row |
| Two Sum | eleIndex + sort + two pointers |
| 3 Sum | Similar approach as two sum but with three pointers |
| 4 sum | Exactly same as 3 sum but with four pointers |
| Sort array of 0s, 1s and 2s | Dutch National Flag Algorithm |




