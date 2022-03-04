<!-- HEADER -->
<p align="center">
  <img  src="./../assets/header.png" />
</p>

# Lecture-4 User Input & Type Casting in Python

## User Input

input()=To take input from user.

Example=
```python
val=input("Message")
```
```python
name=input("Enetr Yourname :")
print(name)
```
Formatting Output
```python
name=input("Enetr Yourname :")
print("Good Evening {}".format(name))
```
```python
val1=input("Enter val1:")
val2=input("Enter val2:")
sum=val1+val2
print(sum)
```

## Type Casting 
Type Casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users.<br><br>
Example=
```python
val1=int(input("Enter val1:"))
val2=int(input("Enter val2:"))
sum=val1+val2
print(sum)
```
```python
val1=(input("Enter val1:"))
val2=(input("Enter val2:"))
sum=int(val1) + int(val2)
print(sum)
```
Formatting Output

```python
val1=(input("Enter val1:"))
val2=(input("Enter val2:"))
sum=int(val1) + int(val2)
print("sum of {} and {} is {}".format(val1,val2,sum))
```


## 🏠 HomeWork

>Write a program to calculate bill when `rate` and `quantity` is given by user.

💡 HINT: use formula `bill` = `rate` * `quantity`, take input for `rate` and `quantity from user.

## 🔗 Some Useful Links

## 📖 References

<!-- FOOTER -->
<p align="center">
  <img  src="./../assets/footer.png" />
</p>