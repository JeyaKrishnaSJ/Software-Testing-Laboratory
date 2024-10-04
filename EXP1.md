# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 13/09/24                                                                          
### REGISTER NUMBER : 212222040064

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
a) do..while

```python
def display(): 
    start = input("Enter a positive value for START: ") 
    end = input("Enter a positive value for END: ") 
    if start.isnumeric() and end.isnumeric(): 
        while True: 
            start = int(start) 
            end = int(end) 
            print(start, end=' ') 
            if start < end: 
                start += 1 
            else: 
                break 
    else: 
        print("Enter a valid positive number.")

display()

```
b) while..do

```python
start = input("Enter a positive value for START: ") 
end = input("Enter a positive value for END: ") 

if start.isnumeric() and end.isnumeric(): 
    start = int(start) 
    end = int(end) 
    while start < end: 
        print(start) 
        start += 1 
else: 
    print("Enter a valid positive number.")

```
c) if..else
```python
def compare(): 
    a = input("Enter a value for A: ") 
    b = input("Enter a value for B: ") 
    try: 
        a = int(a) 
        b = int(b) 
        if a > b: 
            print("A is greater than B") 
        elif a < b: 
            print("B is greater than A") 
        else: 
            print("A is equal to B") 
    except ValueError: 
        print("Enter a valid number.")

compare()

```
d)switch
```python
def switch(): 
    switcher = { 
        0: "even", 
        1: "odd" 
    } 
    n = input('Enter a value for N: ') 
    try: 
        n = int(n) 
        print(switcher[n % 2]) 
    except ValueError: 
        print("Enter a valid number.")

switch()

```
e) for
```python
def iterate(): 
    string = input("Enter a string: ") 
    for i in string: 
        print(ord(i), end=" ") 

iterate()

```



### Output:


![1a](https://github.com/user-attachments/assets/c06152d5-160b-426d-8049-b47f05763b8f)
![1b](https://github.com/user-attachments/assets/e812d4cd-3b87-47db-a8fd-d6c614c2103f)
![Screenshot (55)](https://github.com/user-attachments/assets/2c43d1e1-26fc-4a68-860f-4c9d11e14da0)
![image](https://github.com/user-attachments/assets/ad165e89-95c2-433c-b8f0-db3d9f617de9)
![image](https://github.com/user-attachments/assets/953d3a2c-19c9-4d38-9207-93d044e314d0)


### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


