# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Clone the repository from github
### Step 2: 
Assign the function command in the program
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
using the slicing concept rotate the list
### Step 5: 
end the program
## Program:
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
## Output:
![output](output2.png)
## Result:
Thus the circulate n variables are successfully executed