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
~~~
import numpy as np
array_2d = np.array([[12, 5, 1],
                     [6,  9, 2],
                     [8,  4, 6]])
print("Original Array:")
print(array_2d)
sorted_array = np.sort(array_2d, axis=0)
print("\nArray with Columns Sorted in Ascending Order:")
print(sorted_array)
~~~

## Output
<img width="835" height="462" alt="image" src="https://github.com/user-attachments/assets/13b9c6c7-fad1-41c9-8699-865e4448189f" />

## Result
Thus,the program has been executed successfully.
