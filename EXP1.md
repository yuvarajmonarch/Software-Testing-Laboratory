# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 21/08/2025                                                                        
### REGISTER NUMBER : 212222040186

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
### Do While
```
def display():
    start=input("Enter a positive value for START: ")
    end=input("Enter a positive value for END: ")
    if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=' ')
            if start<end:
                start+=1
            else:
                break
    else:
        print("Enter a valid positive number.")
display()
```
### While
```
start=input("Enter a positive value for START: ")
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
    start=int(start)
    end=int(end)
    while start<end:
        print(start)
        start+=1
else:
    print("Enter a valid positive number.")
```
### Switch
```
def switch():
    switcher={0:"even",1:"odd"}
    n=input('Enter a value for N: ')
    try:
        n=int(n)
        print(switcher[n%2])
    except ValueError:
        print("Enter a valid number.")
switch()
```
### If else
```
def compare():
    a=input("Enter a value for A: ")
    b=input("Enter a value for B: ")
    try:
        a=int(a)
        b=int(b)
        if a>b:
            print("A is greater than")
        elif a<b:
            print("B is greater than")
        else:
            print("A is equal to B")
    except ValueError:
        print("Enter a valid number.")

compare()
```
### For
```
def iterate():
    string=input("Enter a string: ") 
    for i in string:
        print(ord(i),end=" ")
iterate()
```
### Output:
### Do While
<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/5e26c7bd-44dd-4277-957a-20add7280ff7" />

### While
<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/5a960f30-85a1-41d6-8233-4140b9be8f3b" />

### Switch
<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/2fb7889b-1c42-434a-ade5-11b87e140033" />

### If Else
<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/ff2e2168-9b74-49ed-9d67-63c85e680370" />

### For
<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/f1e92f4a-3a0c-4617-8e7b-c73469a12926" />

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


