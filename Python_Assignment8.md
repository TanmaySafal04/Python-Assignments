1. Is the Python Standard Library included with PyInputPlus?
2. Why is PyInputPlus commonly imported with import pyinputplus as pypi?
3. How do you distinguish between inputInt() and inputFloat()?
4. Using PyInputPlus, how do you ensure that the user enters a whole number between 0 and 99?
5. What is transferred to the keyword arguments allowRegexes and blockRegexes?
6. If a blank input is entered three times, what does inputStr(limit=3) do?
7. If blank input is entered three times, what does inputStr(limit=3, default=&#39;hello&#39;) do?

#1 Is the Python Standard Library included with PyInputPlus?

No, It is not included in the Python Standard Library

#2 Why is PyInputPlus commonly imported with import pyinputplus as pypi?

It's an alias given to the PyInputPlus. We can use any other name as well. Giving a short name to the imorted library makes it handy to use.

#3 How do you distinguish between inputInt() and inputFloat()?

inputInt() is used to take integer input from the user whereas inputFloat() is used to take float input from the user




#4 Using PyInputPlus, how do you ensure that the user enters a whole number between 0 and 99?

we can use inputInt() to ensure that the user enters a whole number only along with grater thand and less than parameters to ensure the no. entered is within the desired range. Ex. pyip.inputint(min=0, max=99)

#5 What is transferred to the keyword arguments allowRegexes and blockRegexes?

A list of regex strings that are either explicitly allowed or denied will be transferred to the keyword arguments allowRegexes and blockRegexes.


#6  If a blank input is entered three times, what does inputStr(limit=3) do?

A RetryLimitException will be raised if blank value is entered 3 times when using inputStr(limit=3)

#7 If blank input is entered three times, what does inputStr(limit=3, default=&#39;hello&#39;) do?

If blank input is entered three times, default value specified in inputStr will be displayed. In this case it will display hello



```python

```
