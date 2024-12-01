
## 'Input' Comment Clarification

Programmers can pass string data into your programs using `input`.

```py
# --- input ---

# allows the user to enter text
user_variable = input("enter some text:\n")
# stores a value in terms of a string no matter what value you give it

# --- output ---

#This program prints a message but does not ask for 
#a new text to be stored in  the user_variable.Instead,
#it simply concatenates the string "thank you for this text:" 
# with the previously stored value inside user_variable.
# This works because the stored value is a string.

print('thank you for this text: ' + user_variable)

