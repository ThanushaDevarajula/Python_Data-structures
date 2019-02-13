# Python_Data-structures
# INTRODUCTION TO DATA STRUCTURES
## INTRODUCTION
A data structure is a data organization, management and storage format that enables efficient access and modification. More precisely, a data structure is a collection of data values, the relationships among them, and the functions or operations that can be applied to the data.
There are four data types in the Python programming language:       
1.	 list                                                          
2.	 tuple                                                                                   
3.	 Dictionary                                                                           
4.	 Set                                                                           
## LIST
-	A list is a data structure that holds an ordered collection of items i.e. you can store a sequence of items in a list. It is changeable and allows duplicate members.
-	The list of items should be enclosed in square brackets[ ].
#### Example:
```
     Shop_list = ['apple', 'mango', 'carrot', 'banana']
```
### How to access elements from a list?

 There are various ways in which we can access the elements of a list
####	You access the list items by referring to the index number:
#### example:

````
thislist= ["apple", "banana", "cherry"]
print(thislist[1])
-banana
````

####	To change the value of a specific item, refer to the index number:
#### example:

````
thislist=["apple", "banana", "cherry"]
thislist[1]= "blackcurrant"
print(thislist)
>>[“apple”,”lackcurrent”,”cherry”]

`````

####	To determine if a specified item is present in a list use the in keyword:
#### example:

````
thislist = ["apple", "banana", "cherry"]
if "apple" in thislist:
print("Yes, 'apple' is in the fruits list")
else:
print(“No”)
>> Yes, 'apple' is in the fruits list
`````                                                              


### List Methods
A list object has number of member methods. The following list transformation functions update a list object.
````
Method	      Description

1. append()	  Adds an element at the end of the list
2. clear() 	  Removes all the elements from the list
3. copy()	    Returns a copy of the list
4. count()	  Returns the number of elements with the specified value
5. extend()	  Add the elements of a list (or any iterable), to the end of the current list
6. index()	  Returns the index of the first element with the specified value
7. insert()	  Adds an element at the specified position
8. pop()	    Removes the element at the specified position
9. remove()	  Removes the item with the specified value
10.reverse()	Reverses the order of the list
11.sort()	    Sorts the lis
``````
## TUPLE

-A tuple is a sequence of immutable Python objects. Tuples are sequences, just like lists. The differences between tuples and lists are, the tuples cannot be changed unlike lists and tuples use parentheses, whereas lists use square brackets.
#### Create a Tuple:
````
Thistuple=("apple", "banana", "cherry")
print(thistuple)
>>=("apple", "banana", "cherry")
`````
#### Access Tuple Items
-Return the item in position 1:
````
thistuple = ("apple", "banana", "cherry")
print(thistuple[1])
````
-You cannot change values in a tuple:
````
thistuple = ("apple", "banana", "cherry")
thistuple[1] = "blackcurrant"
print(thistuple)
>>("apple", "banana", "cherry")
`````
-You can loop through the tuple items by using a for loop.
````
thistuple = ("apple", "banana", "cherry")
for x in thistuple:
  print(x)
`````
#### Tuple methods:
Python has two built-in methods that you can use on tuples.
````
Method	Description
count()	Returns the number of times a specified value occurs in a tuple
index()	Searches the tuple for a specified value and returns the position of where it was found

`````
 
## DICTIONARY
-Dictionary in Python is an unordered collection of data values, used to store data values like a map, which unlike other Data Types that hold only single value as an element, Dictionary holds key : value pair.
    
#### Create and print a dictionary: 
````
thisdict={
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(thisdict)
>> {'brand': 'Ford', 'model': 'Mustang', 'year': 1964}
`````
#### Dictionary Methods
Python has a set of built-in methods that you can use on dictionaries.

````
Method	      Description
clear()	    Removes all the elements from the dictionary
copy()	    Returns a copy of the dictionary
fromkeys()	Returns a dictionary with the specified keys and values
get()	      Returns the value of the specified key
items()	    Returns a list containing the a tuple for each key value pair
keys()	    Returns a list containing the dictionary's keys
pop()	      Removes the element with the specified key
popitem()	  Removes the last inserted key-value pair
setdefault()	Returns the value of the specified key. If the key does not exist: insert the key, with the specified value
update()	    Updates the dictionary with the specified key-value pairs
`````

## SETS
 -A Set is an unordered collection data type that is iterable, mutable, and has no duplicate elements. Python's set class represents the mathematical notion of a set.
 -Once a set is created, you cannot change its items, but you can add new items.


#### Create a Set:
````
thisset={"apple", "banana", "cherry"}     # Note: the set list is unordered, meaning: the items will appear in a random order
print(thisset)
>>={"apple","cherry","banana"}

`````
-The set() Constructor
It is also possible to use the set() constructor to make a set.
````
Using the set() constructor to make a set:

thisset = set(("apple", "banana", "cherry")) # note the double round-brackets
print(thisset)
`````
#### Set Methods
-Python has a set of built-in methods same as tuple and list.
### Conclution
We have explored the built-in data structures of Python. These data structures will be essential for writing programs of reasonable size.



 

