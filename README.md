
**FUNCTION**

**Python Functions** is a block of statements that return the specific task. The idea is to put some commonly or repeatedly done tasks together and make a function so that instead of writing the same code again and again for different inputs, we can do the function calls to reuse code contained in it over and over again.
1. In mathematics, a function is a process that relates between an input and an output.
2. In Python, apart from these relationship functions, functions are also a way to organize code with the ultimate goal of code being reusable.
3. Functions are defined with the def keyword followed by the function name and parameters in brackets ()
4. Optionally, a docstring can be added - a documentation string that describes the context of the function
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/72db590b-8e81-4998-b279-55fcc3d38184" /></div>

5. By default, Python will position according to the registration order in which it was defined, and must be called in that order.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/b773e719-d9c0-4065-b5c2-c0a28d55b15c" /></div>

---

**RETURN**

The Phython Return statement is a special statement that can use inside in function or method to send the function’s result back to the caller. A Return statement consist of the return keyword followed by an optional return value. The return value of a Python function can be any Python object.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/32b461d7-e5d5-49ca-a1bf-af39f4e2255a" /></div>

1. The return value of a function can be stored in a variable.

2. This will differentiate a function that returns a value from a function that does not return a value (often referred to as a procedure).
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/2768b84f-5538-416a-9fab-b6870ef39d80)" /></div>

---

**PASS BY REFERENCE VS VALUE**

The difference between pass-by-reference and pass-by-value is that modifications made to arguments passed in by reference in the called function have effect in the calling function, whereas modifications made to arguments passed in by value in the called function can not affect the calling function.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/3d1b8c22-ed7c-409c-8669-25dbc8f67f48" /></div>

---

**NUMPY**

**What is NumPy?**

NumPy is a Python library used for working with arrays. It also has functions for working in the domain of linear algebra, fourier transform, and matrices. NumPy was created in 2005 by Travis Oliphant. It is an open source project and you can use it freely. NumPy stands for Numerical Python.

At the core of the NumPy package, is the ndarray object. This encapsulates n-dimensional arrays of homogeneous data types, with many operations being performed in compiled code for performance. There are several important differences between NumPy arrays and the standard Python sequences:
1. NumPy arrays have a fixed size at creation, unlike Python lists. Changing the size of an ndarray will create a new array and delete the original.
2. The elements in a NumPy array are all required to be of the same data type, and thus will be the same size in memory.

---

**The next step is how to apply NumPy in Python**

**1. Checking NumPy Version**

The “print(np.version)" syntax is used to determine the installed version of NumPy in Python.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/d45da97a-d746-4aa6-b3ca-2658d9412718" /></div>

**2. Import NumPy**

The “import numpy as np” statement is used to import the NumPy library into Python, allowing you to use its functions for numerical calculations and array manipulations.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/bdd179da-48dd-477d-b008-461483eb7712" /></div>

**3. Creating a NumPy Array**

To create an ndarray, we can pass a list, tuple or any array-like object into the array() method, and it will be converted into an ndarray.

The syntax used to create a NumPy array from a list or tuple is the same, the only difference being the use of square brackets for a list [ ] and parentheses for a tuple ().
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/52daa652-677c-4ef9-8c29-ead8308ede1a" /></div>

<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/9c10e552-30d5-4e46-b237-079a3d3f9232" /></div>

**4. Creating an array with specific dimensions**

1. 1 dimension: 1D arrays in NumPy are essentially like lists in Python. They are sequences of elements arranged in a single line.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/400a939d-6386-4cec-87d4-ecfded67f71a" /></div>

2. 2 dimension: 2D arrays in NumPy are like matrices. They have rows and columns, arranged in a grid format.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/8596cebe-db04-48aa-a3d8-cf9aa6ef02e1" /></div>

3. Creating a 3-dimensional array with two 2-dimensional arrays, both containing two arrays, can be achieved using NumPy as follows:
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/a9abb721-5f9a-4c18-a1ed-072ebef216e6" /></div>

**5. Check how many dimensions the arrays have**

The "a = np.array" syntax is used to store an array variable into the NumPy library. And the "print(a.ndim)" syntax is used to provide feedback by displaying dimensional information to the user.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/038d4e64-7657-4bc5-b76d-532a7a973499" /></div>


**6. Changing one dimension to another**

<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/486364fc-0a6d-4f0f-b84e-a416d4b7e585" /></div>
The syntax "ndmin=5" is used to reshape the dimension created into the fifth dimension.


**7. Get the results of the desired elements of the following array**

1. Get the first element from the following array
	<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/037f31c5-c40e-4ad1-bf87-dd44c7f41bca" /></div>
  
  To retrieve the first element, you use [0] because the indexing of elements starts from 0, then 1, 2, 3, etc.

