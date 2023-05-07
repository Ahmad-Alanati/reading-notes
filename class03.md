# Class 03 reading

## why this topic matters?

in these topic you will learn about files and exceptions, every progammer will one day have to deal with files in his project so learning about how to read the file and write on a file will help you save data edit data, and about the exceptions it will help him/her to handle error in his/her program.

## reading Questions 

1. What is the purpose of the ‘with’ statement when opening a file in Python, and how does it help manage resources while reading and writing files?

with is one of the context managers and it help the programmer to not forget the closing of the file and it let's you use the file inside it's block so easy to read too

about it help manage resources while reading and writing the files by closing the file when it finish or exceptions that makes the resources that was hold by the file opening to be released. 

2. Explain the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python. Provide examples of when to use each method.

the method read() is use to read the whole file unlike the readline() method it retruns just the first line after and if you read before with readline it will continue from where it left of.

ex for read(): you can use it to read an image file so you get the data from the image.

ex for readline(): when you can a txt file with multiple line of text.


3. Briefly describe the concept of exception handling in Python. How can the ‘try’, ‘except’, and ‘finally’ blocks be used to handle exceptions and ensure proper execution of code? Provide a simple example.

exception handling is a way to handl error when it occur so our program dosen't crash.

when the python interpeter enter a line of code with try it will run the block if it face an error it will run to the except block and after finishing either of them it will run the finally block of code.

ex:

        try:
            #try code
        except:
            #except code
        finally:
            #finally code

## Things i want to know more about