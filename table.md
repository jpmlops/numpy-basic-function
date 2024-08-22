========𝗧𝗔𝗕𝗟𝗘 𝗢𝗙 𝗖𝗢𝗡𝗧𝗘𝗡𝗧========

- Array Creation Methods
- Array Operations
- Replacing Values Inside Array
- Set Operations
- Splitting
- Stacking
- Comparing Two Arrays
- Repeating Array Elements
- Einstein Summation Conventions
- Statistical Analysis
- Array Printing Options
- Save and Load Array Data

Create an array using numpy:

arr = np.array([1,2,2,3,4,5,6,7,8])

1. Count Non-Zero
2. Clip - It is used to keep the values of an array within a range.
3. count_nonzeros()
4. sort() - This function returns a sorted copy of an array.

```python
import numpy as np

array = np.array([
    [3, 7, 1],
    [10, 3, 2],
    [5, 6, 7]
])
print(array)
print()

# Sort the whole array
print(np.sort(array, axis=None))

# Sort along each row
print(np.sort(array, axis=1))

# Sort along each column
print(np.sort(array, axis=0))

# Output:

[[ 3 7 1]
[10 3 2]
[ 5 6 7]]

[ 1 2 3 3 5 6 7 7 10]

[[ 1 3 7]
[ 2 3 10]
[ 5 6 7]]

[[ 3 3 1]
[ 5 6 2]
[10 7 7]]
```

### numpy.argsort()

This function returns the indices that would sort an array.