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
<img width="430" height="170" alt="image" src="https://github.com/user-attachments/assets/6f75dd75-56e3-4c9f-872e-cc06b06c04a1" />

### While
<img width="330" height="247" alt="image" src="https://github.com/user-attachments/assets/c59c04aa-108d-47f1-a3fd-af7c6a99fca3" />

### Switch
<img width="312" height="147" alt="image" src="https://github.com/user-attachments/assets/fba86a5a-9048-4141-806c-7fee2dcddf6f" />

### If Else
<img width="301" height="161" alt="image" src="https://github.com/user-attachments/assets/8469c712-f82d-4f93-9769-8f43b62c5dd6" />

### For
<img width="297" height="122" alt="image" src="https://github.com/user-attachments/assets/f324141c-bc47-466a-befb-e4e5d14f6084" />

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


