---
layout: post
title:      "Intro to Variables and Classes"
date:       2019-08-21 22:23:42 -0400
permalink:  intro_to_variables_and_classes
---



This blog will illustrate the differences between Instance vs. Class Variables, Instance vs. Class Methods, as well as the 

use of Attribute Accessors as part of the Object-Oriented Programming language, Ruby. In Ruby, everything is an object 

and therefore methods can be attached and executed on command. A Class is a blueprint for an object. The class tells 

the Ruby program how to make an object of a particular variety.

 


As in many languages, Scope defines where in a program Variable is accessible.  A Variable is a symbol or name that 

stands in place of a value. Variables are saved in memory locations and are used to store values such as numeric values, 

characters, character strings, or memory addresses so that they can be used in any part of the program. You assign a 

value to a Variable using the "=" symbol and best practices dictate that an assigned value starts with a lowercase letter 

and can contain letters, numbers and underscores. There are four types of Variables, plus the Constant. 



The first, Global Variables, designated with the "$" symbol, are accessible from anywhere in the Ruby program, regardless 

of where they are declared. Second, the Local Variable declared in a method or within a loop cannot be accessed outside 

of that loop or method. A Local Variable disappears after its scope ends.



The third type, Instance Variables, are designated with the "@" symbol and are similar to Class Variables except that their 

values are local to specific instances of an object. An object can store data in an Instance Variable, getting removed 

from memory only when the object is removed. The Class Variable is designated with "@@" and is a variable that is 

shared amongst all instances of a class. This means that only one variable value exists for all objects instantiated from 

this class. Additionally, this means that if one object instance changes the value of the variable, that new value will 

essentially change for all other object instances. Another way of thinking of thinking of class variables is as global 

variables within the context of a single class. 


Additionally, there is Constant Variable. A Constant doesn’t require any special symbol or syntax to declare. Best 

practices suggest that at least the first letter is uppercase. A Constant is not unlike the Local Variable except that 

its value is supposed to remain unchanged for the duration of the program. If you try to change the value of a Constant, 

errors will be returned. Constants declared within a class or module are available anywhere within the context of that 

class or module. Constants declared outside of a class or module are assigned global scope, they cannot be defined 

inside of a method and are generally found at the top of the class.



Ruby methods are used to bundle one or more repeatable statements into a single unit. Typically, method names should 

begin with a lowercase letter. Methods should be defined before calling them, otherwise Ruby will raise an exception for 

undefined method invoking. A method provides functionality to an Object. A class method provides functionality to a 

class itself, while an instance method provides functionality to one instance of a class. Instance methods are defined 

inside the class body. Ideally, you should use Instance Methods when the functionality you are trying to invoke is tied to 

the identity of a specific object.


When you want to access a method of a class, you will first need to instantiate the class. Then, using the object, you can 

access any member of the class. In Ruby, the method is defined with the keyword **def** and underscoring (if more than 

one word) and the block is finished with the keyword **end**. 



To protect your instances from invalid data, Ruby doesn't allow you to access or change Instance Variables from outside 

the class. Instead you can create something called an Attribute accessor method, which will write values to the Instance 

Variables and spit them back to you later. An attribute is another name for a piece of data regarding an object, There are 

two types of Accessor methods: Attribute writers and Attribute readers. Atrribute writer methods ***set*** an Instance 

Variable and Attribute reader methods ***get*** a value of an instance variable back. Accessor methods are regular 

Instance Methods, but their primary purpose is to access an Instance Variable.



In conclusion, Instance Methods operate on an object and have access to its instance variables, while a Class Method 

operates on a class as a whole and has no access to a particular Instance's Variables (unless you pass the instance in as 

a parameter)



I hope you enjoyed this basic explanation of Ruby OOP concepts!


