# Exp.No:29  
## Encapsulation

---

### AIM  
To write a Python program to create a class `Student` with the private members `name` and `age`, and add getter and setter methods to initialize and modify the `age` variable.

---

### ALGORITHM

1. **Start the Program.**
2. **Define the `Student` class.**
   - Inside the `Student` class, define the `__init__` method to initialize `name` and the private member `__age`.
3. **Define a getter method** `get_age` to return the value of the private member `__age`.
4. **Define a setter method** `set_age` to set a new value to the private member `__age`.
5. **Create an object `stud`** of the `Student` class with the name 'Jessa' and age 14.
6. **Print the name and the age** of `stud` using the getter method.
7. **Use the setter method** `set_age` to change the age of `stud` to 16.
8. **Print the name and the updated age** of `stud` using the getter method.
9. **End the program.**

---

### PROGRAM
212223060181

NANCY
```
class Employee:
    def __init__(self, name, salary):
        self.name = name
        self.salary = salary
    def show(self):
        print("Name: ", self.name, "Salary:", self.salary)
emp = Employee('Jessa', 10000)
print("Name: ", emp.name, 'Salary:', emp.salary)
emp.show()
```
### OUTPUT

<img width="841" height="282" alt="image" src="https://github.com/user-attachments/assets/b9f471eb-89cd-4ef0-886a-00d35bbe48a4" />

### RESULT

Thus, the python code is written and executed successfully.
