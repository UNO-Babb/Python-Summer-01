# Practical Scripting with Python
## UNO Summer Techademy

### Scripting vs. Compiled Languages
#### Compiled Languages
- Written with strict syntax in high-level language
- Converted to machine code by the compiler
  - All lines are evaluated
  - Syntax errors are flagged by compiler
- Compiled program is what actually runs
- Used for major applications
- Source code is not needed for execution

#### Scripting Languages
- Written with strict syntax in high-level language
- Each line is converted to machine code as it runs
  - Syntax errors are not flagged until the individual line is executed
  - Conversion as you go is slower than converting ahead of time
- Easier to begin a program
- Used for automation and simple tasks
- Source code is needed to run

### Getting Started in Repl.it
- Go to [repl.it](https://repl.it/) and create an account.
  - Sign in if you already have an account.
- In the top right pick the **+ new repl**
- Choose **python** as the language
  - You can name it anything, but you might want to remember this is your first program later.

### Our first program
In the ***main.py*** editor (center pane) type each of these commands.
Run the code after typing each to see what it does.
```
print("Hello Python")
print(2 + 3)
print("Hello" + "world")
print("Hello" + 5)
```

## Importing from GitHub
- In the top left of Repl.it, select **+ new repl**
- Change tabs to select **Import From GitHub**
- Paste the following URL into the box:
  - ***github.com/UNO-Babb/Python-Summer-01***



## FirstProgram.py
The instructions for the program is in code. In python, a pound sign (#) is used to denote a comment. This is code that will not execute and is only there for the benefit of the programmer.

Please label all of your work. There is an area at the top of the code for the file name, your name, the purpose of the file, and the last revision date. Please update all of this info.
```
#FirstProgram.py
#Name:
#Date:
#Purpose: To ask a user for their name, and calculate their birth year.
```
- We are going to make a program that that says hello and asks for your name.  
- We have not yet used input, you will need the following code to make it work. Experiment to answer these questions.
  - Do I need a prompt or can I simply get input?
  - How do I use the value the user just gave me?
  - What is the data type of the value the user just gave me?
    - Can it be printed?
    - What happens if it is a number and we try to do math with it?
    - Can I convert data types if this one is not correct for my needs?

```
answer = input("This is a prompt for info: ")
print(answer)
```

## MadLib.py
Create a [Mad Lib](https://en.wikipedia.org/wiki/Mad_Libs) where the user supplies key adjectives, nouns, verbs, adverbs, or other types of speech then constructs a full story with those words.

Your Mad Lib must:
- Ask for at least 6 words
- Consider usability in design (be clear)
- Create a story with the user supplied words.

There are a few ways to join words in python:

```
noun1 = "Bicycle"
print("I like to ride my " + noun1)
print("I like to ride my", noun1)
```
Test which works best for you, note where the spaces fall using the different methods.

Please remember to fill in all of the info at the top of the document.


## Testing your code
You may not actually know that your code works until you fully test what you have written. It is often a good idea to get someone else to run your program, they may do something you had not anticipated which could show you a possible flaw or at least a design issue.
