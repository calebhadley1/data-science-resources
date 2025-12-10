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
6. Working With Lots of Numbers (Intro to Numpy)
7. Deep Numpy
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