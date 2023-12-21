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
```
*/
Program to find the gcd of two number using function.
Developed by: s Deepika 
RegisterNumber:  23002257
*/
def gcd ():
    num1 = int(input())
    num2 = int(input())
    if num1>num2:
        min = num2
    else:
        min=num1
    for i in range(1,min+1):
        if(num1%i==0 and num2%i==0):
            gcd=i
    print("GCD of two numbers is:",gcd)

```

## Output:
![gcd of two number](gcd.png)
![image](https://github.com/Deepikasuresh05/GCD-of-two-numbers/assets/148514509/03e52fc1-1216-4164-9acb-201b67657f3c)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
