<!-- HEADER -->
<p align="center">
  <img  src="./../assets/header.png" />
</p>

# Lecture-13 Logical Operators in Python

> 🚁Write a program to take input for marks of 5 subject and display the grade.

💡 HINT : Per=(total/500)*100

* If the percentage  greater than 90 “Grade: A” is printed.
* If the percentage  greater than 80 “Grade: B” is printed.
* If the percentage  greater than 70 “Grade: C” is printed.
* If the percentage  greater than 60 “Grade: D” is printed.
* otherwise , Fail is Printed.
```python
👨‍💻 program=

marathi,hindi,english,math,science= input("Enter Marks of 5 Subject").split()
sum=int(marathi)+int(hindi)+int(english)+int(math)+int(science)
per=(sum/500)*100
print("Percentage :",per,"%")
if per>=90:
  print("Grade A")
elif per>=80:
  print("Grade B")
elif per>=70:
  print("Grade c")
elif per>=60:
  print("Grade D")
else:
  print("FAIl")

💻Above code will result as : 

Enter Marks of 5 Subject: 91 92 93 94 95
Percentage : 93.0 %
Grade A

Enter Marks of 5 Subject : 81 84 85 88 84
Percentage : 84.399 %
Grade B

Enter Marks of 5 Subject : 74 74 71 71 73
Percentage : 72.6 %
Grade c

Enter Marks of 5 Subject : 66 67 65 64 63 
Percentage : 65.0 %
Grade D

Enter Marks of 5 Subject : 35 42 20 23 31
Percentage : 30.2 %
FAIl
```

* If the condition sequence will change , then output will also change.👇👇 Because we have not set any boundary conditions.


```python
👨‍💻 program=

marathi,hindi,english,math,science= input("Enter Marks of 5 Subject : ").split()
sum=int(marathi)+int(hindi)+int(english)+int(math)+int(science)
per=(sum/500)*100
print("Percentage :",per,"%")
if per>=60:
  print("Grade D")
elif per>=70:
  print("Grade C")
elif per>=80:
  print("Grade B")
elif per>=90:
  print("Grade A")
else:
  print("FAIl")

💻Above code will result as : 

Enter Marks of 5 Subject : 90 96 97 94 95
Percentage : 94.399 %
Grade D

Enter Marks of 5 Subject : 87 74 87 98 68
Percentage : 82.8 %
Grade D

```

* Give Boundary conditions of the above Program 

```python

👨‍💻 program=

marathi,hindi,english,math,science= input("Enter Marks of 5 Subject : ").split()
sum=int(marathi)+int(hindi)+int(english)+int(math)+int(science)
per=(sum/500)*100
print("Percentage :",per,"%")
if per>=60 and per<70:
  print("Grade D")
elif per>=70 and per<80:
  print("Grade C")
elif per>=80 and per<90:
  print("Grade B")
elif per>=90: and per<=100:
  print("Grade A")
else:
  print("FAIl")

💻Above code will result as : 

Enter Marks of 5 Subject : 91 93 93 98 85
Percentage : 92.0 %
Grade A

Enter Marks of 5 Subject : 65 54 65 67 76
Percentage : 65.4 %
Grade D
```

## Logical Operators 

Logical operators are used to combine conditional statements.

### AND Operator

Result True, if both operand condition are true otherwise false.

```python
👨‍💻 program =

# hsc>60 and jee>120
hsc=50
jee=120
result= hsc>60 and jee>120
print(result)

💻Above code will result as : False
 
 ## First condition is false and Second Condition is True therefore, result is false.
```
```python
👨‍💻 program =

# hsc>60 and jee>120
hsc=80
jee=50
result= hsc>60 and jee>120
print(result)

💻Above code will result as : False
 
## First condition is True and Second Condition is False therefore, result is false.
```
```python
👨‍💻 program =

# hsc>60 and jee>120
hsc=5
jee=30
result= hsc>60 and jee>120
print(result)

💻Above code will result as : False

## First condition is False and Second Condition is False therefore, result is false.
```
```python
👨‍💻 program =

# hsc>60 and jee>120
hsc=80
jee=130
result= hsc>60 and jee>120
print(result)

💻Above code will result as : True

## First condition is True and Second Condition is True therefore, result is True.
```

### OR Operator

Result True if both operand condition are true and one of the condition is true otherwise result False.

```python
👨‍💻 program =

# neet>520 or aiims>220
neet=80
aiims=130
result=neet>520 or aiims>220
print(result)

💻Above code will result as : False

## First condition is False and Second Condition is False therefore, result is False.
```
```python
👨‍💻 program =

# neet>520 or aiims>220
neet=530
aiims=130
result=neet>520 or aiims>220
print(result)

💻Above code will result as : True

## First condition is True and Second Condition is False therefore, result is True because one of the condition is true.
```
```python
👨‍💻 program =

# neet>520 or aiims>220
neet=120
aiims=230
result=neet>520 or aiims>220
print(result)

💻Above code will result as : True

## First condition is False and Second Condition is True therefore, result is True because one of the condition is true.

```
```python
👨‍💻 program =

# neet>520 or aiims>220
neet=530
aiims=230
result=neet>520 or aiims>220
print(result)

💻Above code will result as : True

## First condition is True and Second Condition is True therefore, result is True because both of the condition is true.

```
## 🧠📝Always Remember

In python don't use logical operator symbol like (&&) (||).

In python you can use Logical operator keywords like "and" "or".

## 🏠 HomeWork
>🚁Write a program Check Number is Divisible by 3 and 5 using "and" operator.

>🛰️Write a program to check person does gym or yoga and if one or both of them are doing ,then give healthy habit otherwise not.

## 🔗 Some Useful Links

## 📖 References

<!-- FOOTER -->
<p align="center">
  <img  src="./../assets/footer.png" />
</p>  