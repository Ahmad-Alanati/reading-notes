# Class 03 reading

## why this topic matters?

in these topics you will learn about files and exceptions, every programmer will one day have to deal with files in his project so learning about how to read the file and write on a file will help you save data edit data, and about the exceptions, it will help him/her to handle error in his/her program.

## reading Questions
1. What is the purpose of the ‘with’ statement when opening a file in Python, and how does it help manage resources while reading and writing files?

with is one of the context managers and it helps the programmer not forget the closing of the file it lets you use the file inside its block so easy to read too

it helps manage resources while reading and writing the files by closing the file when it finishes or exceptions that makes the resources that were held by the file opening to be released.

2. Explain the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python. Provide examples of when to use each method.

the method read() is used to read the whole file unlike the readline() method which returns just the first line after and if you read before with readline it will continue from where it left off.

ex for read(): you can use it to read an image file so you get the data from the image.

ex for readline(): when you can a txt file with multiple lines of text.

3. Briefly describe the concept of exception handling in Python. How can the ‘try’, ‘except’, and ‘finally’ blocks be used to handle exceptions and ensure proper execution of code? Provide a simple example.

exception handling is a way to handle errors when they occur so our program doesn't crash.

when the Python interpreter enters a line of code with a try it will run the block if it faces an error it will run to the except block and after finishing either of them it will run the finally block of code.

ex:

    try:
        #try code
    except:
        #except code
    finally:
        #finally code

## Things I want to know more about