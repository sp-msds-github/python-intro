# python-intro
uva library workshop on introduction to python

## Who am I?
* [Senior Research Data Scientist with the Data Science Institute and UVA Library](https://dsi.virginia.edu/people/peter-alonzi)
* I like to be interrupted with questions! Please jump right in.

## Welcome to the UVA Library
* [Research Data Services](https://data.library.virginia.edu/)
* [Workshop Series](https://data.library.virginia.edu/training/)
  * Introduction to R (Jenn Huck)	Thursday, 9/6	10:00 – 11:30	Brown 133
  * Introduction to Python (Erich Purpur)	Wednesday, 9/26	10:00 – 11:30	Brown 133
  * Introduction to Git/GitHub (Pete Alonzi)	Tuesday, 10/2	14:00 – 16:00	Brown 133
  
## Getting Python (this will take some time)
* [Windows](https://www.anaconda.com/download/#windows)
* [Mac](https://www.anaconda.com/download/#macos)

* terminology time
  * programming langugage vs software distribution
  * python2 vs python3
  
# Goals for Today
1. Get python running
2. Get comfortable with python
3. Learn how to look up help

## Outline
1. Strings and Functions
2. Data types
3. Loops
4. Logic
5. How to import (aka the most important part)

### A quick note
Today we are working on python. However there is some knowledge of programming that is required. Don't worry if you don't know it, please ask questions. I will do my best to answer them. And I will also do my best to indicate when something is a python specific detail and when it is a programming in general item.

## A brief history
* Designed by [Guido van Rossum](https://www.google.com/search?q=google+image+search+guido+van+rossum&safe=off&rlz=1C5CHFA_enUS690US690&source=lnms&tbm=isch&sa=X&ved=0ahUKEwjE_eGK6KHdAhXrRd8KHUzBDHsQ_AUICigB&biw=1440&bih=697)
* version 1.0 1994
* version 2.0 2000
* version 3.0 2008 (not widely adopted until a few years ago)

# Let's Get to It (hopefully everyone is done installing)
* open spyder [it looks like this](spyder.png)
  * text editor
  * variable explorer
  * console
  * control icons
  
## Strings
* A string is a 'string' of characters
  * 'apple'  # letters
  * 'blue42' # letters and numbers
  * 'i am the very model of a modern major general' # spaces are fine
  * '7 hills' # it can even start with a number
  
## Comments
We also introduce comments here, the computer will ignore everything after the '#' symbol. There are other forms but we'll see them later on.

## Variables
You can "save" things as variables. For those curious as to what's going on under the hood...in python a variable is actually just a pointer to the location in memory where the object lives.
* a = 'apple'
  * a is the variable
  * = is the assignment operator
  * 'apple' (a string) is the object assigned to a
  
* *Important Note*: the assignment operator is not like an equals sign
  * a=5
  * a=7
    * totally works, a was just reassigned to point to 7
    
## Functions
* print(a) # this function will show us what a points to
* we know that print is a function because there is no space between print and the "("
* format of a function: name(arguments)
* we say we "call" a function
* *this is super important* in python the way to spot a function is no space before a "(" and a letter or number
  * [python built-in functions](https://docs.python.org/3/library/functions.html)
  * print(...)
  * type(...)
  * pow(...)
  * in an equation you may see 5*(2+3), you won't seet 5(2+3) (try it and see what happens)
  
## Indexing
* for objects with an order you can access individual elements
* [indexing](indexing.png)
* you can also pull out slices
  * syntax [X:Y]
    * starting at X
    * upto but not including Y



# Import
* *This is the most important topic*
* The import command let's you bring in code from another file and use it
* one example: random number generation
  * import numpy
  * numpy.random.randn()
* There are two steps [info on conda](https://conda.io/docs/user-guide/tasks/manage-pkgs.html) [info on pip](https://pip.pypa.io/en/stable/user_guide/)
  1. install the module, eg: shell]$ conda install numpy
  2. python>>> import numpy

# Scripting vs Programming
It's a matter of modularity. Programs are designed to be modular and work with other programs. Scripts are designed to be single use.



# Ways to Practice
* Beginning
  * Flip a coin (~10 lines)
  * Play rock, paper, scissors  (~25 lines)
* Intermediate
  * Guess a secret number between 1 and 10. With hints. (~20 lines)
  * Dice rolling program
* Expert
  * Play blackjack
  * Play roulette







