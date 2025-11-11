# Exp.No:22  
## Destructor

---

### AIM  
To create a Python class `Student` with a destructor.

---

### ALGORITHM

1. Begin the program.  
2. Define the `student` class.  
3. Inside the `student` class, define the `__init__` method (constructor) and the `__del__` method (destructor).  
4. Create an object `s2` of the `student` class. When the object `s2` is created, the `__init__` method is called, and its print statements are executed.  
5. Use the `del` statement to delete the object `s2`. This triggers the `__del__` method (destructor), and the respective print statements are executed.  
6. Terminate the program.

---

### PROGRAM

```
class Student:
    def _init_(self):
        print("Employee created.")
    def _del_(self):
        
        print("Destructor called, Employee deleted.")
Student()
```

### OUTPUT
<img width="1165" height="207" alt="438288410-914f3b94-78c3-44e4-a041-bfdefaadd169" src="https://github.com/user-attachments/assets/ebc77903-9b4f-4989-9b85-c8ffdfde7385" />


### RESULT
Thus a Python class Student with a destructor was executed and implemented successfully.
