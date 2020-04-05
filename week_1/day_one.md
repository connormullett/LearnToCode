
# What you will learn
 - Print statements
   to display information
 - Variables and data types
 - Input statements
   to get information from the user


# Data types and Printing Data
 - Programming is all about data. We have
   characters, numbers, true/false, etc.
 - Python is built around this and makes
   it look like elementary school math
 - We can store these types in things
   called `Variables`
 - A Variable is an identifier (a name)
   that stores a specific value
 - To create a variable, we need to give
   it a name and `assign` it a value
 - The syntax is as follows for a variable
   named `x` with a value of 5
   `x = 5`
 - Now, we can use this variable elsewhere.
   for example, in a print statement, do math
   with it, change the value, etc.
 - to print a value we can use a print statement
 - a print statement is a line of code that has
   the following syntax
   `print(<value to display>)` where you replace
   the \<value...\> with the variable you want to
   print
 - **NOTE**: variable names cannot start with numbers,
   symbols, or have spaces. In python it is recommended
   to use underscores (\_) to separate words if you
   have multiworded variable names such as `my_var`


## Challenge
 - Create a variable called `my_message` with the
   value `'hello world'` and display it with a print
   statement


## When you're done
 - Create a `boolean` (look it up) variable and print
   it just like we did previously


## If you get stuck
 - With the variable
   * look into strings
 - With running the program
   * refer back to the page where I describe how to
     execute code or look online


# Getting Input from our Users
 - Great, now we know how to print data and hopefully
   you played around with some values and made some
   for practice
 - It's great that we can assign variables, but what
   if we want to change things up and have our users
   enter data, such as their age
 - We do this with `input()` statements
 - The syntax for an input statement is as follows
 `\<variable you want to store data to\> = input('\<a prompt to display to the user\>')`
 - Notice how this looks similar to what we had before. The
   only thing different is the right side. This is because
   we don't know the value yet
 - Inside the parenthesis goes what the user will see before
   they enter a value. The user must press enter when done
   for the program to continue. 


## Challenge
 - Use an input statement to ask for the users age,
   then display that number with a print statement


## If you get stuck
 - look back at the last challenge, you can even do this
   in the same file


## Bonus
 - Have the user enter their name, and have the program
   print out a greeting.
 - Example: 
   ```txt
   Enter your name: Connor
   Hello, Connor!
   ```

