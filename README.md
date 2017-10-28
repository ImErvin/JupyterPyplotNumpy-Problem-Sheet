## Jupyter Pyplot and Numpy Problem Sheet

This is a jupyter,pyplot and numpy problem sheet. The aim of this problem sheet is to understand how to use the powerful Python libraries. This problem sheet was created by Ian Mcloughlin as part of our emerging technologies module in college.

You can find my solutions to each of these problems in this repository.

### How to use this repository

1. Ensure you have Python 3.x, Jupyter and Git installed locally.
2. Enter the following commands into your command line.
```bash
# Change directory to anywhere you desire
cd anywhere..

# Clone this repository using git
git clone https://github.com/ImErvin/JupyterPyplotNumpy-Problem-Sheet.git
cd JupyterPyplotNumpy-Problem-Sheet

# Use Jupyter to open the .ipynb within the directory.
Jupyter notebook IrisNotebook.ipynb

```

### What is are Jupyter?
Notebook documents (or “notebooks”, all lower case) are documents produced by the Jupyter Notebook App, which contain both computer code (e.g. python) and rich text elements (paragraph, equations, figures, links, etc...). Notebook documents are both human-readable documents containing the analysis description and the results (figures, tables, etc..) as well as executable documents which can be run to perform data analysis.[1]

### What is Pyplot?
Pyplot is part of the matplotlib library for Python. It's used to visualize data points in the form of diagrams (plots).

### What is Numpy?
NumPy is the fundamental package for scientific computing in Python. It is a Python library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.[2] Pyplot and numpy work very well together to plot arrays onto diagrams.

### References

[1] http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html

[2] https://docs.scipy.org/doc/numpy-1.13.0/user/whatisnumpy.html

### Problem Sheet Questions

**1. Get and load the data**

    Search online for Fisher’s iris data set, find a copy of the data, download it and save it to your repository. 
    If it is not in CSV format, use whatever means (Excel, notepad++, visual studio code, python) to convert it to CSV and save the CSV version to your repository also. 
    Open your Jupyter notebook for this problem sheet, creating a new one if needed, and load the CSV file into a numpy array.

**2. Write a note about the data set**

    In a markdown cell at the start of your notebook, write a short description of the iris data set, complete with references.

**3. Create a simple plot**

    The dataset contains five variables: sepal length, sepal width, petal length, petal width, and species. 
    Use pyplot to create a scatter plot of sepal length on the x-axis versus sepal width on the y-axis.
    Add axis labels and a title to the plot.

**4. Create a more complex plot**

    Re-create the above plot, but this time plot the setosa data points in red, the versicolor data point in green, and the virginica data points in blue. 
    Setosa, versicolor, and virginica are the three possible values of the species variable. 
    Add a legend to the plot showing which species is in which colour.

**5. Use seaborn**

    Use the seaborn library to create a scatterplot matrix of all five variables.

**6. Fit a line**

    Fit a straight line to the variables petal length and petal width for the whole data set. 
    Plot the data points in a scatter plot with the best fit line shown.

**7. Calculate the R-squared value**

    Calculate the R-Squared value for your line above.

**8. Fit another line**

    Use numpy to select only the data points where species is setosa. 
    Fit a straight line to the variables petal length and petal width.
    Plot the data points in a scatter plot with the best fit line shown.

**9. Calculate the R-squared value**

    Calculate the R-Squared value for your line above.

**10. Use gardient decent**

    Use gradient descent to approximate the best fit line for the petal length and petal width setosa values. 
    Compare the outputs to your calculations above.
