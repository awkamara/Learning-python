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
- ** 
  

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
  
  **Execution Output**:
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

  **Execution Output**:
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

### **Arithmetic Operators**
- **Arithmetic Operators**: basic arithmetic operators in Python include **addition (+), subtraction (-), multiplication (*), division (/), Modulo (%), floor division (//),** and **exponentiation** ( **).

<img width="1112" alt="Screenshot 2024-05-22 at 1 27 58 PM" src="https://github.com/awkamara/my-python-app/assets/145500282/1a73093e-7e4b-471c-ab03-02535dedb4a0">

### **Comparison Operators**
- **Comparison Operators**: are used to compare different values to each other. The return values of comparison operators are either true or false.
- There are **six operators** and they are

  ```
  1.) == or equal to,    2.) != or not equal to,  3.) > or greater than, 
  4.) >= or greater than or equal to, 5.) < or less than, 6.) <= or less than or equal to.
  ```

  <img width="1114" alt="Screenshot 2024-05-23 at 12 28 46 AM" src="https://github.com/awkamara/my-python-app/assets/145500282/11f06ee4-60b8-4498-a42c-f0e7109bcee8">

### **Logical Operators**
- **Logical Operators**: are used to combine multiple expressions together and evaluate them as a single boolean expression. There are **three types** of **logical operators** in Python: **'and'**, **'or'**, and **'not'**.

  ```
  print((10 > 5) and (1 > 3))
  print(10 < 5 or 1 > 3 or "A" == "A")
  print(not("Abdul" == "James"))
  
  **Executed Output**:
  false
  true
  false
  ```

### **Assignment Operators**
- **Assignment Operators**: are used to assign values to variables. This operator is used to assign the value of the right side of the expression to the left side operand.

  <img width="1112" alt="Screenshot 2024-05-23 at 11 24 55 AM" src="https://github.com/awkamara/my-python-app/assets/145500282/e03cee14-42d6-4099-a52e-9caa116372d0">

### **If Statements**
- **If Statements**: the **if statements** is a conditional statement. It is used to execute a block of code only when a specific **condition** is met.
  ```
  number = -15
  if number >= 0:
        print(f"{number} is positive")
  elif number == 0:
        print(number)
  else:
        print(f"{number} is negative")

  **Executed Output**:
  -15 is negative
  ```

### **Quick Word About If Statements**
- You can only have **one IF and ELSE statement but can have as many ELIF statements

### **Ternary If Statements**
- **Ternary If Statements** operator determines **if** a **condition** expression is true or false and then returns the appropriate value as the result. This should only be used if you have one **IF** and **ELSE** statement.

  ```
  number = 10
  message = "positive" if number > 0 else "0 or negative"
  print(message)

  **Executed Output**
  positive
  ```

<img width="1117" alt="Screenshot 2024-05-23 at 1 43 11 PM" src="https://github.com/awkamara/my-python-app/assets/145500282/f3babae4-f8d4-4208-9e5a-de5dcc822724">

### **Lists**
- **Lists**: is a **flexible, versatile, powerful, and popular built-in data type**. It allows you to create **variable-lenght** and **mutable sequences** of objects. In a list, you can store objects of any type. you can also mix objects of different types within the same list, althought list elements often share the same type.
- The first element on the list [1, 2, 3, 4, 5] is element **zero, one, and so on**.

  <img width="1120" alt="Screenshot 2024-05-23 at 1 55 51 PM" src="https://github.com/awkamara/my-python-app/assets/145500282/6ce59032-c623-4fb7-8b9e-016ff47899f4">


### **List Methods**
- **Useful List Methods**: 

<img width="1125" alt="Screenshot 2024-05-23 at 2 07 43 PM" src="https://github.com/awkamara/my-python-app/assets/145500282/daf501e5-87d5-46a2-9a40-0aa3c427206e">

### **Deleting Items form List**
- The **remove** method removes the first occurance of a specified element from a list. For example, to remove the item "banana" from the list thislist, you would use the following code:
- The **pop** method allows you to start removing/deleting from the top.
- The **del** method allows you to delete/remove items by range.

  **EXAMPLE**
  **Remove the last item**
  ```
  thislist = ["apple", "banana", "cherry"]
  thislist.pop()
  print(thislist)

  **Excution Output**
  ['apple', 'banana']
  ```
  **Remove the first occurance of "banana"**
  ```
  thislist = ["apple", "banana", "cherry", "banana", "kiwi"]
  thislist.remove("banana")
  print(thislist)

  **Excution Output**
  ['apple', 'cherry', 'banana', 'kiwi']
  ```
  **Remove the first item**
  ```
  thislist = ["apple", "banana", "cherry"]
  del thislist[0]
  print(thislist)

  **Excution Output**
  ['banana', 'cherry']
  ```

### **Sets**
- **Sets:** in **python** programming is an unordered collection data type that is iterable, mutable and has no duplicate elements. With **Set* the order is not grantee.
- **No Duplicate**, **Order is not allowed** **The syntax for Sets is different ({}) from List syntax ([]).
 
  **Example**
  numbersList = [1, 1]
  numbersSet = {1, 1}
  lettersSet = {"A", "A", "B", "C", "C"}
  print(numbersList)
  print(numberSet)
  print(lettersSet)
  
  **Excution Output**
  [1, 1]
  {1}
  ```
  
### **Set Union Intersection & Difference**
- **Intersection, Union and difference**: The union between two sets, results in a third set with all the elemments for both sets. The order is not grantee on the result.

  <img width="1149" alt="Screenshot 2024-06-04 at 5 35 27 PM" src="https://github.com/awkamara/my-python-app/assets/145500282/71a1067a-66c4-41f4-a696-a9c9e9c2400e">


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

  **Executed output**:
  Azaria
  1
  USA
  ```

### **For Loops**
- **For Loop**: A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string). 

