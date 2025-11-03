# NUMPY-ARRAY-BASICS

A NumPy array is the fundamental data structure of the NumPy (Numerical Python) library. It is the core object for performing fast, efficient numerical computations in Python, especially in data science and machine learning.

Key Points
Homogeneous: Unlike a standard Python list, a NumPy array can only store items of the same data type (e.g., all integers, all floating-point numbers). This strictness is what allows for efficiency.

Multidimensional: Arrays can have any number of dimensions (a 1D array is a vector, a 2D array is a matrix, a 3D array is a tensor, and so on).

Efficiency: NumPy arrays are stored in a contiguous block of memory. This allows underlying C/Fortran code to perform operations on the entire array at once (vectorization) without needing explicit Python loops, making them significantly faster than processing elements one by one in a Python list.

Vectorization: Operations are applied element-wise. For example, adding two NumPy arrays A + B adds the first element of A to the first of B, the second to the second, and so on, which is crucial for mathematical operations.