2. Get the second element from the following array
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/1ce42429-89b0-4db3-bf08-7cda4a02f4e9" /></div>

3. Get the third and fourth element from the following array
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/e451ddfc-598d-47e9-9182-ccf8bc66cc3c" /></div>
The "(arr[2] + arr[3])" syntax is used to find two elements, namely the third element and the fourth element.


**8. Accessing elements from a specified array.**

1. Access the element on the first row, second column
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/100a751c-43eb-4a8a-842a-e1ca8acde04c" /></div>
The "arr[0, 1]" syntax is used to retrieve the element at 1st row and 2nd column.

2. Access the element on the 2nd row, 5th column
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/3ed90c08-1da9-4c11-9d14-04dbfe1cbb7a" /></div>

3. Access the third element of the second array of the first array
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/45ab4aa6-8e58-4815-8e59-af84823b4d55" /></div>
The "arr[0, 1]" syntax is used to access the 2nd dimension, the 1st row, and the 3rd element.

---

**PANDAS**

Pandas is a powerful and widely used open-source Python library primarily used for data manipulation and analysis. It provides high-performance data structures and tools for working with structured data, making it an essential tool for data scientists and analysts.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/c61bbc0c-7f32-4d6c-a08d-ddce338ad8ce" /></div>

Pandas has two main objects: Series and DataFrame.

---

**SERIES**

The Series object is a ONE-dimensional array that can store various types of data, such as integers, floats, strings, and others. It does not have column names as it consists of only one column. Each element in a Series has a label called an index.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/ad859983-02ed-4305-b30e-42e18d605d21" /></div>

Convert it into a Series
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/e92fce17-0c4e-4e6c-b3dc-1efa44283d65" /></div>

Convert the Series to an array
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/c9f1b81a-f0fe-4f2d-a9f2-2d51d3b32978" /></div>

Display the indices.
The indices are represented as a range, where the start point is inclusive, and the stop point is exclusive in the range.
1. Implicit indexing: Default numerical index assigned based on positional order.
2. Explicit indexing: Custom labels or values are assigned to uniquely identify rows or columns.
   <div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/ced79214-b522-4aaf-9ffe-b208db3fe6c1" /></div>

When the implicit and explicit indices are the same, when we call the data, it will rely only on its explicit indices.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/78882cce-13fa-4a0d-85c3-fbf165aec920" /></div>

The result of name_2[0] is an error due to the similarity between the explicit indices and the implicit indices.

We'll now try to perform data-slicing
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/9a5a25b9-227a-4d75-87b2-1f3eb30c7711" /></div>

But if we slice its implicit indices, only the start point will appear, because implicit indices are in the form of a range
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/9df6e5fb-e7af-4967-bf82-e15b0db2333f" /></div>

---

**LOC AND ILOC**

Example of data where some implicit and explicit indices are the same.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/daed4282-ce5e-4877-b76b-ea20f7d731b2" /></div>

When we access a single index, it will display its explicit index.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/1c14dabb-944f-4cbd-ab97-78f0cfb9ac6c" /></div>

When explicit and implicit indices are the same, inconsistencies occur as in the case above.

To address this inconsistency, we will use the principles of loc and iloc.

loc is used to call its explicit indices, while iloc is used to call its implicit indices.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/e0311197-c12a-4c94-b99b-bbccd1107325" /></div>

---

**Dictionary -- Series**

<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/5ad762f6-1418-473e-b00a-b7e329be6fa0" /></div>

---

**DATA FRAME**

DataFrame is a two-dimensional tabular data structure with labeled axes (rows and columns). This allows for easy manipulation and analysis of data. Essentially, a DataFrame is a collection of series, with at least one series.

DataFrame With 2 Series : 
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/e4887335-6469-467f-8695-42bc2b299f1c" /></div>

<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/71cf88c5-48b9-4bd6-aa89-b19dc51a4e27" /></div>

---

**LOAD DATA CSV**

Load Data ‘Kelahiran_Bayi_Jakarta_2020’.csv that has been aplouded in the same folder in Python.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/cc981f7d-4505-4f79-b2c7-f3a8e4ea1799" /></div>

**Head()**

Head() function to a viewing top in data by default is top five can be customized as required.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/f3478c09-cf0f-44e3-87a6-81c7942a03f3" /></div>

**Tail()**

Tail()returns the last 5 rows if a number is not specified,returns a specified number of last rows.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/71529ffb-aae7-45c8-8391-72662d01268d" /></div>


**Info()**

Info()Info method prints information about the DataFrame.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/5b74d712-b193-41f3-b65d-661ec9924cad" /></div>


**Index**

Index returns the index information of the DataFrame.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/f01c39f6-1e0a-41f8-a92a-0e580115e46f" /></div>


