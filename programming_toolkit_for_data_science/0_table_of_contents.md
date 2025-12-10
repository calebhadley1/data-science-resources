# Table of Contents

- [Python Fundamentals](1_python_fundamentals.md)
- [Data Visualization](2_data_visualization.md)
- [Numpy](3_numpy.md)
- [Pandas](4_pandas.md)

1. Knowing the Numbers in Our Data
    - Working with Data
        - [Whirlwind Tour of Python - Chapter 2: How to Run Python Code](https://jakevdp.github.io/WhirlwindTourOfPython/01-how-to-run-python-code.html)
        - [Whirlwind Tour of Python - Chapter 5: Basic Python Semantics: Operators](https://jakevdp.github.io/WhirlwindTourOfPython/04-semantics-operators.html)
        - [Whirlwind Tour of Python - Chapter 4: Basic Python Semantics: Variables and Objects](https://jakevdp.github.io/WhirlwindTourOfPython/03-semantics-variables.html)
        - [Whirlwind Tour of Python - Chapter 9: Defining and Using Functions](https://jakevdp.github.io/WhirlwindTourOfPython/08-defining-functions.html)
        - [Whirlwind Tour of Python - Chapter 6: Built-In Types: Simple Values](https://jakevdp.github.io/WhirlwindTourOfPython/05-built-in-scalar-types.html)
        - [Floating Point Numbers - Computerphile](https://www.youtube.com/watch?v=PZRI1IfStY0)
        - [Two's Complement](https://www.cs.cornell.edu/~tomf/notes/cps104/twoscomp.html)
        - [Double-precision floating-point format](https://en.wikipedia.org/wiki/Double-precision_floating-point_format)
        - [Improve your model's performance with bfloat16](https://docs.cloud.google.com/tpu/docs/bfloat16)
    - Key concepts:
        - Translate simple mathematical expressions to Python and evaluate them
        - Fluently convert simple math formulas into Python
2. Basic Python Flow Control and Data Structures
    - Data Structures in Python
        - [Whirlwind Tour of Python - Chapter 7: Built-In Data Structures](https://jakevdp.github.io/WhirlwindTourOfPython/06-built-in-data-structures.html)
        - [Official Python Data Structures Tutorial](https://docs.python.org/3/tutorial/datastructures.html)
        - [Whirlwind Tour of Python - Chapter 11: Iterators](https://jakevdp.github.io/WhirlwindTourOfPython/10-iterators.html)
        - [How Binary Search Makes Computers Much, Much Faster](https://www.youtube.com/watch?v=KXJSjte_OAI)
        - [bisect — Array bisection algorithm](https://docs.python.org/3/library/bisect.html)
        - [Shallow and Deep Copy Operations](https://docs.python.org/3/library/copy.html)
        - [Python Names and Values](https://nedbatchelder.com/text/names1.html)
    - Flow Control in Python
        - [Whirlwind Tour of Python - Chapter 8: Control Flow Statements](https://jakevdp.github.io/WhirlwindTourOfPython/07-control-flow-statements.html)
        - [Whirlwind Tour of Python - Chapter 9: Defining and Using Functions](https://jakevdp.github.io/WhirlwindTourOfPython/08-defining-functions.html)
    - Key concepts:
        - Data Structures
        - Control Flow
3. Programming Pythonically
    - [Whirlwind Tour of Python - Chapter 6: Built In Scalar Types: Booleans](https://jakevdp.github.io/WhirlwindTourOfPython/05-built-in-scalar-types.html#Boolean-Type)
    - [Python Booleans](https://www.youtube.com/watch?v=9OK32jb_TdI)
    - [Itertools](https://docs.python.org/3/library/itertools.html)
    - Generators
    - Functions as Variables
    - Key concepts:
        - List reasons for the special value None might occur in a Python program
        - Evaluate whether Python considers a given to be true or false
        - Use appropriate Python sequences for concise looping
        - Save functions as values and pass them to other functions
        - Determine whether two variables with the same name are actually the same variable or in different scopes
4. Reading and Writing Data in Python
    - Strings of Data
        - [PyFormat (Old but has clear documntation)](https://pyformat.info/)
        - [re - regex](https://docs.python.org/3/library/re.html)
        - [Whirlwind Tour of Python - Chapter 5: String Type](https://jakevdp.github.io/WhirlwindTourOfPython/05-built-in-scalar-types.html#String-Type)
        - [Python Strings](https://www.youtube.com/watch?v=iAzShkKzpJo)
        - [String Methods to Know](https://docs.python.org/3/library/stdtypes.html#string-methods)
        - [All 47 String Methods In Python Explained](https://www.youtube.com/watch?v=bnSYeYFRCaA)
        - Parsing data from strings
    - Reading and Writing Data in Files
        - [Generators in Python || Python Tutorial || Learn Python Programming](https://www.youtube.com/watch?v=gMompY5MyPg)
        - [Whirlwind Tour of Python - Chapter 13: Generators](https://jakevdp.github.io/WhirlwindTourOfPython/12-generators.html)
        - Reading and Writing TSV files with the `sep='\t'` argument
        - [Json Functions in Python](https://docs.python.org/3/library/json.html)
    - Key concepts:
        - Parse data from strings in Python.
        - Parse text-based files in Python.
        - Save data in Python using appropriate built-in data structures.
        - Write files in Python that can be easily read by common tools.
5. Effective Data Visualization
    - Introduction to Matplotlib
        - [plt.plot](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.plot.html)
        - Common plotting arguments:
            - `color`
            - `linestyle`
            - `marker`
            - `legend`
            - `scatter`
            - `xlabel/ylabel`
            - `annotate`
        - Common chart types
            - scatter, bar
        - Saving plots with `plt.savefig`
        - [Python Data Science Handbook - Simple Line Plots](https://jakevdp.github.io/PythonDataScienceHandbook/04.01-simple-line-plots.html)
        - [Matplotlib Quick Start](https://matplotlib.org/stable/users/explain/quick_start.html)
    - Effective Data Visualization
        - Pick appropriate Axis Ranges (Ex. Starting X at 0 for positive data can help distinguish delta)
        - Keep Colors and Symbols Consistent (Ex. If plotting a group of data multiple times, keep it the same color for clarity)
        - [Python Data Science Handbook - Customizing Plot Legends](https://jakevdp.github.io/PythonDataScienceHandbook/04.06-customizing-legends.html)
        - [Fundamentals of  Data Visualization 17.1: Visualizations along linear axes](https://clauswilke.com/dataviz/proportional-ink.html#visualizations-along-linear-axes)
        - [Atlassian: A complete guide to heatmaps](https://www.atlassian.com/data/charts/heatmap-complete-guide)
        - Use Subplots to present >1 chart together
        - Plot Small Multiples to compare different subsets of the data (Ex. Comparing features dist for each species of flower)
        - [Python Data Science Handbook - Multiple Subplots](https://jakevdp.github.io/PythonDataScienceHandbook/04.08-multiple-subplots.html)
        - [Fundamentals of  Data Visualization 21.1 Small multiples](https://clauswilke.com/dataviz/multi-panel-figures.html#small-multiples)
    - Key concepts:
        - Plot line charts and scatter plots with Matplotlib
        - Design charts to clearly communicate with data
        - Label charts clearly
        - Plot charts using small multiples
6. Working With Lots of Numbers (Intro to Numpy)
    - Introduction to Numpy
        - [IBM - NumPy vs SciPy](https://www.youtube.com/watch?v=l3s-_8uTBVA)
        - [Travis Oliphant: NumPy, SciPy, Anaconda, Python & Scientific Programming | Lex Fridman Podcast #224](https://www.youtube.com/watch?v=gFEE3w7F0ww&t=3089s)
            - Fantastic video on the history of Numpy, Scipy, Anaconda etc.
        - [Python Data Science Handbook - Introduction to NumPy](https://jakevdp.github.io/PythonDataScienceHandbook/02.00-introduction-to-numpy.html)
        - [Numpy - Converting Python sequences to NumPy arrays](https://numpy.org/doc/stable/user/basics.creation.html#converting-python-sequences-to-numpy-arrays)
        - [Numpy - From existing data](https://numpy.org/doc/stable/reference/routines.array-creation.html#from-existing-data)
        - Data Types including float64,32,16, int64, and uint64
        - [Python Data Science Handbook - Understanding Data Types in Python](https://jakevdp.github.io/PythonDataScienceHandbook/02.01-understanding-data-types.html)
        - [Numpy - Array creation](https://numpy.org/doc/stable/user/basics.creation.html)
        - Useful functions for array creation: arange, array, asarray, fromiter, linspace, ones, ones_like, zeros, zeros_like
        - [Python Data Science Handbook - Computation on Arrays: Broadcasting](https://jakevdp.github.io/PythonDataScienceHandbook/02.05-computation-on-arrays-broadcasting.html)
        - [Numpy - Broadcasting](https://numpy.org/doc/stable/user/basics.broadcasting.html)
        - [Python Data Science Handbook - Aggregations: Min, Max, and Everything In Between](https://jakevdp.github.io/PythonDataScienceHandbook/02.04-computation-on-arrays-aggregates.html)
        - [Python Data Science Handbook - Universal Functions](https://jakevdp.github.io/PythonDataScienceHandbook/02.03-computation-on-arrays-ufuncs.html)
        - [Numba](https://numba.pydata.org/)
        - [Numpy - Input and output](https://numpy.org/doc/stable/reference/routines.io.html)
    - Key concepts:
        - Explain why specialized numeric arrays are useful
        - Create and populate a NumPy array
        - Read a NumPy array from a file
        - Test whether a module is installed in the current environment
        - Find NumPy documentation for a given function
7. Deep Numpy
    - Numpy Views
        - Calculating Array offsets with `strides`
        - [Numpy - Internal memory layout of an ndarray](https://numpy.org/doc/stable/reference/arrays.ndarray.html#internal-memory-layout-of-an-ndarray)
        - [Row-major order vs column-major order: Samuel's tutorial](https://www.youtube.com/watch?v=b5lYGvcBjy4)
        - [Numpy - Copies and views](https://numpy.org/doc/stable/user/basics.copies.html)
        - [Python Data Science Handbook - The Basics of NumPy Arrays](https://jakevdp.github.io/PythonDataScienceHandbook/02.02-the-basics-of-numpy-arrays.html)
        - [Numpy - Indexing on ndarrays](https://numpy.org/doc/stable/user/basics.indexing.html)
        - [NeurIPS Proceedings - ImageNet Classification with Deep Convolutional Neural Networks](https://papers.nips.cc/paper_files/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html)
    - Numpy Wrap-Up
        - [Numpy - Linear algebra](https://numpy.org/doc/stable/reference/routines.linalg.html)
            - Some useful methods include dot, matrix_rank, solve, inv
    - Key concepts:
        - Describe the behavior of NumPyviews and when they can be used
        - Use standard views to reshape and transform arrays
        - Check if a given NumPy array is a view or not
        - Find and use NumPy functions for linear algebra and other operations as needed
        - Explain the usage of less common NumPy array structures
        - Identify slow array creation patterns and explain how to avoid them
8. Structured Data Management with Data Frames (Intro to Pandas)
9. Querying Your Data (More Pandas)
10. Exploratory Data Analysis
11. Exploratory Data Analysis
12. Building Models That Generalize
13. Preprocessing Data
14. Course Wrap-Up
    - Working Outside Notebooks
        - Run Python programs using `python3 test.py` syntax
        - Export Jupyter notebooks using `nbconvert` (html, md, notebook, pdf, script):
            - `jupyter nbconvert --to FORMAT my_notebook.ipynb`
        - Testing
            - There are two categories of functionalities to test:
                - Accessing and processsing outside data to prepare for modeling
                - Modeling
            - Try to test with smaller amounts of data to confirm functionality
            - Assertions with unittest or pytest
            - [Test Driven Development](https://testdriven.io/test-driven-development/)
            - [Unittest](https://docs.python.org/3/library/unittest.html)
    - Key concepts:
        - Run Python programs in a command line environment
        - Share Jupyter notebooks in other formats
        - Write simple tests