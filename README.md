# Machine Learning Course Topics
This is a comprehensive list of the topics covered in my machine learning course.

## Introduction to Python
Python is a popular programming language for machine learning due to its simplicity and versatility. 
In this section, we covered the basics of Python programming, including:

Variables and data types  

Copy and Deep copy
<details>
<summary><b>Operators</b></summary><br/>
- Arithmetic operators  

- Assignment operators  

- Comparison operators  

- Logical operators  

- Bitwise operators  

- Membership operators  

- Identity operators
</details>

<details>
<summary><b>Data Types</b></summary><br/>
- Numeric types(int, float, complex)  

- Text type(str)  

- Sequence types(list, tuple, range)  

- Mapping type(dict)  

- Set types(set)  

- Boolean type(bool)  

- Binary types(bytes)
</details>

<details>
<summary><b>List</b></summary><br/>
- Different types of creating list
    Using square brackets and comma-separated values  
    Using the list() constructor  
    Using the range() function  
    Using a list comprehension  
    Creating an empty list and then adding items

- Indexing and Slicing in list

- List methods

    append()  

    insert()  

    remove()  

    pop()  

    sort()  

    reverse()  

    extend()  

    index()  

    count()  

    clear()  

    copy()
    len()

- list characteristics
    Mutable, Ordered, Heterogeneous, Variable length, Nestable, Iterable
</details>

<details>
<summary><b>Control flow statements (if, for, while)</b></summary><br/>
- Several advanced forms of the for loop
    for loop with zip() function
    for loop with enumerate() function
    for loop with dictionary
    for loop in a single line (list comprehension)
</details>

<details>
<summary><b>Functions</b></summary><br/>
Parameters and Arguments
    Argument syntax
    Parameters syntax
function annotations
lambda function
Some useful Built-in functions:
    enumerate()
    zip()
    map()
    filter()
</details>

- Iterables and Iterators
- try and except

## Introduction to Numpy
Numpy is a Python library for numerical computing, which provides powerful array operations and linear algebra functions. In this section, we covered the following topics:

- Creating and manipulating arrays
- Indexing and slicing
- <details>
<summary><b>Basic array operations</b></summary><br/>
    - Basic mathematical operations
    - Trigonometric functions
    - Exponential and logarithmic functions
    - Linear algebra operations(dot product, eigenvalue decomposition, matrix inversion)
    - Statistical functions
</details>
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
    - Rename the column names so that they can be codable
    - BoxPlot for Outliers
    - Feature selection/Reduction
- The intuition behind multiple linear regression (multiple input variables) 
- Ordinary Least Squares: closed-form solution
- SGDRegressor()
- Implementing multiple linear regression with two ways (closed-form solution and SGDRegressor()) using Scikit-learn

## Logistic Regression
Logistic regression is a machine learning algorithm used for classification problems, where the target variable is binary or categorical. We covered how to implement logistic regression using Python and Scikit-learn, and how to evaluate the performance of a logistic regression model. In this section, we covered the following topics:
- Model with GridSearchCV
- Plot the decision boundary

## Neural Networks
Neural networks are a powerful class of machine learning algorithms that can be used for a wide range of tasks, including image recognition, natural language processing, and speech recognition. We covered the basic concepts of neural networks, including how to create a feedforward neural network using Pytorch.

## Decision Tree
A decision tree is a type of supervised machine learning algorithm that is commonly used for classification and regression tasks. It is a tree-like model where each internal node represents a test on an attribute, each branch represents the outcome of the test, and each leaf node represents a class label or a numerical value.

The decision-making process starts at the root node of the tree and follows a path down to a leaf node, based on the values of the attributes being tested. At each internal node, the algorithm chooses the best attribute to split the data based on some metric, such as information gain or Gini impurity. The goal is to create a tree that can accurately predict the class label or numerical value of new instances based on their attribute values. In this section, we covered the following topics:
- A simple decision tree
- Decision Tree with Random search 
- Decision Tree with Grid search (Grid search and random search are two commonly used techniques for hyperparameter tuning in machine learning.)
- Train a Random forest 