**IsNull()**

isnull used to finds NULL values in DataFrame.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/bc8f9212-c4bf-45b8-857d-404ea1446473" /></div>


**NotNull()**

notnull used to finds values that are NOT NULL.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/555b7822-76fe-4a0f-8b65-4ca65bf952e2" /></div>


**Shape**

Shape is the number of rows and columns on the index of the DataFrame.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/6f85d98f-0528-460c-89a2-6f80bcaec669" /></div>


**Columns**

Column returns the label of each column in the DataFrame.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/c82909a0-6159-46e5-b847-41cbd3095f76" /></div>


**Describe**

Returns a description summary for each column in the DataFrame,describe contains numeric data from managed datasets.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/b15631d2-1fcb-4fd9-9661-b7af7e61af0c" /></div>


**Mean**

Mean (The average value) = Return the mean of the values in the specified axis.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/edfa4282-8c17-4b35-87c3-5974e8c37194" /></div>


**Median**

Median (The mid point value) = Return the median of the values in the specified axis.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/4ff140d8-7207-4df3-abc0-cea9bbc0848f" /></div>


**Mode**

Mode (The most common value) = Returns the mode of the values in the specified axis.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/5f6240ea-60f8-496e-bec5-f902488d9d6a" /></div>




Jum’at 

The df.unique() syntax is used to get unique values in the columns of a pandas DataFrame.


The df.nunique() is a function in Python that is used to get the unique number of values in a column or axis in a DataFrame.

The df.type_value_counts() is a method on a DataFrame in pandas that is used to count the number of occurrences of each unique value in a column, while ordering them based on the number of occurrences.

Call a specific column is a notation for retrieving certain columns from a DataFrame df. This notation will return a new DataFrame containing only the specified columns.

Calling a Python dataset with terms and conditions means retrieving or selecting certain data from a dataset based on certain terms or conditions. This can be done using boolean operators or logical statements, such as ==, !=, <, >, <=, >=, or and, or, not.

Calls several columns accompanied by a filter terms and conditions


DateTime 
DateTime is a module in Python that deals with real-time data and time. It provides classes and functions to manipulate and format dates and times. Here are some commonly used classes and functions in the DateTime module. 
date : This class represents a date (year, month, and day) without time.
 datetime : This class represents a date and time (year, month, day, hour, minute, second, and microsecond).
time : This class represents time (hour, minute, second, and microsecond) without a date.


Random Library 
The random module in Python provides various functions to generate random numbers. Here are some commonly used functions in the random library:
 random.random(): This function returns a random float number between 0.0 to 1.0.

Txt File - Open - Read - Close
Open : In Python, you can open and read a text file using the built-in open() function. The open() function in Python is used to open a file and return a file (.txt) object.

Read : The read() function in Python is used to read the contents of a file object that has been opened using the open() function. 

Close : The close() function in Python is used to close a file that has been opened using the open() function. This is important because it frees up system resources and ensures that any changes made to the file are saved.



**FUCTION**

**Python Functions** is a block of statements that return the specific task. The idea is to put some commonly or repeatedly done tasks together and make a function so that instead of writing the same code again and again for different inputs, we can do the function calls to reuse code contained in it over and over again.
1. In mathematics, a function is a process that relates between an input and an output.
2. In Python, apart from these relationship functions, functions are also a way to organize code with the ultimate goal of code being reusable.
3. Functions are defined with the def keyword followed by the function name and parameters in brackets ()
4. Optionally, a docstring can be added - a documentation string that describes the context of the function
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/72db590b-8e81-4998-b279-55fcc3d38184" /></div>

5. By default, Python will position according to the registration order in which it was defined, and must be called in that order.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/b773e719-d9c0-4065-b5c2-c0a28d55b15c" /></div>




**RETURN**

The Phython Return statement is a special statement that can use inside in function or method to send the function’s result back to the caller. A Return statement consist of the return keyword followed by an optional return value. The return value of a Python function can be any Python object.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/32b461d7-e5d5-49ca-a1bf-af39f4e2255a" /></div>

1. The return value of a function can be stored in a variable.

2. This will differentiate a function that returns a value from a function that does not return a value (often referred to as a procedure).
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/2768b84f-5538-416a-9fab-b6870ef39d80)" /></div>




**Pass by reference vs value**

The difference between pass-by-reference and pass-by-value is that modifications made to arguments passed in by reference in the called function have effect in the calling function, whereas modifications made to arguments passed in by value in the called function can not affect the calling function.
<div align="center"><img src="https://github.com/nabilahkh/Specialist-Python-Week-2/assets/92252191/3d1b8c22-ed7c-409c-8669-25dbc8f67f48" /></div>


<div align="center"><img src="" /></div>
