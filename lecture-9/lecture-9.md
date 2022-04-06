<!-- HEADER -->
<p align="center">
  <img  src="./../assets/header.png?" />
</p>

# Lecture-9 Sets in Python

## Tuple

It Data type which Act like Mathmatical sets.
{ }= Define sets.

## Properties of Sets 
* Unorderd  =

Unordered means that the items in a set do not have a defined order.
```python
MyColor={'Sky','Red','Pink','Yellow','Green'}
print(MyColor)
```

* Unindexed =

we cannot access the elements.

* Unique values 
```python
MyColor={'Sky','Red','Pink','Yellow','Green','Sky','Pink'}
print(MyColor)
```

## Adding values to Sets 

add()=The add() method adds an element to the set.But position is not decide because set are unorderd.
```python
Students={ "Aniket","Avishkar","priyanka"}
print(Students)
Students.add("Prachi")
print(Students)
```
## Remove Elements to Sets 

* remove() = Hard Removal
```python
Students={ "Aniket","Avishkar","priyanka","Vaibhavi","Vaishnavi"}
print(Students)
Students.remove("Vaibhavi")
print(Students)
```

* discard() = Soft Removal
```python
Students={ "Aniket","Avishkar","priyanka","Vaibhavi","Vaishnavi"}
print(Students)
Students.discard("Yash")
print(Students)
```
## Union of Sets 

The union() method returns a set that contains all items from the original set, and all items from the specified set.
```python
StudentsList1={ "Aniket","Avishkar","priyanka","Vaibhavi"}
StudentsList2={"Vaishnavi","Divya","Pranali","Meghana","Vaibhavi"}
AllStudents=StudentsList1.union(StudentsList2)
print(AllStudents)
```

## Intersection of Sets

The intersection() method returns a set that contains the similarity between two or more sets.
```python
StudentsList1={ "Aniket","Avishkar","priyanka","Vaibhavi","Vaishnavi"}
StudentsList2={"Vaishnavi","Divya","Pranali","Meghana","Vaibhavi"}
AllStudents=StudentsList1.intersection(StudentsList2)
print(AllStudents)
```
## Symmetric Differnce

```python
StudentsList1={ "Aniket","Avishkar","priyanka","Vaibhavi","Vaishnavi"}
StudentsList2={"Vaishnavi","Divya","Pranali","Meghana","Vaibhavi"}
OnlyOneClassStudent=StudentsList1.symmetric_difference(StudentsList2)
print(OnlyOneClassStudent)
```
The symmetric_difference() method in Python for two elements StudentsList1 and StudentsList2 is used to return the set of elements contained in both StudentsList1 and StudentsList2 but not common in both of them.

## 🏠 HomeWork
>🚁Write a program to use Add(),Remove() function to Sets.

>🛰️Write a program to use 5 different operation on sets.
## 🔗 Some Useful Links

## 📖 References

<!-- FOOTER -->
<p align="center">
  <img  src="./../assets/footer.png" />
</p>  