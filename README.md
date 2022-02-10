# Inverse-of-matrix

## AIM:
To write a python program to find the inverse of a nested array.
## ALGORITHM:
### Step 1:
To import numpy as np

### Step 2:
Create a two list and entry the two matrix using for loop.

### Step 3:
Add the number in list1 and list1 added to list2.

### Step 4:
Inverse the martrix.

### Step 5:
Print the inverse of the matrix.
## PROGRAM:
```
import numpy as np
l1,l2=[],[]
a,b=int(input()),int(input())
for i in range(a):
    for j in range(b):
        num=int(input())
        l1.append(num)
    l2.append(l1)
    l1=[]
print(l2)
value=np.array(l2)
inverse=np.linalg.inv(value)
print(inverse)
```
## OUTPUT:
![inv](https://user-images.githubusercontent.com/94170892/153348019-940a5f70-3e91-48c9-827b-cb055b1ac084.png)

## RESULT:
The above program is successfully find the inverse of the nested array.
