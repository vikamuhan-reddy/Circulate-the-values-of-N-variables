# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the program
### Step 2: 
Get the input from the user using eval function
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
using concatnation join the both the list 


### Step 6: 
print the swapped list
## Program:
```py 
#Program to circulate N values.
#Developed by: vikamuhan
#RegisterNumber:23012418
def circulate():
    l=list(eval(input()))
    n=int(input())
    l1=l[n:]+l[:n]
    print("After circulating the values are:",l1)
```

    


## Output:
![output](./git%20hub%201.png)

## Result:
Thus the python program for circulate the values of n variables is executed successfully
