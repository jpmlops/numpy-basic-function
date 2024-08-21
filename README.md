# Important Numpy Functions in Python

Here are some of the important NumPy functions in Python which every Data scientist must know:

### `1. np.array()`: This function is used to create an array in NumPy.

```python
import numpy as np

arr = np.array([1, 2, 3])
print(arr)

```

### `2. np.arange()`:

This function is used to create an array with a range of values.

Example Code:

```python
import numpy as np

arr = np.arange(1, 6)
print(arr)
```

### `3. np.zeros()`:

This function is used to create an array filled with zeros.

Example Code:

```python
import numpy as np

arr = np.zeros(3)
print(arr)

```

### `4. np.ones()`:

This function is used to create an array filled with ones.

Example Code:

```python
import numpy as np

arr = np.ones(3)
print(arr)
```

### `5. np.linspace()`:

This function is used to create an array with a specified number of evenly spaced values.

Example Code:

```python
import numpy as np

arr = np.linspace(0, 1, 5)
print(arr)
```

### **6. np.random.rand()**:

This function is used to create an array with random values between 0 and 1.

**Example Code**:

```python
import numpy as np

arr = np.random.rand(3)
print(arr)


# **Output**:

[0.5488135  0.71518937 0.60276338]

```

### 7. np.random.randint():

This function is used to create an array with random integer values between a specified range.

Example Code:

```python
import numpy as np

arr = np.random.randint(0, 10, 5)
print(arr)
# Output:

[1 5 8 9 8]
```

### 8. np.mean():

This function is used to find the mean value of an array.

Example Code:

```python
import numpy as np

arr = np.array([1, 2, 3])
mean_value = np.mean(arr)
print(mean_value)

# Output:
2.0
```

### 9. np.median():

This function is used to find the median value of an array.

Example Code:

```python
import numpy as np

arr = np.array([1, 2, 3])
median_value = np.median(arr)
print(median_value)
# Output:

2.0
```
