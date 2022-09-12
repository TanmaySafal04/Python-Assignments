# Questions
1. What exactly is []?
2. In a list of values stored in a variable called spam, how would you assign the value &#39;hello&#39; as the
third value? (Assume [2, 4, 6, 8, 10] are in spam.)
Let&#39;s pretend the spam includes the list [&#39;a&#39;, &#39;b&#39;, &#39;c&#39;, &#39;d&#39;] for the next three queries.
3. What is the value of spam[int(int(&#39;3&#39; * 2) / 11)]?
4. What is the value of spam[-1]?
5. What is the value of spam[:2]?
Let&#39;s pretend bacon has the list [3.14, &#39;cat,&#39; 11, &#39;cat,&#39; True] for the next three questions.
6. What is the value of bacon.index(&#39;cat&#39;)?
7. How does bacon.append(99) change the look of the list value in bacon?
8. How does bacon.remove(&#39;cat&#39;) change the look of the list in bacon?
9. What are the list concatenation and list replication operators?
10. What is difference between the list methods append() and insert()?
11. What are the two methods for removing items from a list?
12. Describe how list values and string values are identical.
13. What&#39;s the difference between tuples and lists?
14. How do you type a tuple value that only contains the integer 42?
15. How do you get a list value&#39;s tuple form? How do you get a tuple value&#39;s list form?
16. Variables that &quot;contain&quot; list values are not necessarily lists themselves. Instead, what do they
contain?
17. How do you distinguish between copy.copy() and copy.deepcopy()?

#1 What exactly is []?

It is an empty list.


#2 In a list of values stored in a variable called spam, how would you assign the value 'hello' as the third value? (Assume [2, 4, 6, 8, 10] are in spam.) Let's pretend the spam includes the list ['a', 'b', 'c', 'd'] for the next three queries.

spam.insert(2,'hello')



#3 What is the value of spam[int(int('3' * 2) / 11)]?

Considering spam=['a','b','c','d'] the value of  spam[int(int('3' * 2) / 11)] will be 'd'



#4 What is the value of spam[-1]?

The value of spam[-1] will be 'd'


#5 What is the value of spam[:2]? Let's pretend bacon has the list [3.14, 'cat,' 11, 'cat,' True] for the next three questions.

The value of spam[:2] will be ['a','b']. 

#6 What is the value of bacon.index('cat')?

The value of bacon.index('cat') will be 1

#7 How does bacon.append(99) change the look of the list value in bacon?

The list bacon will look like [3.14, 'cat', 11, 'cat', True, 99]


#8 How does bacon.remove('cat') change the look of the list in bacon?

The list bacon will look like [3.14, 11, 'cat', True, 99]


#9 What are the list concatenation and list replication operators?

'+' is the list concatenation operator whereas * is the list replication operator

#10 What is difference between the list methods append() and insert()?

append() adds an element at the end of a list whereas insert() adds an element at any specific index which we mention

#11 What are the two methods for removing items from a list?

pop() and remove() are the two methods for removing items from a list

#12 Describe how list values and string values are identical.

We can iterate through list as well as string values. In this way they are identical.

#13 What's the difference between tuples and lists?

Tuples are immutable means once declared, we cannot make changes to it whereas lists are mutable meaning we can make changes to it.

#14 How do you type a tuple value that only contains the integer 42?

t=(42,) is how we type a tuple value that only contains the integer 42

#15 How do you get a list value's tuple form?
    How do you get a tuple value's list form?
    
Don't know the answer. Not able to understand the question.



#16 Variables that "contain" list values are not necessarily lists themselves. Instead, what do they contain?

They will contain references to list values rather than list values themselves.





#17 How do you distinguish between copy.copy() and copy.deepcopy()?

copy.copy() will create a reference of the variable copy and any changes made to it will be reflected in the original copy. 
Whereas in copy.deepcopy() the changes made to this deepcopy won't make any changes to the original copy. It basically creates a new entity with the same value and features s the original copy.
