# Data-structures-in-python
Types of data structures you can use in python

Python Data Structures – Lists
A list is defined as an ordered collection of items, and it is one of the essential data structures when using Python to create a project
List_A = [item 1, item 2, item 3….., item n]
Python Data Structures – Tuples
A tuple is a built-in data structure in Python that is an ordered collection of objects. Unlike lists, tuples come with limited functionality.
tuple_A = (item 1, item 2, item 3,…, item n)
Python Data Structures – Sets
A set is defined as a unique collection of unique elements that do not follow a specific order. Sets are used when the existence of an object in a collection of objects is more important than the number of times it appears or the order of the objects
set_a = {“item 1”, “item 2”, “item 3”,….., “item n”}
What are some examples of data types in Python?
Numeric
In Python, numeric data type represent the data which has numeric value. Numeric value can be integer, floating number or even complex numbers. These values are defined as int, float and complex
Sequence Type
In Python, sequence is the ordered collection of similar or different data types. Sequences allows to store multiple values in an organized and efficient fashion. There are several sequence types in Python –
•	String
•	List
•	Tuple
Boolean
Data type with one of the two built-in values, True or False. Boolean objects that are equal to True are truthy (true), and those equal to False are falsy (false). But non-Boolean objects can be evaluated in Boolean context as well and determined to be true or false. It is denoted by the class bool.
Set
In Python, Set is an unordered collection of data type that is iterable, mutable and has no duplicate elements. The order of elements in a set is undefined though it may consist of various elements.
Dictionary
Dictionary in Python is an unordered collection of data values, used to store data values like a map, which unlike other Data Types that hold only single value as an element, Dictionary holds key:value pair. Key-value is provided in the dictionary to make it more optimized. Each key-value pair in a Dictionary is separated by a colon :, whereas each key is separated by a ‘comma’.
difference between lists and tuples?
LIST	TUPLE
Lists are mutable	Tuples are immutable
Implication of iterations is Time-consum ...	The implication of iterations is compara ...
The list is better for performing operat ...	Tuple data type is appropriate for acces ...
Lists consume more memory	Tuple consume less memory as compared to ...


Difference between List and Dictionary:
List	Dictionary
List is a collection of index values pai ...	Dictionary is a hashed structure of key ...
List is created by placing elements in [ ...	Dictionary is created by placing element ...
The indices of list are integers startin ...	The keys of dictionary can be of any dat ...
The elements are accessed via indices.	The elements are accessed via key-values ...
		
is python case sensitive?
First, let’s clarify what case sensitivity is. It’s the differentiation between lower- and uppercase letters. It can be a feature not only of a programming language but of any computer program.
The shortest answer to the question of case sensitivity in Python is yes. It is a case-sensitive language, like many other popular programming
languages such as Java, C++, and JavaScript. Case sensitivity in Python increases the number of identifiers or symbols you can use.
with what number, does indexing start in Python?
Indexing in Python means referring to an element of an iterable by its position within the iterable. 2 Each character can be accessed using their index number. 3 To access characters in a string we have two ways: Positive index number Negative index number
How do you write comment in Python?
To write a comment in Python, simply put the hash mark # before your desired comment: # This is a comment Python ignores everything after the hash mark and up to the end of the line.
How do you display the rows and columns in a pandas dataframe?
dataframe = pd.DataFrame(data.data, columns=data.feature_names)
print(dataframe)



How to delete a column in pandas Dataframe?
In Order to delete a column in Pandas Data Frame, we can use the drop () method.

