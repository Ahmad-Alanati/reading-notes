# Class 07 reading

## why this topic matters?

## reading Questions

1. Explain the concept of variable scope in Python and describe the difference between local and global scope. Provide an example illustrating the usage of both.

it is an area where the name of you variables, functions and objects are visible (the space where you variables to be accessed by you programe)

there is two type of scope:

* Global scope: in this scope your variables are accessible to all your program.

* Local scope:in this scope you variables are accessible to all funcions and variables in that scope.

### ex:
```python
x = 5
def sum(number):
    y = 10
    return x + y

print(sum(x)) # 15
print(x)# 5
print(y)#error out of scope
```


2. How do the global and nonlocal keywords work in Python, and in what situations might you use them?

by putting the the global and nonlocal keyword before a variable name inside a function by that you defined a list of names that are going to be treated as global/nonlocal name

```python
x = 5
def sum(number):
    global x = 10
    return x + x

print(sum(x)) # 20
print(x)# 10
```

```python
x = 5
def sum(number):
    nonlocal x = 10
    return x + x

print(sum(x)) # 20
print(x)# 10
```

3. In your own words, describe the purpose and importance of Big O notation in the context of algorithm analysis.

with big O notation we can analysis if our algorithm is efficient or not

4. Based on the Rolling Dice Example, explain how you would simulate a dice roll using Python. Describe how you would use code to calculate the probability of rolling a specific number (e.g., the probability of rolling a 6) over a large number of trials.

by making a function that return a random number ex:
```python 
import random

def dice():
    return return random.randint(1, 6)

def probability(number):
    count = 0
    for i in range(100):
        if dice() == number:
            count +=1
    return count/100
```

you can calculate the probability of getting the roll you want.

## Things I want to know more about