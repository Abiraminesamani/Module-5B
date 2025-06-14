# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np
arr = np.array([[3, 7, 2],
                [4, 5, 9],
                [1, 8, 6]])
sorted_arr = np.sort(arr, axis=0)

print("Original Array:")
print(arr)
print("Column-wise Sorted Array:")
print(sorted_arr)

```
## Output
![image](https://github.com/user-attachments/assets/074e6e2b-2af1-47bf-b1f0-150d7b1b2e45)

## Result
Thus, To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order is verified and executed successfuly.
