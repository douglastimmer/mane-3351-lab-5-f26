# MANE 3351 - Manufacturing Engineering Analysis

## Laboratory 5 Assignment

#### Assigned: November 9, 2026

#### Due: November 16, 2026 (before 9:30 AM)

---

#### Learning Goals

1.  Write user-defined scalar function in Python,
1.  Practice using GitHub Desktop to download and upload respositories.

#### Description

The purpose of this laboratory is the use of user-defined functions in Python.

For this lab you will write a function that evaluates the cumulative density function (CDF) of the logisitic distribution shown below. 

$$
F(x)=\frac{\exp\left(\frac{x-\mu}{\sigma}\right)}{1+\exp\left(\frac{x-\mu}{\sigma}\right)}
$$

where $\sigma>0$, $-\infty<\mu<\infty$, and $-\infty< x<\infty$. Your user-defined function will accept three values: $x$, $\mu$ (mu) and $\sigma$ (sigma) and returns the value of $F(x)$.

#### Step 1

Edit the first cell (markdown), to update your personal information.

#### Step 2

In cell 2 (Python cell), define a scalar function to return a single value of $F(x)$ defined in equation 1 above when provided the values of *x*, $\mu$ and $\sigma$. The function definition should be added in cell two below the comments to add function here.

Examples of user-defined functions have been provided in most, if not all, classroom Jupyter Notebook examples. A helpful resource for this step is [Python User Defined Functions](https://www.geeksforgeeks.org/python/python-user-defined-functions/). 

#### Step 3

Also in cell 2, add three lines of code below the function declaration that allows users to input the values for $x$, $\mu$ and $\sigma$. There will be a comment in the template Jupyter Notebook where this code should be inserted. Use the Python Code from Lecture 12 (October 19) as an example.

#### Step 4

Also in cell 2, add code to call your function and store the result of the function call in variable F. Print the value of variable F.

#### Step 5

Run your program and enter 1.0 for the value of *x*, 2.0 for the value of $\mu$, and 5.0 for the value of $\sigma$.

#### Step 6

After running and testing your program, save the Jupyter Notebook. Upload your repository using GitHub desktop.