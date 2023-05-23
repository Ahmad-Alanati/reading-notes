# Class 09 reading

## why this topic matters?

because using some built-in method instade of writing a function will make you code more readable.

in addtion knowing the ethical issue that come from taking some else work and not crediting them will get you in a lot of problems.

lastly using some build-in module will help you to write your code more easy on you.

## reading Questions

1. What is the purpose of dunder methods in Python? Provide an example of a commonly used dunder method.

the purpose of using special/magic/dunder method is a method that makes the class emulate the behavior of built-in types

one of the dunder method is str 
```python
class Food:
    def __init__(self,name):
        self.name = name

    def __str__(self):
        return f'this {self.food} is good'
```

2. In the video “AI Guru makes $238,800 with misleading paid course,” what was the main ethical issue raised concerning the use of developers’ work, and how might this have been avoided?

the issue is using other people code without crediting them and how to solve that issue is to crediting them properly.

3. Describe the Python statistics module and give an example of a function within the module that can be used to perform a common statistical operation.

the statistics module is a build in module that provide statistics functions for example median,mean,mode,quantiles and more

example on using statistics module:
```python
from statistics import mean

def find_the_mean(list_of_data):
    return mean(list_of_data)

list_of_nums = [1,2,3,4,5,6,7,8,9,10]
print(find_the_mean(list_of_nums))
```

## Things I want to know more about