<h3>GO_STP_7724-ASSIGNMENT-2</h3>

**DAY 4: ASSIGNMENT 2 (PYTHON EXERCISES)**

**DATE: 26 MAY 2021**

**AUTHOR: AAMIR P**

**REG. ID: GO_STP_7724**

<u>QUESTIONS</u>

<b>1. Is a list mutable?</b>

Yes, lists are mutable.

<b>2.Does a list need to be homogeneous?</b>

Lists can be either homogeneous or heterogeneous.

<b>3.What is the difference between a list and a tuple?</b>

The main difference between a list and a tuple is that lists are mutable while tuples are immutable. A list has a variable size while a tuple has a fixed size. 

<b>4. How to find the number of elements in the list?</b>

The most straightforward way to get the number of elements in a list is to use the Python built-in function len(). 

<b>5. How to check whether the list is empty or not?</b>

Using the len() function on a given list, we can check to find if it equals to 0. If it equals 0, then it is an empty list.

<b>6. How to find the first and last element of the list?</b>

In any list the first element is assigned index value 0 and the last element can be considered as a value -1. So we apply these index values to the list directly and get the desired result. 

<b>7. How to find the largest and lowest value in the list? </b>

The min () function in Python returns the lowest value and max () function in Python returns the largest value in a List . 

<b> 8. How to access elements of the list?</b>

To access elements of the list, we can use the square brackets for slicing along with the index or indices to obtain value available at that index. 

<b>9. Remove elements in a list before a specific index</b>

To remove an item at specified index or position from a List, we can use pop () method of List class with index provided as argument. 

<b>10. Remove elements in a list between 2 indices</b>

list_1 = [10,20,85,78,41,15,12] 


del list_1[2:6]

<b>11. Return every 2nd element in a list between 2 indices</b>

list = [10,20,85,78,41,15,12] 


list[0:6:2]

<b>12. Get the first element from each nested list in a list</b>

list = [[10,20,30],[40,50,60],[12,14,15]] 

for l in nested_list:
print(l[0],end=" ") 

<b>13. How to modify elements of the list?</b>

To change a list element we use, list name followed by the index position inside the square brackets ([]), and then provide the new value using the Equal sign. 

<b>14. How to concatenate two lists? </b>

using “+” operator

<b>15.How to add two lists element-wise in python? </b>

list1 = [1, 2, 3]
list2 = [4, 5, 6]
sum_list = []
for (item1, item2) in zip(list1, list2):
sum_list.append(item1+item2)
print(sum_list)

<b>16.Difference between del and clear?</b> 

Clear () function delete all the keys and values in the dictionary and leave the dictionary empty. While del <dict> , delete the complete dictionary; and when we want to find the deleted dictionary then it will give an error that <dict> is not defined. 

<b>17. Difference between remove and pop?</b>
  
Remove() deletes the matching element from the list whereas pop removes the element present at specified index. 

<b>18. Difference between append and extend?</b>

append () adds a single element to the end of the list whereas extend () can add multiple individual elements to the end of the list.
  
<b>19. Difference between indexing and Slicing? </b>

“Indexing” means referring to an element of an iterable by its position within the iterable. “Slicing” means getting a subset of elements from an iterable based on their indices.
  
  <b>20. Difference between sort and sorted?</b>
  
sort() function will modify the list it is called on. The sorted() function will create a new list containing a sorted version of the list it is given. The sorted() function will not modify the list passed as a parameter. 
  
  <b> 21. Difference between reverse and reversed? </b>
  
  reverse() actually reverses the elements in the container. reversed returns an object that can be used to iterate over the container's elements in reverse order. 
  
  <b> 22. Difference between copy and deepcopy? </b>
  
  In Python, we use = operator to create a copy of an object. It doesn't create a new object. It only creates a new variable that shares the reference of the original object. A deep copy creates a new object and recursively adds the copies of nested objects present in the original elements.If we make changes to any nested objects in original object old_list, we’ll see no changes to the copy new_list. 
  
  <b>23. How to remove duplicate elements in the list? </b>
  
  Using set data structure 
  
  <b> 24.How to find an index of an element in the python list? </b>
  
  The index () method returns the index of the specified element in the list . 
  
  <b> 25. How to find the occurrences of an element in the python list? </b>
  
  count() method helps to find the occurrences of an element in the python list. 
  
  <b> 26. How to insert an item at a given position? </b>
  
  insert() is an inbuilt function in Python that inserts a given element at a given index in a list. 
  
  <b>27. How to check if an item is in the list?</b>
  
  Python “in” is the most conventional way to check if an element exists in a list or not. This particular way returns True if the element exists in the list and False if the element does not exist in the list.
  
 <b>28. How to flatten a list in python? </b>
  
  Using sum(),the function has two parameters:”iterable” which is a list of lists and “start” which is an empty list that serves as the initial flat list to which items of the inner sublists are added
  
  <b>29. How to convert python list to other data structures like set, tuple, dictionary? </b>
  
A. Using tuple(list_name).
B. Using set(list_name).
C. Using dict(list_name).
  
  <b>30. How to apply a function to all items in the list? </b>

  Use map() to apply a function to all elements in a list.
  
  <b>31. How to filter the elements based on a function in a python list? </b>
       
       Using the built in function called filter().
       
  <b>32. How python lists are stored in memory?</b>
  
  Python has the variable refer to the value. Similar to pointers in C, variables in Python refer to values (or objects) stored somewhere in memory.

       
