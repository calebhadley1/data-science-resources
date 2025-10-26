# Numpy

## Important Concepts:
- Constructing Arrays
- Memory usage of NP Arrays vs Python Lists
- Data Types
    - float(64,32,16), int(64,32,16), uint(64,32,16)
- Ranges
    - arange, array, asarray, fromiter, linspace, ones, zeroes, ones_like, zeroes_like
- Broadcasting
    - [broadcast_arrays](https://numpy.org/doc/stable/reference/generated/numpy.broadcast_arrays.html), [broadcast_to](https://numpy.org/doc/stable/reference/generated/numpy.broadcast_to.html)
- Reducing Arrays
    - Reductions allow us to apply [functions](https://numpy.org/doc/stable/reference/routines.statistics.html) to np arrays
- Universal Functions *ufuncs*
    - https://jakevdp.github.io/PythonDataScienceHandbook/02.03-computation-on-arrays-ufuncs.html
    - https://numpy.org/doc/stable/user/basics.ufuncs.html
    - https://numpy.org/doc/stable/reference/generated/numpy.frompyfunc.html
- Saving Numpy outputs
    - https://numpy.org/doc/stable/reference/routines.io.html
- Copies vs Views
    - Do not continaully build up arrays with append/insert/delete like you would in Python since this will re-create a new copy of the array each time.
- Linear Algebra
    - Dot product, solve, invert, etc.

## Resources:
- [Python Data Science Handbook Chapter 2: Introduction to NumPy](https://jakevdp.github.io/PythonDataScienceHandbook/02.00-introduction-to-numpy.html)
    - Covers topics such as arrays, how numpy arrays are implemented versus compiled languages like C, data types, broadcasting, and reductions
- [Numpy vs SciPy](https://www.youtube.com/watch?v=l3s-_8uTBVA)
- [Lex Fridman and Travis Oliphant on the origins of Numpy and SciPy]()
- [Numpy Getting Started Docs](https://numpy.org/doc/stable/user/index.html)
- [Numba](https://numba.pydata.org/)
    - One of Numba's features is creating new ufuncs that behave like those built into NumPy.
- [Row vs Column Major Order](https://www.youtube.com/watch?v=b5lYGvcBjy4)
- [Copies vs Views](https://numpy.org/doc/stable/user/basics.copies.html)
- [Indexing](https://numpy.org/doc/stable/user/basics.indexing.html)
- [Linear Algebra Subpackage](https://numpy.org/doc/stable/reference/routines.linalg.html)
