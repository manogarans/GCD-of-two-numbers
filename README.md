# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```python
#GCD of a number.
#Developed by:Manogaran s
#Register Number:23004448
def gcd():
    num1=int(input())
    num2=int(input())
    for i in range(1,min(num1,num2)):
        if num1%i==0 and num2%i==0:
            gcd1=i
    print("GCD of two numbers is:",gcd1)
```
## Output:
![output](/GCD%20(2).png)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
