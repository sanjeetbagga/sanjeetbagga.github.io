---
published: true
title: Programming - Basic Java Cheatsheet
layout: post
---
# Table of Contents
- Types of data
- Variables
- Printing Data
- Grouping variables together
- Methods
- Expressions
- If Statement
- For and While Loops


### Types of Data
Data can be in a few types. 
Primitive data is native in java. The primitive types are: 

* int (Integers)
- boolean (True or False)
- char (Characters)
- long (Time)
- float (Number with a fractional part)
- double (Number to its decimal place) 
- byte (Used to store up to eight bits)

Non-primitive data can be imported into java. Some of these include:

- Lists (list of objects)
- Strings (word)
- Objects
- Scanner (Gather info from file)
- BufferedReader (Gather info from file)
- ArrayLists (Store objects)
- etc.


### Variables
These are basically data containers that you can call on in a given program.
You can store all types of data in here.

- Example (Primitive): int x = 0;

- Example (Non-Primitive): Object o = new Object();

### Printing Data
In order to display data, you call the System.out.print(DATA) command. You can also put an "ln" after "print" to print the data in a new line.

- Ex: System.out.println(DATA);

### Grouping Variables
You can group variables of the same type in different ways.
One way is by using arrays. 

Think of arrays as a hotel floor. As you can assign people to different hotel rooms on a floor, you can assign data into different slots of an array.

- How you do that is by first creating it: DATATYPE [] rooms = new DATATYPE[# of objects]; 

- And then filling it up, from slot 0 to the number of objects you put in, minus one.

- To fill it up, you simply: rooms [your slot number] = your data;

- And to call that data, you use: rooms [your slot number] like a variable. Ex: System.out.print(rooms[0]);



### Methods
These are like headers for your program. They act as subsections of your code and allow you to call them when needed. 
You can add parameters to your method, which allow you to give your method data to use in it.

- Example: public static VARIABLE TYPE name (PARAMETERS, IF ANY) {

// Code
}

The keyword static allows you to access the method with different methods throughout your program. 

### Expressions
These are true or false statements that you can use to compare two variables or primitive values.
You can compare by using the following:
>= (Greater than or equal)
== (Equal)
<= (Less than or equal)
> (Greater than)
< (Less than)
.compareTo (want to use for non-primitives)
.equals (want to use for non-primitives)
and many more

- Ex: 1 >= 2
- Ex: 'a' >= 'z'
- Ex: int a = 2; int b = 2; a == 2

### If Statements
These statements allow you to use expressions to trigger certain commands and code.

Ex: if ( a >= b) {
// if the expression is true, then run this code
}
You can add an else command afterwards to run if the statement is false

Ex: if () {

//Code
} 
else // you can add an if statement here too if you still want to compare something {

//Code
}


### For and While Loops
For loops allow you to run statements continuously from a starting point to an ending point. To do that, you give the code a starting point, an expression to when you want the code to stop, and what to do after you have run the code once.
Ex: for (int x = 0; 0 >= 100; x++)  { 

// This will start the code when x is equal to 0 and run it until x is equal to 100

}

For each loops allow you to run statements as long as objects are in a group of object. To do this, you simply give the object data type with a variable name and the object group into the code. 

Ex: for (DATA TYPE name | group) {

// Will loop all the data from the given data type in the group. You can access this info from the name.

}

While loops allow you to loop through statements while a certain expression is true. 

Ex: while(Expression) {
//Code to run while the expression is true.
}

### This covers only the basics in Java. This cheatsheet will not go in depth into stuff like data encapsulation or anything of that sort.

