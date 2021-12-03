# opject-orianted-programming
* we have 2 manner to do a programe
  * procedural code
  * oop manner
### procedural code
the program is written as a long series of operations to execute. some of that might be organized into named functions to make the code modular and maintainable  
but the end goal is really just to get from Point A to Point B to complete some task. It's a straight forward approach  
the thing is like a sequence of steps you need to follow to bake a cake (the same approach)  
Mix the ingredients together, pour them into a cake pan, and put it in the oven.  
### oop  
rather than describing a sequence of steps, I'll describe each of the objects in my kitchen, 
* the pan, 
* the oven, 
* and the mixer, 
* and what each one can do. 
So, instead of writing a single large program, my object oriented code is split apart into several self contained objects. Almost like several mini programs where each object contains its own data and logic to describe how it behaves and interacts with other objects.  
*One of the main advantages of using an object oriented approach is code re-usability.*  
**logic programming languages, like Prolog. Or functional programming languages, like Haskell.**
### what's an object in a computer program  
the object is a noun may be mug or person or bank account  
but, the verb is a behavior of the object  
Every object has characteristics, inherent properties that describe its current state.  
*Attributes or properties, characteristics, states, variables, those are all related terms*  
being an object has nothing to do with complexity. And it's possible for one object to contain other objects.    
**three things that describe objects in an object-oriented programming language.**  
- Identity, 
- attributes, 
- behaviors.   
**Every object in a computer program is self-contained so it has its own identity separate from other objects, its own attributes to describe its current state and its own behaviors, the things it can do**  
the idea of an object extends further to describe non-tangible things too. Like a date, a timer, or a bank account.  
### class is the detailed description,
the definition, or the template of what an object will be. but it isn't the object itself. Classes are like our collection of cookie cutters.  
the class always comes first. You can't make round cookies without the circular cutter.  
 **there are three components that make up a class**
* name,(type)
* attributes to describe that object,(properties, data)
* behaviors, the things that object can do,(operations)  
___
*write those behaviors as code, they're typically called a method.* 
- A method is a block of code or procedure that can be called to perform some action, and it may return a value. ( methods basically function with the key difference that methods are defined as part of a class.)  
- methods are included in any object in that class. And, since methods exist as part of an object, **they can only access data that is known to that object.**  
example of a class   

