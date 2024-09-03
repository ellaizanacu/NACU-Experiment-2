# **EXPERIMENT 2 - NUMERICAL PYTHON (NUMPY)**

## 1. NORMALIZATION PROBLEM: 
**Function Used:** *import numpy as np*

**Description:** This function imports the entire NumPy library, a tool for numerical computing in Python, and gives it a shortened alias as 'np' to use it.

**Function Used:** *X = np.random.random((5,5))*

**Description:** This function generates a 5x5 ndarray with randomly drawn numbers from a uniform distribution between 0 and 1.

**Function Used:** *X_mean = X.mean()*

**Description:** This function calculates the mean (average) of all the elements in the ndarray X.

**Function Used:** *X_std = X.std()*

**Description:** This function computes the standard deviation of all the elements in the ndarray X.

**Function Used:** *X_normalized = (X - X_mean)/X_std*

**Description:** This function normalizes the ndarray X by subtracting the mean and dividing by the standard deviation, resulting in an ndarray where the values have a mean of 0 and a standard deviation of 1.

**Function Used:** *np.save('X_normalized.npy', X_normalized)*

**Description:** This function saves the normalized ndarray 'X_normalized' to a file named 'X_normalized.npy' for later use.

**Function Used:** *print(X_normalized)*

**Description:** This function prints and displays the value for the ndarray 'X_normalized'.

## 2. DIVISIBLE BY 3 PROBLEM:
**Function Used:** *import numpy as np*

**Description:** This function imports the entire NumPy library, a tool for numerical computing in Python, and gives it a shortened alias as 'np' to use it.

**Function Used:** *A = np.arange(1, 101).reshape(10, 10) ** 2*

**Description:** The function 'np.arange(1, 101)' creates an ndarray of the first 100 positive integers and the function '.reshape(10, 10)' reshapes the ndarray into a 10x10 ndarray. This function results in a 10x10 ndarray where each element is the square of the numbers from 1 to 100.

**Function Used:** *div_by_3 = A[A % 3 == 0]*

**Description:** This function extracts all the elements from the ndarray A that are divisible by 3.

**Function Used:** *np.save('div_by_3.npy', div_by_3)*

**Description:** This function saves the elements that are divisible by 3 into a file named 'div_by_3.npy'.

**Function Used:** *print("\n Elements Divisible by 3: \n", div_by_3)*

**Description:** This function prints and displays the list of elements from ndarray A that are divisible by 3.
