# Simulating a human using Basic Python

##### This page contains most of the examples taken out in the session. For more "comprehensive" notes go to the bottom of this page.

A just born baby
```python
print('crys')
```
A baby after a couple of months
```python
hear = input('What is he saying?')
print(hear)
```
The child in kindergarden
```python
words = "Apple" #strings
numbers = 10 #integers
unknown = '10'
decimals = 3.45 #float

print(type('10'))
```
Boolean Data Types
```python
right = True
wrong = False

print(type(True))
```
Forcing the child to change the datatype
```python
unknown = "10"
print(int(unknown))
print(float(unknown))
print(str(unknown))
print(bool(unknown))
```
```
DIY

Make any 4 values of different datatypes (str,int,float,bool)
and try to convert it into the other 3 datatypes
```
The Child in primary school
```python
# Kid starts getting home work

didHW = "Manage kar le"

if didHW == True:
  print("I did my home work.")
elif didHW == False:
  print("I did not do my home work.")
else:
  print("I did it mam but forgot my book at home.")
```
Guest at home
```python
for number in range(10):
  print(number)
```
```python
for number in range(1,11):
  print(number)
```
```python
for number in range(11,1,-1):
  print(number)
```
```python
name = 'Abhishek'

for letter in name:
  print(letter)
```
Mathematics
```python
num1 = 6
num2 = 2

#addition
addition = num1 + num2
print('When to add them you get', addition)

#subtraction
subtraction = num1 - num2
print('When you subtract you get', subtraction)

#MULTIPLICATION
multiplication = num1 * num2
print('When you multiply you get', multiplication)

#division
division = num1 / num2
print('When you divide you get', division)

quotient = num1//num2
print("The quotient is", quotient)
reminder = num1%num2
print("The reminder is", reminder)
```
Making friends
```python
friend1 = 'Uday'
friend2 = 'Manish'
friend3 = 'Murali'

print(friend1, friend2, friend3)

friends = ['Uday','Manish','Murali', 'Dinesh', 'Ramesh', 'Suresh', 'Mukesh', 'Rakesh']
print(friends)

for friend in friends:
  print(friend)

print(len(friends))

print(friends[0]) #brings out the 0th indexing value from the list of friends

friends.append('Ram')
```

You reached this far. If you are intrested on learning more [***Click Here***](comprehensive)

ps. It might be bit hard to follow on just keep practicing youself on random stuff and you will get better.

few places to practice stuff
[HackerRank](https://www.hackerrank.com/access-account/) | [CodeChef](https://www.codechef.com/login)
