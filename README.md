Python Program: Name Length and $ Count
Description

This Python program asks the user to enter their name and a symbol ($).
It then:

Calculates the length of the name.

Counts how many times the $ symbol appears in the entered text.

Code
name = input("enter your name:")
string1 = input("enter $:")

print("length of your name is", len(name))
print("$ repeats", str.count(string1, "$"))
How It Works

input() is used to take input from the user.

len(name) calculates the total number of characters in the name.

count() counts how many times the character $ appears in the given string.

Example

Input

enter your name: ali$$khan
enter $: $

Output

length of your name is 9
$ repeats 2
Note

For correct counting, the count() function should usually be used on the string that contains the characters.

Example:

print(name.count("$"))
