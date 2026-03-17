# Exp.No:30  
## COUNTER CLASS

---

### AIM  
To write a Python program to create a `Counter` class that can increment the value of a counter.

---

### ALGORITHM

1. **Start the Program.**
2. **Define the `Counter` class.**
   - Initialize the `current` variable with 0.
3. **Define the `increment()` method** to increment the value of `current` by 1.
4. **Define the `value()` method** to return the current value of `current`.
5. **Define the `reset()` method** to reset the `current` value back to 0.
6. **Create a `counter` object** of the `Counter` class.
7. **Call the `increment()` method** three times to increment the counter.
8. **Call the `value()` method** and print the result to show the current counter value.
9. **End the program.**

---

### PROGRAM

```

# Name: Vikram GS
# Reg No: 212222060296

class Student:
    def __init__(self, name, marks):
        self.name = name
        self.__marks = marks   # private variable

    def get_marks(self):
        return self.__marks

s = Student("Vikram", 90)

print("Name:", s.name)
print("Marks:", s.get_marks())
```

### OUTPUT
Object count: 3


### RESULT

Counter class successfully counts number of objects created.