|class name|cookie 1|cookie 2|
|----------|--------|--------|
|weight   |16g|         12g  |   
|color     |blue    |   red  |
|decorate()|decorate()|decorate()|  
___
* After defining the class, I can create objects based on it through a process called **instantiation**.  
* it's called that because each object I create is an instance of that particular class.   
* each object has its own identity, independent from other objects. Its own data.  
* object-oriented languages come with a collection of predefined classes. So you can start creating objects right away. Basic useful things like strings, dates, and arrays are often included as provided classes, so you don't have to begin each program by defining the same common classes over and over again.  
___
These classes are defined and then gathered together into frameworks or libraries.  
In Java, you have the Java Class Library, .NET Framework for C# and VB.net, C++ has the C++ Standard Library, Ruby also calls its default library The Standard Library, as does Python.
___
## the oop is built on 4 ideas which are 
* abstraction
* polymorphism
* inheritance
* encapsulation
### abstraction
that filter the class from any other attributes that may be added like when I say the person I empty the person from being eaten or anything not related to him
### encapsulation 
we stack the object's data along with methods that operate on that data within the same class to restrict any access to someone or some other object's content to modify on my data that's called "black boxing" so, you have to follow my method to get this content, this closing off to the inner working of the object and only expose specific input and output that reduce dependency between different objects in the system 
### inheritance
used to make a superclass or (parent or base) class that have attributes I need it to inherit it all to subclasses or (child or derived)classes by writing in the child  "everything in parent-class-name"
### polymorphism 
means having multiple forms, the first type of polymorphism
- dynamic (run-time) polymorphism
allow us to access methods (using the same interface) that are used in different types of objects and implement that method in different ways
the benefit is to use any form of the object as long as it has the method that is used in the base object and take the same input and return the same output
the method is overriding in the second object 
- static (compile-time) polymorphism
uses overloading method that allows us to implement multiple methods within a class that have the same name but its difference in the set of input parameter
the class will automatically execute the appropriate method depending on what you giving
___
### object-oriented has three fundamental steps to work
- understand the problem (analyze) 
- plan your solution (design)
- build it (programming)
UML standardized notation for diagrams to visualize object oriented systems
Use case diagram: describe users interaction with the program  
### the approach in 5 methedology 
- gather requirements : what is app need to do , flesh out the problem
- describe the application : build a story in a plain lang for how people will use it
- identify the main objects 
- describe the inter actions : between the objects , understanding each object responsiplity
- create a class diagram
___
### gather requirement
- figure out what your app need to do 
- what is the problem are you trying to solve 
- why are you building the app in the first palce 
1- Functional requirement  (what must to do)
what are the nesseary feature and capapility  (functional features) example: 
the system must do
- contain music library 
- allow users to pick an album
- then select an individual song from that album
- prevent them from playing full album  
(have a button that allow users to click to sort by artist ) is not a good way to express instead : jukebox on spaceship
- allow users to sort by artist
- identify individual user
- track number of play per user   
2- Non-functional requirement (how should it do it) : descibe required charachtaristic of app rather than features example: jukebox on spaceship
- useability: intuitive to use while floating in the space
- reliability: 24/7 availiable
- performance: low-power to not affect the system
- supportability: updatable to add modern songs 
how should it do it : 
- legal, performance, support, security
system should be has :
- maintainability, reliability, usabiliy, availibity
___
### FURPS is classifing software quality attribute 
*(its checklist of several key quality to consider when determing requirements*
- Functionality: capabilities and feature of the app , reusabiliy and security 
- useability: affects the person who will be using the program, Is it easy on the eyes? Is it intuitive to use? Is the documentation accurate and complete?
- reliability: avilability, failture rate, need to know how much system downtime is acceptable, If the failures are predictable and how the system can be recovered.
- performance: speed, efficiency, dictate the application's response time through put. And they put limits on the system resources it can use.
- supportability:  Make sure the application can be tested, extended, serviced and installed and configured.
### FURPS + : add four more catagory
- Design : addresses constraints on how the software must be built because the app requires certain things such as a relational database.
- Implementation: Does it have to be written in a certain language? Are there standards or methodologies that need to be followed?
- The interface: typically refers not to the user interface but to an external system that needs to be interfaced with.
- physical requirements : Actual physical constraints related to the hardware the application will be deployed on.
___
### use cases
we use it to visualize a proccess by an actor to reach a goal , example
title: short and clear like : play a song
actor: user also could be system entity
success senario: written in a plain language or steps
this for during non error will happen to solve any unpredictable thing and also precaution is extentions and precondition
extention: describe steps for unworking steps in success senario
precondition: before the use case is working , it will ask the actor to do the precondition whatever it is
you can add more things like : postcondition , scope ...
example of use cases to a jukebox  
  
title : play multiple songs
actor : user
success senario : 
* system identify user 
* user browses available albums and songs 
* user select a song 
* system beginning play selected song
* user continues browsing and select a second song 
* system adds second song to play queue 
* system plays second songs after the first one is over
___
### brainstorming for possible actors before writting use case (identifing actors)
* thing in jobtitles and departement
* use stick figures to represent each possible human actor
* ask does the system interact with other computer system or any organization those are also actors
we split the roles of the actors to catagories accoring their needs into primary and secondary actor  
the primary is not the important but the one who initiate the use case  
___
### identifing senario
* we in writting senario describe a goal that an actor can accomplich in a single encounter
* stay focus on user intention , what they really want to accomplish 
* first, focus on success senario and then use extention in very common mistake that may happens 
* use active voice : omit needless words like 
the system is provided with the meal package by astronauts **instead** astronauts inserts meal package  
also no details about system technology and mechanism 
___
### user interface : 
in designing user interface dont focus on use (screen, button, select, click) but focus on intention of user  
use case prompt to expose important actors
* who perfoms system administartion tasks 
* who manage users and security 
* what happens if the system fail
* is anyone looking at performance matrics and logs
___
### diagraming use cases 
![diagraming use cases](https://d3n817fwly711g.cloudfront.net/blog/wp-content/uploads/2015/02/use-case-diagram-relationships-include.png)
___
### user stories 
describe a single small senario from user prespective focusly on their goal, the format is:  
as a (type of user), i want (goal), so that (reason) example:  
as an astronaut , i want to heat up a meal , so that i can eat a warm food **or**  
as a user , i want my song to be added in the front of a long play queue , so that i dont have to wait hours to hear it   
the difference between use case and user stories
![difference between use case and user stories](https://assets.justinmind.com/wp-content/uploads/2020/10/user-stories-vs-use-cases-benefits.png)
___
### identifing objects 
when analyse is done so, we go into conceptual model : represent important abject and the relationship between them  
how we know the object, through all nouns in requirements , use case and , user stories then we filter it and remove the duplicates and the one which is part of other  

![identifing objects  ](https://media.cheggcdn.com/media/703/703b201b-0f24-48fa-8ee4-c8f78e24f48e/phplSpbWg)
### identifing class relationships 
![identifing class relationships ](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQT_pdhqnwedrCce18BqLV5dmEvcKYOMfET3g&usqp=CAU)
### identifing class responsibilities 
how we know the class responsibilities, through all verbs in requirements, use case and, user stories then we put the verb on the his object 
*each object should be responsible for it itself*
![identifing class relationships ](https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/247641904_1048738549272615_1643890656934615772_n.jpg?_nc_cat=102&ccb=1-5&_nc_sid=730e14&_nc_eui2=AeFjsNHbYd93BaUwHIGsE4fmnzqylmeexuufOrKWZ57G60FgOoyHACq6FSV2qHKnC8U9mhqYwcNmBnwavC8ytV-K&_nc_ohc=UkLDq7sjnmMAX93GA4c&_nc_ht=scontent.fcai20-5.fna&oh=ae413d0422133c1c41c6c3d89f5f2411&oe=6197E827)
___
### CRC card is 
class, responsibility, collaboration 
![identifing class relationships ](https://univertis.com/wp-content/uploads/2019/01/oop_crc.png)
___ 
### class diagram
the encapsulation principle implement through "-" minus sign if it has - sign its not accessible by other objects 
![class diagram ](https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/248061141_921502485121782_8721004604835230591_n.jpg?_nc_cat=101&ccb=1-5&_nc_sid=730e14&_nc_ohc=dV8hnQ5K7dQAX-RClbl&_nc_ht=scontent.fcai20-5.fna&oh=4f0f47a0c4fb64cbe68e9948c27abb48&oe=6198DBB8)
___
### instantiation 
through new in code , when we use instantiation the computer in background specify a section of memory to hold the new object including space for variable in it
![class diagram ](https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/248968984_921503355121695_4052042524593544554_n.jpg?_nc_cat=103&ccb=1-5&_nc_sid=730e14&_nc_ohc=oPhD8hg3ahUAX98CUiU&_nc_ht=scontent.fcai20-5.fna&oh=86eed86b43921fec556917a9cf61fc83&oe=6199040C)
### instance variables
variable for which each instantition object of a class has a separete copy (doesnt affect other object)
___
### notes
- class name is singular 
- make attributes and behavior private as possible
- the initial focus in class creation is behavior , your focus should really be on what object do rather than viewing them as data structure
- if you find your class is devoid of any resposibility review conceptual models and crc cards
### constructor
its a special method that gets called to create object like this 
![class diagram ](https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/248975347_921505131788184_4337047309839591743_n.jpg?_nc_cat=104&ccb=1-5&_nc_sid=730e14&_nc_ohc=0oKzmKsMAbEAX_U7cxV&tn=TczB4nrqjaDgEJwZ&_nc_ht=scontent.fcai20-5.fna&oh=4f8c3b7bf2a0df0816480418668a4199&oe=619B10C0)
#### overloading constructor 
for a specific object to call then we use multiple constructor
![class diagram ](https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/248061142_921507195121311_3476095370511594139_n.jpg?_nc_cat=103&ccb=1-5&_nc_sid=730e14&_nc_ohc=omlHpWuAEs4AX-jbRWW&_nc_ht=scontent.fcai20-5.fna&oh=7b633fc1b0f0b2d703499c8953cb2fff&oe=619AD3AB)
#### destructor or finalizer
- a special method that get called when object is destroyed 
- is the place to put some code that will automatically be called when the object is destroyed
___
### static varible or class variable
is a variable that is shared across all object in a class 
![class diagram ](https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/248072452_921512011787496_8515414543701869728_n.jpg?_nc_cat=104&ccb=1-5&_nc_sid=730e14&_nc_ohc=zTe5pBiv3igAX__YUBB&_nc_ht=scontent.fcai20-5.fna&oh=70fd94164ab8329a02473f0d0700d975&oe=6199F93E)
___
### inheritance 
we usually use "is a" or "kind of" to recognize the relation between parent and child classes

[<img src="https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/248501437_921515745120456_975799649942595287_n.jpg?_nc_cat=109&ccb=1-5&_nc_sid=730e14&_nc_ohc=7mQ-CO30DlsAX-2yjO0&tn=TczB4nrqjaDgEJwZ&_nc_ht=scontent.fcai20-5.fna&oh=31248554789be66a9edb0f564c6ebaeb&oe=619B1462" width="450"/>](https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/248501437_921515745120456_975799649942595287_n.jpg?_nc_cat=109&ccb=1-5&_nc_sid=730e14&_nc_ohc=7mQ-CO30DlsAX-2yjO0&tn=TczB4nrqjaDgEJwZ&_nc_ht=scontent.fcai20-5.fna&oh=31248554789be66a9edb0f564c6ebaeb&oe=619B1462)
#### overriding
allowing subclass to replace the implementation of a method from the superclass

[<img src="https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/248770039_921515178453846_4322576902453661329_n.jpg?_nc_cat=108&ccb=1-5&_nc_sid=730e14&_nc_ohc=WnwTRJOkj8QAX9f24Wx&_nc_ht=scontent.fcai20-5.fna&oh=ba001fb87a18788c9f4a97497df95dde&oe=61993FEC" width="450"/>](https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/248770039_921515178453846_4322576902453661329_n.jpg?_nc_cat=108&ccb=1-5&_nc_sid=730e14&_nc_ohc=WnwTRJOkj8QAX9f24Wx&_nc_ht=scontent.fcai20-5.fna&oh=ba001fb87a18788c9f4a97497df95dde&oe=61993FEC)

#### inheritance in code 
[<img src="https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/248177406_921515355120495_8449223314889244530_n.jpg?_nc_cat=109&ccb=1-5&_nc_sid=730e14&_nc_ohc=GFNhjs1VT78AX_G47wk&_nc_ht=scontent.fcai20-5.fna&oh=44954e3e8c514525ce6c6642b42773ef&oe=619B5E41" width="450"/>](https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/248177406_921515355120495_8449223314889244530_n.jpg?_nc_cat=109&ccb=1-5&_nc_sid=730e14&_nc_ohc=GFNhjs1VT78AX_G47wk&_nc_ht=scontent.fcai20-5.fna&oh=44954e3e8c514525ce6c6642b42773ef&oe=619B5E41)
#### calling method in super class
[<img src="https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/248920393_921523188453045_5330540200628103960_n.jpg?_nc_cat=105&ccb=1-5&_nc_sid=730e14&_nc_ohc=5xIL13ONVzUAX9ZtgzA&_nc_ht=scontent.fcai20-5.fna&oh=6bd201c83b7da2ce96ee81d15544a156&oe=619A7CEC" width="450"/>]
___
#### abstract class
it cant be intantiate it exist in other class for inheritance
#### concrete class or final class
is the opposite it can be instantiate and cant inherit or extend 
___
### interface 
- list of method for a class to implement and it doesnt contain any actual behavior
- programming structure that declares a set of methods for a class to implement but the interface itself doesnt contain any functionality , there is no implemented code or behavior its a colliction of method signatures a service
[<img src="https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/248279648_921523878452976_3817587267760450145_n.jpg?_nc_cat=108&ccb=1-5&_nc_sid=730e14&_nc_ohc=efN4HSM44QwAX9I0f0E&_nc_ht=scontent.fcai20-5.fna&oh=32dae20af1ccaa9522476293910057df&oe=619B8799" width="450"/>]
#### difference between interface and class
[<img src="https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/248422129_921527601785937_7081646503373446704_n.jpg?_nc_cat=102&ccb=1-5&_nc_sid=730e14&_nc_ohc=XdiKio9vMPkAX9hXowI&_nc_ht=scontent.fcai20-5.fna&oh=0994cd057302e1a3fdd9b89aecf49f90&oe=6199C5ED" width="450"/>]
___
### aggregation 
is another relation between classes but differ from inheritance to recognize it we ask "has a" instead of "is a" it might be better to use "uses a or uses many"
for in condition the aggregation class is destroyed so the related class dont affect (a fleet uses many spaceships)
### composition
implies ownership and use "owns a" to recognize (aspaceship owns an engine)
*the difference between aggregation and composition*
if a part is destroyed in aggregation the other classes dont affect but in composition it affects
___
### object orianted languages properties
[<img src="https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/248268027_921531888452175_4496498059630631732_n.jpg?_nc_cat=101&ccb=1-5&_nc_sid=730e14&_nc_ohc=zj9IdI30HQEAX_rFE57&_nc_ht=scontent.fcai20-5.fna&oh=db2f80589aa66f2a6808dd1081254dcf&oe=619A873B" width="450"/>]
#### things to consider 
[<img src="https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/248543793_921532191785478_7241590549737601657_n.jpg?_nc_cat=100&ccb=1-5&_nc_sid=730e14&_nc_ohc=5hOLmB6-GLYAX_QPC3r&_nc_ht=scontent.fcai20-5.fna&oh=48fe6dfe2ada8c4745a99fc2c52eacf0&oe=61994FF7" width="450"/>]
- single responsibility principle : a class should have only a single responsibility
- code smell : any characterisitic in a program's code that possibly indicates a deeper problem
- design pattern : the re-usable form of a solution to a design problem 
#### factory method pattern 
[<img src="https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/247957722_921532528452111_589999904259805061_n.jpg?_nc_cat=104&ccb=1-5&_nc_sid=730e14&_nc_ohc=BDIvUqo3Ux8AX9ct5Z-&_nc_ht=scontent.fcai20-5.fna&oh=9481bf3589c27e17940406b253599d8f&oe=619C3E14" width="450"/>]
#### memento pattern 
[<img src="https://scontent.fcai20-5.fna.fbcdn.net/v/t1.6435-9/p843x403/248415885_921532648452099_7636747492030225208_n.jpg?_nc_cat=102&ccb=1-5&_nc_sid=730e14&_nc_ohc=lDuMDEclv6kAX9IfJwK&_nc_ht=scontent.fcai20-5.fna&oh=1e17f1fbe873ec28da5f3ddeaf8f91cf&oe=619B8509" width="450"/>]







 


