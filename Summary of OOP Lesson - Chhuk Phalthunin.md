The class started by the teacher asking students to create an empty git. Inside the git, we are to create 2 empty branches known as TP and Course.

After that we did a review of the OOP lesson. We discussed Function, Variables, Class Method, Constant, Module and Package. 

**1\. Variable**

* **What it is:** A named storage location in memory used to hold data.  
* **Example:**

name \= "Sophea"  
score \= 95

#### **2\. Constant**

* **What it is:** A value intended to remain fixed and unchanged throughout the program.  
* **Example:**  
  PI \= 3.14159

MAX\_USERS \= 100

#### **3\. Function**

* **What it is:** A standalone, reusable block of code that performs a specific task.  
* **Example:**

def greet(name):  
    return f"Hello, {name}\!"

#### **4\. Class**

* **What it is:** A blueprint or template used to create objects with shared attributes and behaviors.  
* **Example:**

class Student:  
    def \_\_init\_\_(self, name, major):  
        self.name \= name  
        self.major \= major

*   
* 

#### **5\. Method**

* **What it is:** A function defined inside a class that operates directly on that object's data.  
* **Example:**


class Student:  
    def \_\_init\_\_(self, name):  
        self.name \= name

    def introduce(self):  
        print(f"My name is {self.name}.")

#### **6\. Module**

* **What it is:** A single code file containing reusable code that can be imported into other files.  
* **Example:**


import math

print(math.sqrt(16))  \# 4.0

#### **7\. Package**

* **What it is:** A folder containing multiple related modules grouped together.  
* **Example structure:**  
* Plaintext

school/             \# Package (folder)  
├── \_\_init\_\_.py  
├── teachers.py     \# Module

* └── students.py     \# Module  
* 

After that, we discussed clean code. Clean code is fundamentally about maintaining consistency; we have to consider other people reading our code after us. We must be mindful of proper indentation and spacing, and leave helpful comments so we understand the code's purpose when revisiting it later. In Python, these best practices are defined by a style guide called **PEP 8**, which we should always strive to follow.  
