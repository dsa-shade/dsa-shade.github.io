# Array Slicing





**Array Slicing**

**Advanced Slicing Techniques**

You can also use negative indices for slicing operations. Negative indices count from the end of the array.

Example:

```python
arr = [1, 2, 3, 4, 5]
print(arr[-4:-1]) # Output: [2, 3, 4]
print(arr[::-1])  # Output: [5, 4, 3, 2, 1]
```

Using negative steps allows you to reverse the array or slice in the opposite direction.

**Multidimensional Arrays**

For multidimensional arrays (like those created using NumPy), you can perform slicing on each dimension.

Example:

```python
import numpy as np
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
print(arr[1:, :2])  # Output: [[4, 5], [7, 8]]
```

Understanding array slicing can greatly enhance your ability to manipulate data efficiently.
