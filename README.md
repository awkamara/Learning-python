# **Learning-python**
### **Topics covered**
- **nstalling Python and Pycham**
- **Variables**
- **Creating Variables**
- **Naming Variables**
- **Data Types**
- **Dynamically Type Language**
- **Comments**
- **Strings**
- **Multiline and Formatting Strings**
- **Indentation**
- **Arithmetic Operators**
- **Comparison Operators**
- **Logical Operators**
- **If Statements**
- **Quick Word**
-  
  

## Installing Python and IDE steps 

### Installing Python 

Download link for **Python**!

https://www.python.org/downloads/

- [1] Select the one that apply to your **operating system**. ie, **Windows**, **Mac**, and **Linux**.
- [2] Select the latest version.
- [4] Click downloads folder.
- [4] In the **download folder** and double click the file to start the installation.
- [5] After, followed the default settings by clicking next till finished.

### Installing IDE

- There are various IDE you can used but you will have to **install additional Python plugins**.
- Pycham is the best one I would recommened because there is **no additional plugins needed**.

Download link for **Pycham**!

https://www.jetbrains.com/pycharm/download/download-thanks.html?platform=macM1&code=PCC

- [1] Select the one that applies to your operating system. ie, **Windows**, **Mac**, and **Linux**.
- [2] Select the free **Community Version** not the **Professional version**.
- [3] Click downloads folder.
- [4] In the **download folder** and double click the file to start the installation.
- [5] Just follow the default settings by clicking next till finished.

### **Variables**

**Variable**: A variable is a storage location in a computer's memory where a value can be **store**, **retrieved**, and **manipulated** during the execution of a program.

### Examples of **Variables**

<img width="1108" alt="Screenshot 2024-05-03 at 12 42 54 AM" src="https://github.com/awkamara/Learning-python/assets/145500282/c074e248-afad-41f1-9b30-dce69fee4c6e">

###**Naming Variables**

These are the naming conventions that would work.

- **name = "James"**
- **fullName = "J James" or full_name = "J James"**

### **Data Type**
- A **data type** represents a kind of value and determines what operations can be done on it. **Numeric, non-numeric and Boolean (true/false)** data are the most obvious.

  ***EXAMPLE**
  ```
  brand = "Azaria"
  age = 1
  pi = 3.14
  numbers = []
  isAdult = True
    
  print(type(brand))
  print(type(age))
  print(type(pi))
  print(type(numbers))
  print(type((isAdult))
  
  **Execution output**:
  <class 'str'>
  <class 'int'>
  <class 'float'>
  <class 'list'>
  <class 'bool'>
  ```

### **Dynamically Type Language**
- **Dynamic Type** which means that variable types are determined and checked at runtime rather than during compilation.

  **EXAMPLE**
  ```
  x = 10
  y = "hello"
  z = 3.14

  print(type(x))
  print(type(y))
  print(type(z))

  **Execution output**:
  <class 'int'>
  <class 'str'>
  <class 'float'>
  ```
### **Comments**
- **Comments**: can be used to make the code more readable and explain/documenting your **Python Code**. There two ways to make comments ("""comments""" or # comment)

  <img width="1093" alt="Screenshot 2024-05-06 at 12 36 30 AM" src="https://github.com/awkamara/my-python-app/assets/145500282/f93296f2-eb6a-4ab2-95e9-3fa14105cec1">

### **Strings**
- **Strings**: is a sequence of characters enclosed in either single quotes ('') or a double quotes ("")

  <img width="1115" alt="Screenshot 2024-05-22 at 11 37 08 AM" src="https://github.com/awkamara/my-python-app/assets/145500282/abad3a88-a59c-4e2b-b365-251188cd0929">

### **Multiline and Formatting Strings**
- **Multiline and Formatting Strings**: triple quotes (""" comment """) can be used to create a multiline string. It allows you to format text over many lines and include line breaks. Put two triple quotes around the multiline Python string, one at the start and one at the end to define it.

  <img width="1114" alt="Screenshot 2024-05-22 at 11 48 05 AM" src="https://github.com/awkamara/my-python-app/assets/145500282/3cc7b818-2c0a-4d7f-9d24-e71e465572ef">
  
### **Indentation**
- **Indentation**:Python uses indentation to define code blocks, which are groups of statements that are executed together.
  ```
  # indentation
  def myFunction():
      name = "Afonti"
      surname = "Kama"
  ```
  **Keywords**
  ```
  'False', 'None', 'True', 'and', 'as', 'assert', 'async', 'await', 'break', 'class', 'continue', 'def', 'del',
  'elif', 'else', 'except', 'finally', 'for','from', 'global', 'if', 'import', 'in', 'is', 'lambda',
   'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield'
  ```
  

### **Dictionary**
- Dictionary allows you to store data values in keys: called value keys pairs. Every key value should be unique otherwise will be a conflict.

  **EXAMPLE**
  ```
  person = {
    "name": "Azaria",
    "age": 1,
    "address": "USA"
  }
  print(person["name"])
  print(person["age"])
  print(person["address"])

  results:
  Azaria
  1
  USA
  ```
