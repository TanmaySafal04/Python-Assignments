# Questions
1. Why are functions advantageous to have in your programs?
2. When does the code in a function run: when it&#39;s specified or when it&#39;s called?
3. What statement creates a function?
4. What is the difference between a function and a function call?
5. How many global scopes are there in a Python program? How many local scopes?
6. What happens to variables in a local scope when the function call returns?
7. What is the concept of a return value? Is it possible to have a return value in an expression?
8. If a function does not have a return statement, what is the return value of a call to that function?
9. How do you make a function variable refer to the global variable?
10. What is the data type of None?
11. What does the sentence import areallyourpetsnamederic do?
12. If you had a bacon() feature in a spam module, what would you call it after importing spam?
13. What can you do to save a programme from crashing if it encounters an error?
14. What is the purpose of the try clause? What is the purpose of the except clause?


#1 Why are functions advantageous to have in your programs?

Functions enables code reusability i.e, if we want to perform a certain operation on a list of values we 
can just pass those values into that function and get the output returned. Also debugging a code is easier
when we use functions in our program because the name of a function usually indicates the type of operation
it performs.


#2 When does the code in a function run: when it's specified or when it's called?

The code in a function runs when the function is called and usually returns a value.


#3 What statement creates a function?

def is the keyword used to create a function.Eg- def prime(a): 
Here def is used to create a function whose name is prime and it takes a single parameter


#4 What is the difference between a function and a function call?

A function is used to perform a certain operation and enables code reusability. A function call is used to run the 
code within the function and in return expects a value to be returned by function but it's not mandatory.

#5 How many global scopes are there in a Python program? How many local scopes?

There's only one global scope in a python program. But there can be many local scopes in a python program. 
The number of local scopes depends on the number of loops, functions, conditions etc. used in a 
python program.

#6 What happens to variables in a local scope when the function call returns?

The variables in the local scope of that function is used and it occupies memory and a certain operation is performed
using those variables or on those variables. The local variables present elsewhere other than in the function called
remain unaffected.




#7 What is the concept of a return value? Is it possible to have a return value in an expression?

Return value is a a value returned by a function or an expression. Yes lambda expression can return a value so an 
expression can return a value.

#8 If a function does not have a return statement, what is the return value of a call to that function?

No value will be return. Even if we use a print statement we would get None






#9 How do you make a function variable refer to the global variable?

We can make a function variable refer to the global variable by creating an object of a class and using the reference
of the class which is the object to refer to the global vairable.



#10 What is the data type of None?

The data type of None is NoneType

#11 What does the sentence import areallyourpetsnamederic do?

This sentence will give an error as there's no such module in python named areallyourpetsnamederic.
If such module exists, then this statement will simply import this module and we can use it in our code.



#12 If you had a bacon() feature in a spam module, what would you call it after importing spam?

from spam import bacon



#13 What can you do to save a programme from crashing if it encounters an error?

We can handle the expression using try and except by keeping the code in the try block and using except to return 
the type of Exception whenever an error occurs.

#14 What is the purpose of the try clause? What is the purpose of the except clause?

try clause is used to test any block of code for errors. except clause is used to exceute a certain code when any
error is encountered in the code enclosed in the try block.


