## PYTHON : FUNCTION, OOP, Unittest, and LIBRARY or MODULATION
-----
In OOP only explains the writing of methods and classes:
1.  **Class** 
2.	**Object Method** 
3.	**Class Method**
4.	**Static Method** </br>

In Library/Modulation only explains multiple libraries such as:
1.  **os** 
2.	**sys** 
3.	**math**
4.	**random**
5.	**datetime** </br>

#### Leggoo….

## Function
-----
A function is a block of code which only runs when it is called. You can pass data, known as parameters, into a function.
A function can return data as a result. </br></br>
Here's how to declare a List : </br>
```
  def nameFunction():
    x = "Hello World"
    return x
``` 
### Using Parameter as Referenced
```
  def nameFunction(param, ....):
    print(param + " as an output")
  
  nameFunction("Hello, here")
``` 
Full Documentation about Function, check our python program above.

## Object-Oriented Programming (OOP)
-----
Object-Oriented Programming (OOP) is a programming paradigm that uses objects and classes in programming. The main concept of OOPs is to bind the data and the functions that work on that together as a single unit so that no other part of the code can access this data. <br><br>
Here's how to declare a Class :
```
  class nameClase:
    #statement 1
    .
    .
    #statement n
```
### Object Method
```
  class calculator:
    def addition(self, num1, num2):
      self.add = self.num1 + self.num2
      return self.add
    
    #find meaning this code in our program.
``` 
### Class Method
```
  class calculator_cm:
    def addition(cls, num1, num2):
      cls.add = num1 + num2
      return cls.add
    
    #find meaning this code in our program.
``` 
### Static Method
```
  class calculator_sm:
    def addition(num1, num2):
      addNum = num1 + num2
      return addNum
    
    #find meaning this code in our program.
``` 
## Unittest
a software testing process that ensures every unit/function of the program is tested.
```
  import unittest
    .
    .
  #find full code in our program.
``` 
## Library Modulation
-----
### txt-File
1. How to Open
```
  ourFile = open('yourfile.txt', r)
``` 
2. How to Read
```
  weWillOpen = ourFile.read()
``` 
3. How to Close
```
  ourFile.close()
```
### os library
```
  import os
    .
    .
  #find full code in our program.
``` 
### sys library
```
  import sys
    .
    .
  #find full code in our program.
``` 
### math Modulation
Python has also a built-in module called math, which extends the list of mathematical functions.
```
  import math
    .
    .
  #find full code in our program.
``` 
### random Modulation
Python has a built-in module that you can use to make random number.
```
  import random
    .
    .
  #find full code in our program.
``` 
### datetime Modulation
Python has a built-in module that you can use to make random number.
```
  import datetime
    .
    .
  #find full code in our program.
``` 

#### FIND OUR FULL DOCUMENTATION ABOVE :)
