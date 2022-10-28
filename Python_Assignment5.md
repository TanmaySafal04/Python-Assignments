# Questions
1. What does an empty dictionary&#39;s code look like?
2. What is the value of a dictionary value with the key &#39;foo&#39; and the value 42?
3. What is the most significant distinction between a dictionary and a list?
4. What happens if you try to access spam[&#39;foo&#39;] if spam is {&#39;bar&#39;: 100}?
5. If a dictionary is stored in spam, what is the difference between the expressions &#39;cat&#39; in spam and
&#39;cat&#39; in spam.keys()?
6. If a dictionary is stored in spam, what is the difference between the expressions &#39;cat&#39; in spam and
&#39;cat&#39; in spam.values()?
7. What is a shortcut for the following code?
if &#39;color&#39; not in spam:
spam[&#39;color&#39;] = &#39;black&#39;

8. How do you &quot;pretty print&quot; dictionary values using which module and function?

#1 What does an empty dictionary's code look like?

An empty disctionary looks like ==> {} 

#2 What is the value of a dictionary value with the key 'foo' and the value 42?

 The value of a dictionary value with the key 'foo' and the value 42 is ==> {'foo':42}

#3 What is the most significant distinction between a dictionary and a list?

In a dictionary, the values exist in the form of key-value pair and we use these keys to access the values in a dictionary whereas in a list we use numerical indexes to access the values on a list. 

#4 What happens if you try to access spam['foo'] if spam is {'bar': 100}?

We will get 100 as the output.

#5 If a dictionary is stored in spam, what is the difference between the expressions 'cat' in spam and 'cat' in spam.keys()?

'cat' in spam returns the values corresponding to the key named 'cat' whereas spam.keys() will return all the available keys in the dictionary named spam.

#6 If a dictionary is stored in spam, what is the difference between the expressions 'cat' in spam and 'cat' in spam.values()

'cat' in spam returns the values corresponding to the key named 'cat' whereas spam.keys() will return all the available values in the dictionary named spam.

#7 What is a shortcut for the following code? if 'color' not in spam: spam['color'] = 'black'
spam['color']=['black' if 'color' not in spam]



#8 How do you "pretty print" dictionary values using which module and function?

 We can pretty-print dictionary values using pprint module


```python

```
