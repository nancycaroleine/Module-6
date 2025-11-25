# Exp.No:30  
## Polymorphism

---

### AIM  
To write a Python program to create a class .

---

### ALGORITHM

1.Define class Cat with:
2.Constructor (name, age)
3.Methods: info(), make_sound()
4.Define class Cow similarly.
5.Create objects cat1 and cow1.
6.For each animal in (cat1, cow1):
7.Call make_sound()
8.Call info()
9.Call make_sound() again
10.End.

---

### PROGRAM
212223060181

NANCY
```
class Cat:
    def __init__(self, name, age):
        self.name = name
        self.age = age
    def info(self):
        print(f"I am a cat. My name is {self.name}. I am {self.age} years old.")
    def make_sound(self):
        print("Meow")
class Cow:
    def __init__(self, name, age):
        self.name = name
        self.age = age
    def info(self):
        print(f"I am a Cow. My name is {self.name}. I am {self.age} years old.")
    def make_sound(self):
        print("Moo")
cat1 = Cat("Kitty", 2.5)
cow1 = Cow("Fluffy", 4)
for animal in (cat1, cow1):
    animal.make_sound()
    animal.info()
    animal.make_sound()
```

### OUTPUT

<img width="771" height="238" alt="image" src="https://github.com/user-attachments/assets/3e5c2597-5c0c-4301-9486-c421e7c5b13a" />

### RESULT

Thus, the python code is written and executed successfully.
