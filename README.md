# Non_techie_Intro_to_Python
This is a collection of Jupyter Notebooks for non-techie newbies to get familiar with Python
----
## OUTLINE:

### 1. Inputs in Python:
- I, Working with inputs:
    - 1, Directly type down the data's value.
    - 2, Assign data into variables.
- II, Types of inputs:
    - 1, String
    - 2, Float and int
    - 3, Bool
    - 4, Data casting

---- 

### 2. Working with strings:
- I, What are strings in Python?
- II, Escape sequences
- III, Raw strings
- IV, Indexing and slicing
- V, Strings concatenation
- VI, format method

----

### 3. Calculator_Working with Boolean and Numerical data:
- I, Python's operators
- II, Assignment operators
- III, Comparison operators
- IV, Logical operators

----

### 4. Data structure: Overview of tuples, lists and sets
      
----

### 5. Data structure: Lists
- I, Definition
- II, Index and slice
- III, Split a strings to a list
- IV, Mutate a list
- V, Clone and copy a list:
- VI, Concatenate lists:
- V, Sort a list:
- V, Ammendment:
    - Pop an element from a list
    - Insert an element into a list
 
----

### 6. Data structure: tuples

- I, Definition:
- II, Index and slice: 
    - len()
- III, Immutable:
- IV, Concatenate tuples:
- V, Sort a tuple into a sorted list:
- VI, Appendix:
    - Create nested tuples
    - Call out elements of the same index within nested tuples
    - Assign values within a tuple to variables
    - Count the frequency of a value within a tuple

----

### 7. Data structure: Sets

- I, Definition:
- II, Converse a list or a tuple into a set:
- III, Unindexable:
- IV, Mutate sets:
- V, Logical operators and corresponding set's methods:
- VI, Something to notice:

----

### 8. Data structure: Dictionaries

- I, Definitions
- II, Membership check
- III, Call out values
- IV, Modify contents
    - 1, Add new keys
    - 2, Delete keys

----
### 9. Syntax:

- I, Comment:
- II, Keywords:
- III, Indentation:
- IV, Write neat code:

---- 

### 10. Branching in Python:
if, elif, else

----

### 11. Looping:

- I, What is a loop?
- II, Basic loops
- III, Looping using branching statement?
- IV, Special keywords for looping.

----

### 12. Working with operating system:

- Import the module
- Working with already existing directories:
    - get the current working directory
    - change the current working directory
    - show the content within a folder
    - show the content of each sub-folder within a directory
    - check the metadata of a folder:
        -  intepret timestamp
- Working with the operating system:
    - Show the directories of all environments
    - Show the directory of a specific environment
- Create new folders:
    - mkdir vs makedirs
    - rename a folder
    - check if the newly created directory is a file or a folder
    - rmdir vs removedirs
    - check if a directory exists or not
- Create new files:
    - join path
    - check the name of the file
    - check the full directory of the file
    - check the name and the directory of the file
    - check the extension of the file
 
----

### 13. Working with text-based file:
- Download CONTENT FROM an API.
- open a file in a simple way.
    - Read a file
    - Check the mode and the name of a file
    - REMEMBER to CLOSE the file afterwards
    - Check whether you have closed the file or not
- open a file in a smart way.
    - Print out a certain number of characters.
    - Print out a certain number of lines.
- write new content into a file and delete pre-existing contents
- Append new content into a file
- Additional modes to work with files
- Copy a file

----

### 14. Working with other file formats: csv and json
- I, What is a file format?
- xlsx
- csv
- json

----

### Apd_Handling exceptions:

- What are exceptions?
- Ways to handle exceptions:
    - try except:
        - in general
        - specifically
        - print out name of the errors arising
    - try except else
    - try except else finally

----

### Apd_Working with Pandas
- What is pandas?
- Create a pandas dataframe:
    - From a numpy array
    - From a dictionary
- Load data from file_paht or link: 
- Extract data from a df:
    - Extract columns
    - Extract specified rows and columns, using:
        - df.loc[]
        - df.iloc[]
- Modify a dataframe:
    - Rename the header
    - Drop the columns or rows
    - Rename the columns
- Get the information of a data:
    - Data types within df

----

### Apd_Numpy:

- What is numpy?
-  Working with 1dNumpy arrays
- Working with 2dNumpy arrays

---

### Apd_Exploratory data analysis:

- Load the data
- Have an overview of the data
- Data processing:
- EDA
- Lists of df functions taken into account:
    - pd.options.mode.use_inf_as_na = True #set the empty strings as NaN values
    - df.drop
    - df.replace()
    - df.isnull().to_frame()
    - df.dropna()
    - df.fillna()
    - df.select_types(include = np.number).columns.to_list()
    - df.describe()
    - df.info()
    - df.transpose()
    - df.pivot()
    - 
