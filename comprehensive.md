# Print Statements

```print()``` is the simplest command and shows us output in console
```python
print("Hello World")
```

We can have have various strings in same ```print()```
```python
print("Hello", "Hi", "Namaste")
```

Not just strings we can also include numbers and decimals too
```python
print(10, 20.5, "Hi")
```

# Input Statements and Variables
```python
print("Enter a number: ")
```

```input()``` is used to get input from the user
```python
n=int(input()) # input always gets the data as class 'str'
```

**Note:** You can also type the string directly inside the ```input()``` like this
```python
n = int(input("Enter a number: "))
```

```n``` is variable and is used in mathematical operations
```python
print(n)
print(n+1)
print(n+2)
```

# Variables and Litrals
Name is string (```str```)
```python
print("Enter your name: ")
s = str(input()) 
```

Number is integer (```int```)
```python
print("Enter a number: ")
n = int(input()) 
```

Fractional number is floating number (```float```)
```python
print("Enter a fractional number: ")
f = float(input())
```

Example to use all variables from above
```python
print("Hi", s, "your entered number", n, "and", f)
```

Merging ```input()``` statement with ```print()``` statement like below gives same result
```python
ss = str(input("Enter your name: "))
nn = int(input("Enter a number: "))
ff = float(input("Enter a fractional number: "))
print("Hi",ss,"your entered number",nn,"and",ff)
```

Change of variable mid-code
```python
ff = 52 #here "ff" is variable and "52" in literal 
print("Your ff variable in now changed to",ff)
ff=ff+1
print("Your ff variable in now changed to",ff)
```

Example
```python
r = int(input("Enter the Radius of the Circle: "))
area = 3.14*r*r
#here '3.14' is literal and 'r' is variable as '3.14' remains same for all iterations whereas 'r' changes
print("Area of the Entered Circle is", area)
```

# Data Types
```python
n=10 #it is an integer
print(n)

f = 6.3 #it is a decimal number
print(f)

s = "IITMOD" #it is a string 
print(s)
```

```type(x)``` tells class of ```x```
```python
print(type(n))

print("n is of type:",type(n))
print("f is of type:",type(f)) #float is a floating number i.e. Number other than interger
print("s is of type:",type(s))
```

```python
l = [10,20,30]
print(l) #displays all l
print(l[0]) #displays 1st element of l
print(l[1]) #displays 2nd element of l
print(l[2]) #displays 3rd element of l
#Note: Computer starts counting from 0
```

```l``` is of class ```list```
```python
print(type(l))
print(type(l[1])) #l[1] is of class 'int'
```

# Operators and Expressions
```python
n = 3*2
print(n) #prints '6'

a = 1
b = 2
c = a+b
print(c) #prints '3'

d = "NIAMT"
e = "Ranchi"

f = d*e #does not exist as sritng can not be multiplied
#Displays error "TypeError: can't multiply sequence by non-int of type 'str'"

g = d+e
print(g) #prints 'NIAMTRanchi'. This is called concatenation of str


k=10+13*2
print(k) #prints '36'. It is due to "operator precedence" i.e. it follows BODMAS.

l = 14
m = 7
o = l/m
print(o) #o is float inspite l and m being int & exactly divisible
```
# Operators and Expressions continued

Arithimetic Operators ```(+, -, *, /, //, %, **)```
```python
a = 3
b = 2

print("Addition", a + b) #result = 5
print("Substraction", a - b) #result = 1
print("Multiplication", a * b) #result = 6
print("Division", a / b) #result = 1.5

print("Floor Division", a // b) #result = 1
#gives int(a/b) i.e. Quotient

print("Modulus", a % b) #result = 1
#gives the reminder

print("Exponential", a ** b) #result = 9
# gives the value of a power b.  i.e a^b
```

Relational Operators ```(>, <, >=, <=, ==, !=)```

*Relational operators always give ```bool``` value*
```python
print("Greater than", 5 > 10) #result = False
print("Greater than", 10 > 5) #result = True

print("Lesser than", 5 < 10) #result = True
print("Lesser than", 10 < 5) #result = False

print("Greater than", 5 > 5) #result = False
print("Greater than or Equal to", 5 >= 5) #result = True
print("Greater than or Equal to", 10 >= 5) #result = True

print("Lesser than", 5 < 5) #result = False
print("Lesser than or Equal to", 5 <= 5) #result = True
print("Lesser than or Equal to", 5 <= 10) #result = True

print("Equal to", 5 == 5) #result = True
print("Equal to", 5 ==50) #result = False

print("Not equal to", 5 != 5) #result = False
print("Not equal to", 5 != 50) #result = True
```

Logical Operatiors ```(and, or, not)```


```and``` = ' * ' ```(1*1=1, 1*0=0, 0*1=0, 0*0=0)```

```python
print(True and True) #result = True
print(True and False) #result = False
print(False and True) #result = False
print(False and False) #result = False
```

```or``` = ' + ' ```(1+1=1, 1+0=1, 0+1=1, 0+0=0)```
```python
print(True or True) #result = True
print(True or False) #result = True
print(False or True) #result = True
print(False or False) #result = False
```

```not``` = inverse
```python
print(not(True)) #result = False
print(not False) #result = True #the '()' is not mandatory
```

```str``` comparison
```python
print(s == "Good") #Result = True
print(s =="good") #Result = False

print('apple' > 'one') #Result = False
print('four' < 'ten') #Result = True
#Here computer compares strings letter by letter
# It takes the 0th letter of 'apple' and 0th letter of 'one' i.e. 'a' and 'o' and compares then in alphabetical order.
# As 'a' come before 'o' in the order 'apple' is lesser than 'one' in string comparison
#Similarlly as 'f' come before 't', 'four' is lesser than 'ten' 

print("applea" > "appleb") #Result = False
#it compares all charecters if starting chatecters are same

print("abcde" > "abcdef") #Result = False
#After abcde, computer compares 'f' with 'None' and as f can't be less than 'None' value comes as false
```
