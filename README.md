# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the input value from the user.
### Step 2: 
Enter the list of numbers for circulation.
### Step 3: 
Get the value from the user for the number of rotation.
### Step 4: 
Using the slicing concept rotate the list.

### Step 5: 
Run the programme in code runner.
### Step 6: 
Show the values in output and close the variables.
## Program:
```
#Program to circulate N values.
#Developed by: S Adithya Chowdary 
#RegisterNumber: 21001700
def circulate():
    l = [10, 20, 30, 40, 50, 60]
    n = int(input())
    p = l[n:]+l[:n]
    print("After circulating the values are:",p)
 ```
## Output:
![OUTPUT](/IMAGES/image2.png)

## Result:
Thus the python program to circulate the n variable using function concept is solved.
