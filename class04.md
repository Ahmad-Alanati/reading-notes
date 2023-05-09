# Class 04 reading

## why this topic matters?

in these topics you will learn about files and exceptions, every programmer will one day have to deal with files in his project so learning about how to read the file and write on a file will help you save data edit data, and about the exceptions, it will help him/her to handle error in his/her program.

## reading Questions
1. What are the key differences between classes and objects in Python, and how are they used to create and manage instances of a class?

Objects is like a dictionary but it have store function too unlike dictionary that store data

object is created by a template, and that template is class.

as i wrote class is a template so any changes on the class will effect the objects too
for ex: if you create a function on the class all the object that you create from that class will have that function

how to make a class it is simple:

        class Class_Name:
            #variables of the class
            var = 'hello'
            #function of the class
            def Name_Of_The_Function(self):
                #function code
        
        my_Object_Of_Class_Name_01 = Class_Name()

2. Explain the concept of recursion and provide an example of how it can be used to solve a problem in Python. What are some best practices to follow when implementing a recursive function?

revursion is a way to solve problem by chip it into s smaller problems so that problem you have been thinking about for days now have n children and you started solving them.

for example:
you can sum the number from 1 to n with one for loop:

    sum = 0
    for num in range(n)
        sum += num
    print(sum)
you can solve it using revursion:

    def sum(n):
        if n == 1:
            return n
        return sum(n-1) + n

to write a good recursion you much follow this practices:
- Define your base case.
- keep your code simple.


3. What is the purpose of pytest fixtures and code coverage in testing Python code? Explain how they can be used together to improve the quality and maintainability of a project.



## Things I want to know more about