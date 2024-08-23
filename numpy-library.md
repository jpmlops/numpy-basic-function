# Engineering Domains of NUMPY

The list of engineering domains and functions used for solving problems in this blog post are :

- Disaster Management (np.fft.fft)
- Mechanical Vibrations (np.linalg.eigval)
- Probability & Statistics (numpy.random.hypergeometric)
- Physics(np.meshgrid)
- Material Science(np.poly1d)

So, Let’s get started with importing `numpy`, `matplotlib`, `pandas` into our `Jupyter` notebook working on the Python 3 environment.

## Array indexing

Numpy offers several ways to index into arrays.

**Slicing**: Similar to Python lists, numpy arrays can be sliced. Since arrays may be multidimensional, you must specify a slice for each dimension of the array:

```python
import numpy as np

# Create the following rank 2 array with shape (3, 4)
# [[ 1  2  3  4]
#  [ 5  6  7  8]
#  [ 9 10 11 12]]
a = np.array([[1,2,3,4], [5,6,7,8], [9,10,11,12]])

# Use slicing to pull out the subarray consisting of the first 2 rows
# and columns 1 and 2; b is the following array of shape (2, 2):
# [[2 3]
#  [6 7]]
b = a[:2, 1:3]

# A slice of an array is a view into the same data, so modifying it
# will modify the original array.
print(a[0, 1])   # Prints "2"
b[0, 0] = 77     # b[0, 0] is the same piece of data as a[0, 1]
print(a[0, 1])   # Prints "77"
```

### Mixed Indexing

You can combine basic slicing with integer and boolean indexing.

#### array[start:stop:step]

- `start`: The starting index of the slice (inclusive).
- `stop`: The ending index of the slice (exclusive).
- `step`: The step size between each index.
