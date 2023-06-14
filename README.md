# Machine Learning Course Topics
This is a comprehensive list of the topics covered in my machine learning course.

## Introduction to Python
Python is a popular programming language for machine learning due to its simplicity and versatility. 
In this section, we covered the basics of Python programming, including:


- Variables and data types
- Operators
    - Arithmetic operators
    - Assignment operators
    - Comparison operators
    - Logical operators
    - Bitwise operators
    - Membership operators
    - Identity operators
- Data Types
    - Numeric types (int, float, complex)
    - Text type (str)
    - Sequence types (list, tuple, range)
    - Mapping type
    - Set types (set)
    - Boolean type
    - Binary types
- List
    - Different types of creating list
        - Using square brackets and comma-separated values
        - Using the list() constructor
        - Using the range() function
        - Using a list comprehension
        - Creating an empty list and then adding items
    - Indexing and Slicing in list
    - List methods
        - append()
        - insert()
        - remove()
        - pop()
        - sort()
        - reverse()
        - extend()
        - index()
        - count()
        - clear()
        - copy()
        - len()
    - list characteristics
        - Mutable, Ordered, Heterogeneous, Variable length, Nestable, Iterable
- Control flow statements (if, for, while)
    - Several advanced forms of the for loop:
        - for loop with zip() function
        - for loop with enumerate() function
        - for loop with dictionary
        - for loop in a single line (list comprehension)

- Functions
    - Parameters and Arguments
        - Argument syntax
        - Parameters syntax
    - function annotations
    - lambda function
    - Some useful Built-in functions:
        - enumerate()
        - zip()
        - map()
        - filter()
- Iterables and Iterators
- try and except

## Introduction to Numpy
Numpy is a Python library for numerical computing, which provides powerful array operations and linear algebra functions. In this section, we covered the following topics:

- Creating and manipulating arrays
- Indexing and slicing
- Basic array operations
    - Basic mathematical operations
    - Trigonometric functions
    - Exponential and logarithmic functions
    - Linear algebra operations(dot product, eigenvalue decomposition, matrix inversion)
    - Statistical functions
- Axis
- Reshaping and Transposing
- Random number generation

## Introduction to Pandas
Pandas is a Python library for data manipulation and analysis, which provides powerful tools for handling tabular data. In this section, we covered the following topics:

- Loading and showing data
- Change index
- df.loc[] vs df.iloc[]
- Sort Dataframe by one column
- Boolean Masking for filtering Dataframe
- Data exploration methods (shape, columns, info, describe, unique, value_counts) 
- Data visualization methods
    - For numerical features
        - plot()
        - scatter()
        - hist()
        - boxplot()
    - For categorical features
        - bar()
        - pie()
        - boxplot()
- Applying function to pandas Dataframe
- Data Transformation
    - Grouping (Groupby)
    - Pivoting
    - Merging

## Introduction to Matplotlib
Matplotlib is a Python library for data visualization, which provides flexible and customizable plotting functions. In this section, we covered the following topics:

- Basic plotting functions (line plots, scatter plots, histograms)
- Customizing plots (labels, legends, styles, color, marker, title and xlabel-ylabel,  )

## Gradient Descent
Gradient descent is a fundamental optimization algorithm for finding the minimum of a function. In machine learning, it is commonly used to optimize the parameters of a model. In this section, we covered the following topics:

- Loss Function
    - MAE function
    - MSE function
- Plot loss Function
- Optimizer
    - The intuition behind gradient descent and How GD works
    - The mathematical formulation of gradient descent
    - Implementing gradient descent from scratch in Python and plot the result

## Linear Regression
Linear regression is a simple yet powerful method for modeling the relationship between a dependent variable and one or more independent variables. In this section, we covered the following topics:

- The intuition behind linear regression
- Simple linear regression (one input variable)
- Hypothesis function
- The mathematical formulation of linear regression
- Plot Hypothesis function with coef, and intercept which are computed by model
- Implementing linear regression using Numpy and Scikit-learn
- Evaluating model performance (mean squared error, R-squared)

## Multiple Linear Regression
Multiple linear regression is an extension of linear regression that can model the relationship between a dependent variable and multiple independent variables. In this section, we covered the following topics:

- Preprocess and EDA
    - Check and handle missing values
    - Encoding categorical feature
    - Change order of columns
    - Rename the column names so that they can be codeble
    - BoxPlot for Outliers
    - Feature selection/Reduction
- The intuition behind multiple linear regression (multiple input variables) 
- Ordinary Least Squares: closed-form solution
- SGDRegressor()
- Implementing multiple linear regression with two ways (closed-form solution and SGDRegressor()) using Scikit-learn