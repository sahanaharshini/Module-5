# Exp.No:21  
## Constructors - Parameterized Constructor

---

### AIM  
To write a Python code to create a class for a person with a parameterized constructor, which will take the `name` and `userid` of the person as parameters and print the `userid` of the person.

---

### ALGORITHM

1. Begin the program.  
2. Define a `person` class.  
3. The `person` class should have a parameterized `__init__` method that accepts two parameters: `name` and `userid`.  
4. Inside the `__init__` method, assign the `name` to `self.name` and the `userid` to `self.userid`.  
5. Print the `self.userid`.  
6. Prompt the user to enter their `name` (string) and `userid`.  
7. Create an instance `s1` of the `person` class by passing the entered `name` and `userid` to the constructor.  
8. Terminate the program.

---

### PROGRAM

```
class Student:
    def __init__(self,a,b):
        self.roll=a
        self.name=b
    def show(self):
        print("Hello my id is :", self.roll)
        print("My name is :", self.name)
name=input()
roll=input()
s1 = Student(name,roll)
s1.show()
```

### OUTPUT
<img width="1166" height="255" alt="438287456-40db141a-3224-47f2-9aed-e4d084e61e5f" src="https://github.com/user-attachments/assets/d6f8961b-4c3d-42fe-8d16-c12af98230e7" />

### RESULT
Thus a Python code to create a class for a person with a parameterized constructor, which will take the name and userid of the person as parameters and print the userid of the person was executed and implemented successfully.
