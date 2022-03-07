<!-- HEADER -->
<p align="center">
  <img  src="./../assets/header.png" />
</p>

# Lecture-6 Comments And String Methods in Python

## Comments in python

Comments in Python are the lines in the code that are ignored by the compiler during the execution of the program.

1. Single Line Comment (#)

A single-line comment begins with a hash (#) symbol. The single-line comment is used to comment only one line of the code. 
```python
#This is sample program 
print("roadtocode4u")
```
2. Multiline Comment ("""   """)

In Python Triple double quote (""") and single quote (''') are used for Multi-line commenting.Multi-line comment is useful when we need to comment on many lines. 
```python
"""
This is a comment
written in
more than just one line
"""
print("roadtocode4u")
```

## String Methods

1.  Upper()

Converts a string into upper case.
```python
myString="roadtocode4u"
newString=myString .upper()
print(newString)
```

2. Lower()

Converts a string into lower case.
```python
myString="ROADTOCODE4U"
newString=myString .lower()
print(newString)
```
3. Strip()

Removes white space from the end of String 
```python
str1="ROADTOCODE4U"
str2="ROADTOCODE4U             "
print(str1)
print(str2.strip())
```

4. Replace()

Replace in string
```python
myString="roadtocode4u"
newString=myString.replace("o","#")
print(newString)
```

5. split()

Splits the string at the specified separator, and returns a list.
```python
student="Harshada,Aniket,Prachi,Anjali"
print(student.split(','))
```

## Array 
 Collection of similar data type
 ```python
myString="India"
print(myString[2])
 ```

## Escape character

 An escape character is a backslash \ followed by the character you want to insert.

 ```python
 sentence="I\'m Good .She said , How Are You ?"
print(sentence)
 ```

## 🏠 HomeWork

>Write a program to implement upper(), lower(), strip() and replace() function on given string.

>Write a program to implement escape character to use single quote and double quote in the same string

## 🔗 Some Useful Links

## 📖 References

<!-- FOOTER -->
<p align="center">
  <img  src="./../assets/footer.png" />
</p>