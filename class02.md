# Class 02 reading

## why this topic matters?

learning how to deal with stress is a topic every programer must know about because in any job you have to deal with deadlines, your working states and more.

## reading Questions 

1. What are the key principles of Test-Driven Development (TDD) in Python, and how do they contribute to the overall quality of code?   

the key principles for TDD is to make a small feature and test it and getting an error so you can fix then back to coding untill your software is done

the TDD focus on our software design so our software won't run into a problem in the future.

2. Explain the purpose of the if __name__ == '__main__': statement in Python scripts. What are some use cases for including this conditional in your code?

it is used to know if the file we are in right now is the main file or it is been imported in another file so the user don't run the file sepertly:
ex:

    def intro():
        print("hello world")
        
    intro()

second file:

    if __name__ == "__main__":
        intro()
    
    import intro

    intro.intro()
    

3. Describe the concept of recursion in Python.

making a funcion call itself morethen once untill it get to the base case where it will return a value and that value will be used back in the parent function call.

4. What is the difference between Python modules and packages? Explain how to create, import, and use them in your Python programs.

## Things i want to know more about