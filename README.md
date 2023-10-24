# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 

### Step 1:
Get the two values from user 
### Step 2: 
Assign the value of second variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Assign the value in temporary variable to the first variable
### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the program
## Program:
```python
#Program to circulate N values.
#Developed by:PRAVIN KUMAR A. 
#RegisterNumber:23007430
def circulate():
   list1=eval(input())
   n=int(input())
   result=list1[n:]+list1[:n]
   print("After circulating the values are:",result)

```


## Output:
![output](https://github.com/RAVENPRAVIN/Circulate-the-values-of-N-variables/assets/146820534/80a7a66c-9fd3-405a-ad7d-fc5f0b9580a1)


## Result:
Thus the python program of circulate n of variables executed successfully