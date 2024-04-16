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
Program to find the gcd of two number using function.
Developed by: Darius Rijin I
Register number: 212223230037
'''
    
def gcd():
    a,b=int(input()), int (input())
    if a>b:
        smaller=b
    else:
        smaller=a
    for i in range(1,smaller+1):
        if(a%i==0 and b%i==0):
            hcf =i
    print("GCD of two numbers is:",hcf)
```

## Output:
![Screenshot 2024-04-16 204346](https://github.com/DariusRijin07/GCD-of-two-numbers/assets/138849120/be0863b6-d9a9-4483-a7d6-8710110b95fb)


![Screenshot 2024-04-16 204420](https://github.com/DariusRijin07/GCD-of-two-numbers/assets/138849120/6ea1cd0b-2421-419a-a065-ff83f420f5c7)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
