# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
## Step 1:
Get the two values from the user
## Step 2:
Import def keyboard and function_name
## Step 3:
Get the value from the user for the number of rotation
## Step 4:
Using the slicing concept rotate the list

## Step 5:
Print the values after circulation the values
## Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by:balasudhan p 
#RegisterNumber:212222240017
def circulate():
    l=eval(input())
    n=eval(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```    

## Output:
![Screenshot 2023-04-11 090404](https://user-images.githubusercontent.com/118807740/231055382-bef2a8fb-c6d6-4c56-b4ff-585322ac1344.png)


## Result: program for circulate N values executed Successfully
