# Numpy-Numerical-Python-Practice

Sections Covered:-

What is Numpy?
NumPy is a python library used for working with arrays.
It also has functions for working in domain of linear algebra, fourier transform, and matrices.
NumPy was created in 2005 by Travis Oliphant. It is an open source project and you can use it freely.
NumPy stands for Numerical Python.

1. Numpy ndarray

N-Dimensional array(ndarray) in Numpy
Array in Numpy is a table of elements (usually numbers), all of the same type, indexed by a tuple of positive integers.
In Numpy, number of dimensions of the array is called rank of the array.A tuple of integers giving the size of the array along each
dimension is known as shape of the array. 
An array class in Numpy is called as ndarray. 
Elements in Numpy arrays are accessed by using square brackets and can be initialized by using nested Python Lists.

2. Array Operations

Using Arithmetic Operators with Numpy
Let’s look at a one-dimensional array. I have 2 arrays, array1 and array2, created through two different techniques:
array1 = np.array([10,20,30,40,50])
array2 = np.arange(5)
You can perform arithmetic operations on these arrays. For example, if you add the arrays, 
the arithmetic operator will work element-wise.
The output will be an array of the same dimension.

3. Statistical Method

NumPy has quite a few useful statistical functions for finding minimum, maximum, percentile standard deviation and variance, etc. 
from the given elements in the array. The functions are explained as follows −
numpy.amin() and numpy.amax()
These functions return the minimum and the maximum from the elements in the given array along the specified axis.
numpy.ptp()
The numpy.ptp() function returns the range (maximum-minimum) of values along an axis.

4. Matrix Class

Note:
It is no longer recommended to use this class, even for linear algebra. Instead use regular arrays.
The class may be removed in the future.

Returns a matrix from an array-like object, or from a string of data. 
A matrix is a specialized 2-D array that retains its 2-D nature through operations.
It has certain special operators, such as * (matrix multiplication) and ** (matrix power).

Parameters
dataarray_like or string
If data is a string, it is interpreted as a matrix with commas or spaces separating columns, and semicolons separating rows.

dtypedata-type
Data-type of the output matrix.

copybool
If data is already an ndarray, then this flag determines whether the data is copied (the default), or whether a view is constructed.


