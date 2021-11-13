# JupyterLab
- enables you to work with documents and activities such as Jupyter notebooks,text editors, terminals, and custom components in a flexible, integrated, and extensible manner.
- offers a unified model for viewing and handling data formats. JupyterLab understands many file formats (images, CSV, JSON, Markdown, PDF, Vega, Vega-Lite, etc.)

# Numpy in Python (data analysis)
NumPy was originally developed in the mid 2000s, and arose from an even older package called Numeric. 
This longevity means that almost every data analysis or machine learning package for Python leverages NumPy in some way.

- **Lists Of Lists for CSV Data**
- **Numpy 2-Dimensional Arrays**
- **Creating A NumPy Array**: we can slice,assign values,index and make them dimensional!
> We can create a NumPy array using the numpy.array function. If we pass in a list of lists, it will automatically create a NumPy array with the same number of rows and columns. 
> Because we want all of the elements in the array to be float elements for easy computation, we’ll leave off the header row, which contains strings.

> **Note:** One of the limitations of NumPy is that all the elements in an array have to be of the same type, so if we include the header row, all the elements in the array will be read in as strings.
> Because we want to be able to do computations like find the average quality of the wines, we need the elements to all be floats.

- **Using NumPy To Read In Files**

### NumPy Data Types
- float: numeric floating point data.
- int: integer data.
- string: character data.
- object: Python objects.

### NumPy Array Operations
- Single Array Math: - , + , x , /
- Broadcasting: try to match up elements
- Array Comparisons
- Array Methods: ex:- Summation ( sum() )
- Subsetting: conditional choice (ex:- rows > 7)
- Reshaping NumPy Arrays
- Combining NumPy Arrays

> Checkout the Numpy Cheat-sheet [cheatnumpy](https://s3.amazonaws.com/dq-blog-files/numpy-cheat-sheet.pdf)
