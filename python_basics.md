# Python Assignments



## **Write a program to print your name.**

```
print("ADAKA NAGARJUNA")
```


###  **write a program for a Single line comment and multi-line comments**

```
print("single line comment")                             #single line comment  
print("""This is 
a 
multiline comment in python
which expands to many lines""")                            #Multiline comment
```

### **Define variables for different Data Types int, Boolean, char, float, double and print on the Console.**


```
a=10
b=10.5
c="nagarjuna"
d=True
print(type(a))
print(type(b))
print(type(c))
print(type(d))
```

### **Define the local and Global variables with the same name and print both variables and understand the scope of the variables**

```
def f():
    # local variable
    s = "I love Python"
    print(s)
f()

def f():
    print("Inside Function", s)
 
# Global scope
s = "I love python"
f()
print("Outside Function", s)
```