<img width="1156" alt="Screenshot 2024-06-04 at 5 54 20 PM" src="https://github.com/awkamara/my-python-app/assets/145500282/117849be-a19c-4392-8d95-fe86c5dd3bc8">


### **Loop Through Dictionaries**
- You can loop through a dictionary by using a **for** loop.
- When looping through a dictionary, the return value are the keys of the dictionary, but there are methods to return the values as well.

  **Example**

  <img width="1183" alt="Screenshot 2024-06-06 at 10 36 15 AM" src="https://github.com/awkamara/my-python-app/assets/145500282/655dedf9-7545-4e3a-94cb-17045915c3f3">

### **Exercise**
- numbers = [1, 2, 5, 6, 7, 9] combine these numbers

### **Exercise Solution**
  **Answer**
  ```
  result = 0
  numbers = [1, 2, 5, 6, 7, 9]
  for number in numbers:
      result += number
  
  print(f"Result = {result}")

  **Excution Output**

  Result is 31
  ```

### **While Loop**
- **While Loop**: is used to execute a block of statements repeatedly until a given condition is satisfied. When the condition becomes false, the line immediately after the loop in the program is executed.
   
  **Example**

<img width="1151" alt="Screenshot 2024-06-08 at 12 15 09 AM" src="https://github.com/awkamara/my-python-app/assets/145500282/5061b215-ac9e-4b83-80a2-10d83de8308d">

### **Break and Continue**
- The **Break** statement is used to terminate the loop or statement in which it is present. The **continue** statement skips the current iteration of the loop and the conrol flow of the program goes to the next 
  iteration.

  **Example**
  
  Break
  <img width="1148" alt="Screenshot 2024-06-08 at 2 00 22 AM" src="https://github.com/awkamara/my-python-app/assets/145500282/ce21024e-9ec6-43dc-92cd-44739d87bf2a">

  continue
  ```
  number = 0

  for n in [1,2,3,4,5,6,7]:
      if n == 5:
          break
      print(n)
  
  # while number < 10:
  #  if number == 5:
  #       continue
  #       print("number is 5 hooray")
  #    number += 1
  ```
  ```
  number = 0
  
  while number < 10:
      if number == 5:
   #       print("number is 5 hooray")
      number +=1

  **Executed Output**
  number is 5 hooray
  ```
  
### **Functions**
- **Function**: A **function** is a block of code or statement to perform a specific task, known as parameters, into a function.

  **Example**
  
  <img width="1173" alt="Screenshot 2024-06-09 at 1 16 16 AM" src="https://github.com/awkamara/my-python-app/assets/145500282/c1978a1a-78e3-4d3a-aa25-2b3e30d1ed36">

### **Parameters and Arguments**
- A parameter is the variable listed inside the parentheses in the function definition. An argument is the value that are sent to the function when it is called.
  
  **Example**
<img width="1183" alt="Screenshot 2024-06-09 at 1 40 28 AM" src="https://github.com/awkamara/my-python-app/assets/145500282/0403849d-c17a-45e7-be46-59e3dd31c381">


### **Return Values From Functions**
- 


### **Built in Functions and Import Statement**


### **Creating Modules**


### **Clases and Objects**


### **Creating Classes and Objects**




  
