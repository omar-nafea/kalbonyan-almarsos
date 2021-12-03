# summary for recalling

### Programming

 Programming : is the process of converting ideas into instructions that a computer can understand and execute. These instructions are specific and sequential.
 a bug : is when something unexpected happens
 a crash : is when your program stops early or freezes

### translate source code into machine code

1-compile it (C, C++, and Objective-C)
2-interpret it (PHP and JavaScript)
3-combination of both (Java, C# and Python)

### statements

1-keywords 
2-expressions (2+3)-> input (1,2) + operators (+,-,*,/)
Alan Perlis, who said, "There are two ways to write error free programs, "only the third one works."

### error categories

1-Syntax -> print(hello world) >>> print("hello world")
2-Runtime -> 10 * (2/0)
3-semantic -> name = "alice"         
              print("hello name")     >>>   print("hello" , name)

### the variable is a container for a value

the computer gives us space in its memory where we can put data (variable) that we want to use as a reference for later.
assigning the value : is giving them a name and then setting their value , assignment operator, which is the equals sign
the value for this variable is different (integer,string,boolean)

#### rules that we have to follow when working with variables in Python

1- variable names should contain only letters, numbers, and underscores.(name shouldn't start with a number)
2- spaces are not allowed in the name.  ( _ ) replace by underscore
3- Capital C Cookies is not the same as lowercase c cookies.
4- variables cannot be keywords. 
(False - await	- else	- import -	pass - None	- break	 - except	 - in	 - raise - True	- class	- finally	- is - return - and	- continue	- for	- lambda	- try - as	- def	 - from	nonlocal - while - assert - del - global - 	not	- with - async - elif - if - or - 	yield)

### integer operator 

1- power (**) >> 2 ** 3
2- quotient (//) >> 15 // 7
3- reminder (%) >> 14 % 6 
4- no comma in numbers
5- float is a decimal num

### string is 

(letters , numbers , symbols , space ) between( " " ) or ( ' ' ) but (' it's good ' ) is wrong 

### Boolean expressions result is ( true or false ) consists of

Relational operators work with two operands, and they return a value, true or false 
equality operator -> == 
```python
4 == 2*2 
 true  
5 == 8/4  
false
name = " kal " 
name == " martin "  
false
# not equal sign -> != 
```
- greater and smaller than involved > <
- greateror equal and smalleror equal than involved >= , <=

### if statement  

if (condition)(:)<- this colon is part of if statement
do an action 
true -> do this action
false -> do not do this action

### if-else statement in python

if (condition) :
do an action 
else : <- if the condition doesnt occur then do the else action 
do an another action 

#### if-else statement in java and Ruby

```java                             
if (5>6) {                      
system.out.println("nope")      
}                               
else{                           
system.out.println("yep")       
}
```
```Ruby
if 5>6
puts "nope"
else 
puts "yep"
end
```
### functions

A function : is a block of code packaged together with a name. 
function like def 
1- create the fuction with a name
2- call his name it to do there instructions
```python
define fun 
#  his name
def say_hello()  
# instruction
    print("hello world")
# call it by his name
say hello()   
```
#### parameter

is  to change the function behavior based on some input.
def fun_name(parameter)
    instruction
fun_call (argument)
```python
def wash_car(amount_paid):

    if (amount_paid == 12):
        print("Wash with tri-color foam")
        print("Rinse twice")
        print("Dry with large blow dryer")

    if (amount_paid == 6):
        print("Wash with white foam")
        print("Rinse once")
        print("Air dry") 

wash_car(6) 
```
####  A return statement

consists of the return keyword and the value that the function should return.
return my_value
using return when a fun get me an output and i need it in other fun
```python
def withdraw_money(current_balance, amount):
    if (current_balance >= amount):
        current_balance = current_balance - amount
balance = withdraw_money(100, 80)


if (balance <= 50) :
    print("We need to make a deposit")
else :
    print("Nothing to see here!")
```

* list
    * gdf;ljg
    sdflhdgh
*  s

```python
"""
 print("hello world") 
"""
dfsd

```
