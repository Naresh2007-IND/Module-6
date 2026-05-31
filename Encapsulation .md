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
```python
class Rectangle:

    def __init__(self, length=10, breadth=5):
        self.__length = length
        self.__breadth = breadth

        if self.__length > 0 and self.__breadth > 0:
            print("Length =", self.__length)
            print("Breadth =", self.__breadth)
        else:
            print("Invalid dimensions")

r = Rectangle()
```
## Output
<img width="258" height="68" alt="Screenshot 2026-05-31 154712" src="https://github.com/user-attachments/assets/c30c7f56-e167-4868-9737-be6735b18528" />

## Result
The code was successfully executed by using python
