## *1. Write a Python program to create an array of 5 elements and display the array items Access each individual items through indexes*
_Code:_
```python
import arrray as arr
a= arr.array('d',[10,20,30,40])
print(a[0])
print(a[1])
print(a[2])
print(a[3])
```
_Output:_ ![Output](https://user-images.githubusercontent.com/79211248/120897317-14435e80-c643-11eb-9932-349f3e023da6.png)

## *2. Write a Python Program to reverse the order of items in the array.*
_Code:_
```python
import array as arr
arr = arr.array
arr=[1,2,3,4,5]
result = list(reversed(arr))
print "Reversed array using reversed() method:",result
res=arr[::-1]
print "Reversed arrary using list slicing is:",res
arr.reverse()
print "Reversed array using reverse() method",arr
```
_Output:_ ![Output](https://user-images.githubusercontent.com/79211248/120897347-49e84780-c643-11eb-82f1-0b68982741dd.png)

## *3. Write a Python program to append a new item to the end of the array.*
_code:_
```python
a= ['mango','orange','apple']
b= ['pear','grapes','banana']
a.append(b)
print a
```
_Output:_ ![output](https://user-images.githubusercontent.com/79211248/120910863-18ea3000-c6a0-11eb-90f9-fb54346364ff.png)

## *4. Write a Python program to remove a specified item using the index from an array.*
_Code:_
```python
a = [1,2,3,4,5]
a.pop(1)
print"removed a specified item using the index from an array by PDP operation: ",a
```

_Output:_![output](https://user-images.githubusercontent.com/79211248/120911417-07efed80-c6a5-11eb-8489-b1d03cd280b4.png)

## *5. Write a Python program to get the length of an array.*
_Code:_
```python
a=[1,2,3,4,'hello']
print"Display all elements:",a
print"Length of all elements: ", len(a)
```
_Output:_![output](https://user-images.githubusercontent.com/79211248/120911882-5488f800-c6a8-11eb-8182-6968eba8deb0.png)

