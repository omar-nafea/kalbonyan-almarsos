# Beyond the Fundamentals

### collections   
Grouping similar items together 
types 
1- simple -> lists
2- complex -> dictionary
#### list 
is groups pieces of data together in a certain order and assigns the collection a name(this name called variable).
city1 = 'Tokyo'             
city2 = 'Dakar'             
city3 = 'Mumbai'            
city4 = 'Buenos Aires'   -->>
cities = [
    'Tokyo', 
    'Dakar', 
    'Mumbai', 
    'Buenos Aires',
]
##### you can print any of those items by writing its index for list. print(cities[2]) -> mumbai b.counting start with 0
#### dictionary
lets you store related information, but with a ##### label for each item.
California state symbols
state_bird = 'California quail'
state_animal = 'Grizzly bear'
state_flower = 'California poppy'
state_fruit = 'Avocado'  -->>
california_symbols = {
    'bird': 'California quail',
    'animal': 'Grizzly bear',
    'flower': 'California poppy',
    'fruit': 'Avocado',
}
##### A dictionary doesn't use index numbers, but referencing the name of the variable that stores the dictionary value. print(california_symbols[animal]) -> Grizzly bear

In Python,
item in a list can be combine strings, numbers, and boolean
can add or remove items, or you can change the value of an existing item : mutable collections
immutable collections  : cannot change after they're created (tuple) once you create a tuple, you can't change it
(
'avocado',
'15',
'true',
)
C++, require that all values  must be same data type
what's known as a list in Python is called (an array) in JavaScript and C++. Python dictionaries are known variously as (associate arrays)
###  loop :  it repeats the same procedure multiple times until it reaches a specified endpoint.
First, you need to specify the data that's being iterated through.
Second, you need to describe what should happen to the data on each iteration.
Finally, you need to indicate when the loop should stop. 
1- for loop to print the contents of my list
2- in It indicates the set of values that we want to iterate through                       
spices = [
    'salt',
    'pepper',
    'cumin',
    'turmeric',
]
for spice in spices:
    print(spice)
print('No more boring omelettes!')
3- while loop something that needs to happen repeatedly until it's done.
i = 5             | variable
while i <= 100:   | end point
    print(i)
    i += 5        | operation
###  A Python module 
is a Python file that contains code make a module available in my own program through importing
testmodule.py -> def mult(x, y) : print(f'{x} * {y} = {x * y}')
import testmodule
testmodule.mult(10, 5)
#### library: use multiple modules together, so they're distributed and used in a group
#### framework : distributed in larger groupings, set of code is used together but in a specific way.
### Concatenation :  multiple strings are combined into a single string.
value = input('Enter a number: ')
print(value + 'its my favorite num')
Concatenation with mathematical operation you have to define the numbers as integers
value = input('Enter a number: ')
value_int = int(value)
print(value_int * 10)
### change the contents of a string
1- capitalized
text = 'hello'
text.capitalized()
print('text')
###  search for specific characters in a string.
The find and index methods give you a reference to the first occurrence of text you specify,
while the rfind and rindex methods provide the last occurrence.
Getting part of a string value is known as slicing.
note = 'award: Nobel Peace Prize'
string[start:end] from a starting point to ending point      award_text = note[2:5] -> 'ard'
string[start:]    from these start to the end of string       award_text = note[6:] -> "Nobel Peace Prize"
string[:end]      from the begging of string to these end      award_text = note[:5] -> 'award:'
print(award_text)
###  A regular expression (regex)
lets you create a description of a pattern that you want to match, made up of letters, numbers and special characters.
text by enclosing it in slashes. -> \people\
Back slashes mark many patterns in a regular expression.   \d   indicates a digit,   \w   indicates a word character like a letter
dot     indicates any character. 
plus sign     to indicate one or more occurrences of the preceding pattern.
Asterisk      indicates zero or more and question mark     indicates zero or one. 
Creating a regular expression can be a complex task. Fortunately regular expressions are already written for many common patterns,
### style guides
developers create and share documentation of their approaches to code, For Python called PEP 8(https//PEP8.org)
#### pseudocode 
an outline for your program, writing a description of what you're trying to do using plain language.
### Python methods that are specific to input and output.
1- open method.
#### When a file doesn't exist, Python will create it. and use it as a  file to store the output of this program.
Why might you display statements for the user indicating when processing starts and when output is complete?
if you want to let the user know where in the process the program is when a program takes a long time to run
Without feedback to the user, it can be unclear if a program is still working or has already finished.
#### test cases 
are commands or scripts that use the program in a way designed to test a specific scenario.
### oop -> object orianted programming
program divided into units called objects each object has 
1-attibute -> the data it has (properities)
2-behavior -> something object can do
we can use object method to work with properities
create an object by a blueprint known as 
### class
describe the type of attibute and behavior, ' we can use same class to build multiple objects '
#### list is created based on the array class that's build into python 
list inherit method like (count, pop) from list class
string inherit method like (found, capitalize) from string class
#### memory management
write code that decides what's kept in memory and what's thrown away. This process is known as 
#### garbage collection
this is an automated process in which the compiler keeps track of which items in memory are no longer needed and deletes them.
#### multiplethreading 
its executing multiple task at the same time to increase the perfomance , many languages support that 
