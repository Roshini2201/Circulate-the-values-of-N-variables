# Circulate the values of N variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the two values from the user. 
### Step 2: 
Assign the value of second variable to a temporary variable. 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list 
### step 5:
Print the values it would be interchanged
## Program:
```
#program to ciculate N values.
#Developed by: ROSHINI.S
#Register Number:212223240142.

def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![output](/img%202.png)
## Result:
Thus circulating n variables are successfully executed
