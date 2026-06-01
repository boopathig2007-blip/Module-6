# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
class Student:
    def __init__(self, name, marks):
        self.__name = name      # Private member
        self.__marks = marks    # Private member

    def display(self):
        print("Name :", self.__name)
        print("Marks:", self.__marks)

# Object Creation
s = Student("Arun", 85)

# Accessing private members through a method
s.display()
## Output
Name : Arun
Marks: 85
## Result
Thus, the Python program demonstrating Encapsulation using Private Members was executed successfully, and the private data members were accessed through a public method.
