# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
### Step 2: 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
### Step 6: 
## Program:
```
#Program to circulate N values.
#Developed by: LOKHNATH.J
#RegisterNumber: 23004865

def circulate():
    l1=eval(input())
    a=int(input())
    l2=[]
    for i in range(a,len(l1)):
        l2.append(l1[i])
    for i in range(a):
        l2.append(l1[i])
    print("After circulating the values are:",l2)
```
## Output:
![Screenshot 2023-11-14 085930](https://github.com/Lokhnath10/Circulate-the-values-of-N-variables/assets/138969918/b3b67fe7-cc12-4b4f-ba8b-5d1e5662e30d)


### Result:
Circulate the value of N variable are successfully executed
