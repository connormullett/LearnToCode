
# General Setup
This guide will explain how to setup project files
and create a working directory. In this file will
also be notes on how run python files from VS Code


## Getting Started
 - Create a folder called `projects`, or whatever
   you want to name it, and place it on your desktop,
   or whever you want to put it
 - You can organize this however you would like, but
   a good idea is to organize it by creating new
   folders by week, and new folders per challenge.
   It's not a good idea to just have a bunch of files
   in one folder with no structure as eventually we
   will have challenges that will need multiple files,
   or have text files for data


## Starting a Challenge
 - Create a new folder and name it after the challenge
 - Create a file called `main.py` or name it something
   else if you like. As long as it has the file extension
   `.py`, it will be fine.
 - Now you can do your work and complete the challenge


## How to use the Terminal
 - The terminal is where we will be finding and executing
   files. Using it is not hard and a couple of commands will
   be more than enough to get started
 - The terminal we will use is VSCodes integrated terminal
 - To open it press `ctrl+\``
 - There are only two commands we need to know to navigate
   using this terminal
 - `ls` - This will `list` all of the current folders and files
   and programs in the current folder (directory) you are in
 - `cd` - This stands for "change directory". We use this after `ls`
   to change our location in the terminal. To do this, we need to
   append the name of a folder to the command (ie cd foo). This will
   change our directory so that we are inside the foo folder. Then we
   can `ls` again to view the contents in a new folder
 - `cd ..` - This is the exact same command, but instead of a directory
   name, we have a double dot. This means the parent directory. In
   other words, if we use this command, we will go back to the directory
   we were just in. Its like a 4 character back button

### CHALLENGE
 - Try and use the terminal to find your desktop and view its contents



## Running Python Scripts
 - When you are ready to run the script, press `ctrl+\``.
 - Now, we need to make sure we are in the right directory
   Consult the "How to use the terminal" section above
 - Once we see the script in our terminal, we use the command
   `python {filename}.py` where `{filename}.py` is the name of
   the file you are trying to run
 - This will execute the python interpreter on the file you gave
   and execute the program
  
REMEMBER: Python reads the file as its running, top to bottom
This can sometimes lead to issues with execution and create errors

