# Questions


1. In the below elements which of them are values or an expression? eg:- values can be
integer or string and expressions will be mathematical operators.
*
hello

-87.8

-

/

+

6

Answer:
Values are: hello,-87.8,6
Expressions are: *,-,/,+



2. What is the difference between string and variable?

Answer: A String is a series of characters which can't store any value.
        A variable is a memory location where a value can be stored. It can be of type float,integer,string etc.




3. Describe three different data types.

Answer: The three types of data types are:
         i) Integer: It stores decimal numbers either zero, positive or negative. It can't store fractional value.
         ii) Float: Unlike integer, it can also store fractional value
         iii) String: It is a series of characters and can store any data type by implicit conversion.

4. What is an expression made up of? What do all expressions do?

Answer: An expression is a combination of variables and operators which compute a certain value. Expression calculates the value
        based on the order of precedence of operators.

5. This assignment statements, like spam = 10. What is the difference between an
expression and a statement?

Answer: An expression is a single statement which computes a value whereas a statement may or may not compute a certain
        value. It is usally contained within the body of a class or a function or a loop and even outside their body.

6. After running the following code, what does the variable bacon contain?
   bacon = 22
   bacon + 1

Answer: The value of bacon would still remain 22 as after incrementing the value of bacon by 1, we are not storing it
        in the variable bacon again. If we would have written bacon=bacon+1 then we would have got the value 23.


7. What should the values of the following two terms be?
i) "spam" + "spamspam"   
ii) "spam"*3 

Answer: i) spamspamspam   (simple concatenation of two strings)
        ii) spamspamspam   (repition of a string 3 times)

8. Why is eggs a valid variable name while 100 is invalid?

Answer: There are certain rules in python regarding the name of a variable. A numeric value can't be a variable as it can't             store any value whereas eggs can store a value and it follows the rules of naming a variable. 

9. What three functions can be used to get the integer, floating-point number, or string
version of a value?

Answer: int(),float() and str() are the three functions can be used to get the integer, floating-point number and string
version of a value respectively.

10. Why does this expression cause an error? How can you fix it?
'I have eaten' + 99 + 'burritos'

Answer: Here we are trying to concatenate an integer value with the string which is not possible unless we convert that integer
        value to string. We can fix it by writing 'I have eaten' + str(99) + 'burritos'.


```python

```
