1. What are escape characters, and how do you use them?
2. What do the escape characters n and t stand for?
3. What is the way to include backslash characters in a string?
4. The string &quot;Howl&#39;s Moving Castle&quot; is a correct value. Why isn&#39;t the single quote character in the
word Howl&#39;s not escaped a problem?
5. How do you write a string of newlines if you don&#39;t want to use the n character?
6. What are the values of the given expressions?
&#39;Hello, world!&#39;[1]
&#39;Hello, world!&#39;[0:5]
&#39;Hello, world!&#39;[:5]
&#39;Hello, world!&#39;[3:]

7. What are the values of the following expressions?
&#39;Hello&#39;.upper()
&#39;Hello&#39;.upper().isupper()
&#39;Hello&#39;.upper().lower()
8. What are the values of the following expressions?
&#39;Remember, remember, the fifth of July.&#39;.split()
&#39;-&#39;.join(&#39;There can only one.&#39;.split())
9. What are the methods for right-justifying, left-justifying, and centering a string?
10. What is the best way to remove whitespace characters from the start or end?

#1 What are escape characters, and how do you use them?

Escape character are followed by a '\' symbol. Example:-  \n,\t etc.


#2 What do the escape characters n and t stand for?

escape characters 'n' and 't' are used for next line and for giving a tab space respectively.


#3 What is the way to include backslash characters in a string?

To include a backlash in a string we can use \\ (double backslash) eg: string="\\Tanmay"

#4 The string "Howl's Moving Castle" is a correct value. 
Why isn't the single quote character in the word Howl's not escaped a problem?


Because there's no closing to the single quote character so it won't be treated as a string.

#5 How do you write a string of newlines if you don't want to use the n character? 

 By using end=<character> at the end inside the print statement.

#6 What are the values of the given expressions? 
'Hello, world!'[1] ------> 'e'
'Hello, world!'[0:5] --------> 'Hello'
'Hello, world!'[:5] -------> 'Hello'
'Hello, world!'[3:] -------> 'lo, world!'



#7 What are the values of the following expressions? 
'Hello'.upper() ===> 'HELLO'
'Hello'.upper().isupper() ===> True
'Hello'.upper().lower() ===> 'hello'


#8 What are the values of the following expressions? 
'Remember, remember, the fifth of July.'.split() '-'.join('There can only one.'.split())

The above expression gives an error




#9 What are the methods for right-justifying, left-justifying, and centering a string?

.rjust() , .ljust() and .centre() are the methods used for right-justifying, left-justifying and centering a string.


#10 What is the best way to remove whitespace characters from the start or end?
 
 .trim() is the best way to remove whitespace characters from the start or end.


```python

```
