---
layout: post
title:  "Programming"
image: ''
date:   2017-10-05 00:00:00
tags:
- Programing
- Python
description: ''
categories:
- Programing
- Python
---

<img src="https://thumbsplus.tutsplus.com/uploads/users/48/posts/29072/preview_image/data-python-3%20(1).png?height=300&width=300">

# Programming Lingo / Meaning
Ive written down and collected all information to create an idea of programming in my mind. Many of the examples are towards python.

## Syntax
Syntax refers to the spelling and grammar of a programming language. Computers are inflexible machines that understand what you type only if you type it in the exact form that the computer expects. The expected form is called the syntax.
Each program defines its own syntactical rules that control which words the computer understands, which combinations of words are meaningful, and what punctuation is necessary to be a correctly structured document.

The three levels of syntax include the following:
Lexical syntax : All the basic symbols of the language (i.e. names, values, operators).
Concrete syntax: The rules for writing expressions, statements and programs.
Abstract syntax: The internal representation of the program specified by a simpler grammar than the concrete syntax.

## Variables
A symbol or name that stands for a value
x + y = z
<br>x,y and z are all variables or symbols for potential values

## Literals
A value that is writen to mean exactly what it is, it can be a number, a character or any string. 
<br>For example, in the expression, x = 3
<br>x is a variable, and 3 is a literal.

## Constant
In programming, a constant is a value that never changes. The other type of values that programs use is variables, symbols that can represent different values throughout the course of a program.
A constant can be
a number, like 25 or 3.6
a character, like a or $
a character string, like "this is a string"

## But wait! a Literal and Constant sound the same!
A literal is a value that is expressed as itself. For example, the number 25 or the string "Hello World" are both literals.

A constant is a data type that substitutes a literal. Constants are useful in situations where
a specific, unchanging value is to be used at various times during the software program.
you want to more easily understand the software code
A variable in a program can change its value during the course of execution of the program. A constant retains the same value throughout the program.

Constant Example:
<br>const PI = 3.14; var radius = 5; var circumference = 2 * PI * radius;	

Literal Example:
<br>Var radius = 5; var circumference = 2 * 3.14 * radius;

## Expression
In programming, an expression is any legal combination of symbols that represents a value. Each programming language and application has its own rules for what is legal and illegal. 
<br>For example, in the C language x+5 is an expression, as is the character string "MONKEYS."
Every expression consists of at least one operand and can have one or more operators. Operands are values, whereas operators are symbols that represent particular actions. 

Example:
<br>In the expression x + 5
<br>x and 5 are operands, and + is an operator.

## Operators
A symbol that represents a specific action. 
<br>For example, a plus sign (+) is an operator that represents addition. The basic mathematic operators are + addition, - subtraction, * multiplication, / division.

In addition to these operators, many programs and programming languages recognize other operators that allow you to manipulate numbers and text in more sophisticated ways. For example, Boolean operators enable you to test the truth or falsity of conditions, and  relational operators let you compare one value to another.

## Operand
In all computer languages, expressions consist of two types of components: operands and operators. Operands are the objects that are manipulated and operators are the symbols that represent specific actions.

For example in the expression 5 + x
<br> x and 5 are operands and + is an operator. 

All expressions have at least one operand.

## Charachter
In computer software, any symbol that requires one byte of storage. This includes all the ASCII and extended ASCII characters, including the space character.

In character-based software, everything that appears on the screen, including graphics symbols, is considered to be a character.

In graphics-based applications, the term character is generally reserved for letters, numbers, and punctuation.

## Charachter Strings
A character string is a series of characters manipulated as a group. A character string differs from a name in that it does not represent anything -- a name stands for some other object.

A character string is often specified by enclosing the characters in single or double quotes. For example, WASHINGTON would be a name, but 'WASHINGTON' and "WASHINGTON" would be character strings.

## Data types
Types of data tells the interpeter or compiler how the data is intended to be used 
The most important ones are:

| Data Type 		| Values                                                     	|
|:----------------------|:--------------------------------------------------------------|
| Booleans  		| True or False  						|
| Integers  		| (1 and 2)     						| 
| Floats    		| (1.1 and 1.2) 						|
| Fractions 		| (1/2 and 2/3) or even complex numbers 			|
| Strings   		| are sequences of Unicode characters, e.g. an html document	|
| Bytes and byte arrays | e.g. a jpeg image file 			 		|
| Lists     		| are ordered sequences of values   			 	|
| Tuples    		| are ordered, immutable sequences of values 		 	|
| Sets      		| are unordered bags of values 				 	|
| Dictionaries 		| are unordered bags of key-value pairs 			|
|---------------------------------------------------------------------------------------|

## Keywords
A programing language reserves some keywords for opperators and such.

Here is a table having almost all the keywords supported by Python Programming language Keywords are
reserved words for the programing language and part of the syntax.

|**KeyWords**	|**In**		|**Python**	|
|:-------------:|:-------------:|:-------------:|
|and		|exec 		|not		|
|assert		|finally	|or		|
|break		|for		|pass		|
|class		|from		|print		|
|continue	|global		|raise		|
|def		|if		|return		|
|del		|import		|try		|
|elif		|in		|while		|
|else		|is		|with		|
|except		|lambda		|yield		|
|-----------------------------------------------|

## Operators
A symbol that represents a specific action. For example, a plus sign (+) is an operator that represents addition. The basic mathematic operators are + addition, - subtraction,* multiplication,/ division.

**There are diffrent types of operators**
+ Arithmetic operators
+ Comparison (Relational) operators
+ Logical (Boolean) operators
+ Bitwise operators
+ Assignment operators
+ Special operators

source
<a href="https://www.programiz.com/python-programming/operators" target="_Blank">Operators Information</a>

<img src="http://2.bp.blogspot.com/-tFSfukQ1xvA/VHSjD5vqe6I/AAAAAAABHXI/JEfDfPBLGu8/s1600/Women%2BTelephone%2BOperators%2Bat%2BWork%2B(12).jpg">


## Statements
A statement is the smallest standalone element of an imperative programming language that expresses some action to be carried out. 
<br>It is an instruction written in a high-level language that commands the computer to perform a specified action. 
<br>A program written in such a language is formed by a sequence of one or more statements. A statement may have internal components (e.g., expressions).

|Statement	|Action							|
|:--------------|:------------------------------------------------------|
|=		|Assignment						|
|assert		|Assertion facility					|
|break		|Break out of a loop					|
|class		|Define a new class of objects				|
|continue	|Go to the top of a loop				|
|def		|Define a function					|
|del		|Delete a variable or part of an object			|
|elif		|If 							|
|else		|else							|
|except		|catching Exceptions					|
|exec		|Dynamically execute Python code			|
|finally	|cathcing exceptions					|
|for		|Iterate over the members of a sequence			|
|from		|Import names from a module				|
|global		|Use a global variable					|
|if		|Conditional branching					|
|import		|Import an external module				|
|pass		|A placeholder, no-operation statement			|
|print		|Display values to output				|
|raise		|Raise an exception					|
|return		|Return a result of a function				|
|try		|Anticipate possible exceptions				|
|while		|Repeat a group of statements				|
|yield		|Return one of a sequence of values from a generator	|
|-----------------------------------------------------------------------|

## Functions and or Procedures
In programming, a named section of a program that performs a specific task. In this sense, a function is a type of procedure or routine. 

Some programming languages make a distinction between a function, which returns a value, and a procedure, which performs some operation but does not return a value.

## Expressions
An expression is any valid unit of code that resolves to a value.

An expression in a programming language is a combination of one or more explicit values, constants, variables, operators, and functions that the programming language interprets (according to its particular rules of precedence and of association) and computes to produce ("to return", in a stateful environment) another value. This process, as for mathematical expressions, is called evaluation.

## Assignments
In computer programming, an assignment statement sets and/or re-sets the value stored in the storage location(s) denoted by a variable name; in other words, it copies a value into the variable. In most imperative programming languages, the assignment statement (or expression) is a fundamental construct.

## Conditionals
Referring to an action that takes place only if a specific condition is met. 
<br>Conditional expressions are one of the most important components of programming languages because they enable a program to act differently each time it is executed, depending on the input. 
<br>Most programming languages use the word if for conditional expressions.

For example, the conditional statement:
<br>if x equals 1 exit
<br>directs the program to exit if the variable x is equal to 1.

## Loops
One of the three basic logic structures in computer programming.

The other two logic structures are selection and sequence.

In a loop structure, the program asks a question, and if the answer requires an action, it is performed and the original question is asked again until the answer is such that the action is no longer required.

For example, a program written to compute a companys weekly payroll for each individual employee will begin by computing the wages of one employee and continue performing that action in a loop until there are no more employee wages to be computed, and only then will the program move on to its next action. 

Each pass through the loop is called an **iteration**. Loops constitute one of the most basic and powerful programming concepts.

All logic problems in programming can be solved by forming algorithms using only the three logic structures, and they can be combined in an infinite number of ways. The more complex the computing need, the more complex the combination of structures.

<img src="https://cdn.dribbble.com/users/196525/screenshots/1216701/companioncube2.gif">

## Selection
Also called a decision, one of the three basic logic structures in computer programming.

In a selection structure, a question is asked, and depending on the answer, the program takes one of two courses of action, after which the program moves on to the next event.
This structure is sometimes referred to as an if-then-else because it directs the program to perform in this way: If Condition A is True then perform Action X elseperform Action Y.

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c5/If-Then-Else-diagram.svg/1200px-If-Then-Else-diagram.svg.png" width="50%" height="50%">

## Sequence
One of the three basic logic structures in computer programming. 

In a sequence structure, an action, or event, leads to the next ordered action in a predetermined order. 
<br>The sequence can contain any number of actions, but no actions can be skipped in the sequence.

The program, when run, must perform each action in order with no possibility of skipping an action or branching off to another action.

## Compiled Languages
<img src="http://www.webopedia.com/FIG/COMPILE.gif">
To transform a program written in a high-level programming language from source code into object code. 
Programmers write programs in a form called source code. Source code must go through several steps before it becomes an executable program. 

The first step is to pass the source code through a compiler, which translates the high-level language instructions into object code.
<br>The final step in producing an executable program -- after the compiler has produced object code -- is to pass the object code through a linker. The linker combines modules and gives real values to all symbolic addresses, thereby producing machine code.


## Interpetive Language (scripting)
An interpreted language is a programming language for which most of its implementations execute instructions directly, without previously compiling a program into machine-language instructions.
<br>The interpreter executes the program directly, translating each statement into a sequence of one or more subroutines already compiled into machine code.

The terms interpreted language and compiled language are not well defined because, in theory, any programming language can be either interpreted or compiled. In modern programming language implementation it is increasingly popular for a platform to provide both options.

Interpreted languages can also be contrasted with machine languages. Functionally, both execution and interpretation mean the same thing — fetching the next instruction/statement from the program and executing it. Although interpreted byte code is additionally identical to machine code in form and has an assembler representation, the term "interpreted" is practically reserved for "software processed" languages (by virtual machine or emulator) on top of the native (i.e. hardware) processor.

In principle, programs in many languages may be compiled or interpreted, emulated or executed natively, so this designation is applied solely based on common implementation practice, rather than representing an essential property of a language.

Many languages have been implemented using both compilers and interpreters, including BASIC, C, Lisp, Pascal, and Python. Java and C# are compiled into bytecode, the virtual machine-friendly interpreted language. Lisp implementations can freely mix interpreted and compiled code.

## Typing
In programming languages, a type system is a set of rules that assigns a property called type to the various constructs of a computer program, such as variables, expressions, functions or modules. These types formalize and enforce the otherwise implicit categories the programmer uses for data structures and components (e.g. "string", "array of float", "function returning boolean"). 

The main purpose of a type system is to reduce possibilities for bugs in computer programs by defining interfaces between different parts of a computer program, and then checking that the parts have been connected in a consistent way. This checking can happen statically (at compile time), dynamically (at run time), or as a combination of static and dynamic checking. 
<br>Type systems have other purposes as well, such as expressing business rules, enabling certain compiler optimizations, allowing for multiple dispatch, providing a form of documentation, etc.

A type system associates a type with each computed value and, by examining the flow of these values, attempts to ensure or prove that no type errors can occur. The given type system in question determines exactly what constitutes a type error, but in general the aim is to prevent operations expecting a certain kind of value from being used with values for which that operation does not make sense (logic errors); memory errors will also be prevented. 

Type systems are often specified as part of programming languages, and built into the interpreters and compilers for them; although the type system of a language can be extended by optional tools that perform added kinds of checks using the languages original type syntax and grammar.

Scripting languages came about largely because of the development of the Internet as a communications tool. JavaScript, ASP, JSP, PHP, Perl, Tcl and Python are examples of scripting languages

### Strong / Weak Typing
In computer programming, programming languages are often colloquially classified as strongly typed or weakly typed (loosely typed). 
<br>These terms do not have a precise definition, but in general, a strongly typed language is more likely to generate an error or refuse to compile if the argument passed to a function does not closely match the expected type. 
<br>On the other hand, a weakly typed language may produce unpredictable results or may perform implicit type conversion.

<a href="https://pythonconquerstheuniverse.wordpress.com/2009/10/03/static-vs-dynamic-typing-of-programming-languages/" target="_blank">Typing Information Source</a>

## Programing Paradigms

Programming paradigms are a way to classify programming languages based on their features. Languages can be classified into multiple paradigms.

Some paradigms are concerned mainly with implications for the execution model of the language, such as allowing side effects, or whether the sequence of operations is defined by the execution model. Other paradigms are concerned mainly with the way that code is organized, such as grouping a code into units along with the state that is modified by the code. Yet others are concerned mainly with the style of syntax and grammar.

Common programming paradigms include:

+ imperative which allows side effects,
+ functional which disallows side effects,
+ declarative which does not state the order in which operations execute,
+ object-oriented which groups code together with the state the code modifies,
+ procedural which groups code into functions,
+ logic which has a particular style of execution model coupled to a particular style of syntax and grammar, and
+ symbolic programming which has a particular style of syntax and grammar.

For example, languages that fall into the imperative paradigm have two main features:
<br>they state the order in which operations occur, with constructs that explicitly control that order, and they allow side effects, in which state can be modified at one point in time, within one unit of code, and then later read at a different point in time inside a different unit of code. The communication between the units of code is not explicit. 

<br>Meanwhile, in object-oriented programming, code is organized into objects that contain state that is only modified by the code that is part of the object. Most object-oriented languages are also imperative languages. 

<br>In contrast, languages that fit the declarative paradigm do not state the order in which to execute operations. Instead, they supply a number of operations that are available in the system, along with the conditions under which each is allowed to execute. The implementation of the languages execution model tracks which operations are free to execute and chooses the order on its own. More at Comparison of multi-paradigm programming languages.

Here is an overview:

|Paradigm|Description|Main traits|Related paradigm(s)|Examples|
|--------|-----------|-----------|-------------------|--------|
|Imperative	|Programs as statements that directly change computed state (datafields)|Direct assignments, common data structures, global variables||C, C++, Java, PHP, Python, Ruby|
|Structured	|A style of imperative programming with more logical program structure|Structograms, indentation, no or limited use of goto statements|Imperative|C, C++, Java, Python|
|Procedural	|Derived from structured programming, based on the concept of modular programming or the procedure call|Local variables, sequence, selection, iteration, and modularization|Structured, imperative|C, C++, Lisp, PHP, Python|
|Functional	|Treats computation as the evaluation of mathematical functions avoiding state and mutable data|Lambda calculus, compositionality, formula, recursion, referential transparency, no side effects|Declarative|C++, Clojure, Coffeescript, Elixir, Erlang, F#, Haskell, Lisp, Python, Ruby, Scala, SequenceL, Standard ML, JavaScript
|Event-driven including time-driven|Control flow is determined mainly by events, such as mouse clicks or interrupts including timer|Main loop, event handlers, asynchronous processes|Procedural, dataflow|JavaScript, ActionScript, Visual Basic, Elm|
|Object-oriented|Treats datafields as objects manipulated through predefined methods only|Objects, methods, message passing, information hiding, data abstraction, encapsulation, polymorphism, inheritance, serialization-marshalling|Procedural|Common Lisp, C++, C#, Eiffel, Java, PHP, Python, Ruby, Scala|
|Declarative|Defines program logic, but not detailed control flow|Fourth-generation languages, spreadsheets, report program generators||SQL, regular expressions, CSS, Prolog, OWL, SPARQL|
Automata-based programming|Treats programs as a model of a finite state machine or any other formal automata|State enumeration, control variable, state changes, isomorphism, state transition table|Imperative, event-driven|Abstract State Machine Language|

Sources for Further Reading
1. <a href="https://en.wikipedia.org/wiki/Comparison_of_programming_paradigms" target="_blank">Programing Paradigms Wiki</a>
2. <a href="http://www.webopedia.com/TERM/O/object_oriented_programming_OOP.html" target="_blank">OOP Object Oriented Programing</a>

## Declarative
In computer science, declarative programming is a programming paradigm—a style of building the structure and elements of computer programs—that expresses the logic of a computation without describing its control flow.

Many languages that apply this style attempt to minimize or eliminate side effects by describing what the program must accomplish in terms of the problem domain, rather than describe how to accomplish it as a sequence of the programming language primitives (the how being left up to the languages implementation). This is in contrast with imperative programming, which implements algorithms in explicit steps.

Declarative programming often considers programs as theories of a formal logic, and computations as deductions in that logic space. Declarative programming may greatly simplify writing parallel programs.

Common declarative languages include those of database query languages (e.g., SQL, XQuery), regular expressions, logic programming, functional programming, and configuration management systems.


## Data Scope
In computer programming, the scope of a name binding – an association of a name to an entity, such as a variable – is the region of a computer program where the binding is valid: where the name can be used to refer to the entity.
<br>Such a region is referred to as a scope block. In other parts of the program the name may refer to a different entity (it may have a different binding), or to nothing at all (it may be unbound).

The scope of a binding is also known as the visibility of an entity, particularly in older or more technical literature – this is from the perspective of the referenced entity, not the referencing name. 
<br>A scope is a part of a program that is or can be the scope for a set of bindings – a precise definition is tricky, but in casual use and in practice largely corresponds to a block, a function, or a file, depending on language and type of entity. 
<br>The term "scope" is also used to refer to the set of all entities that are visible or names that are valid within a portion of the program or at a given point in a program, which is more correctly referred to as context or environment.

Strictly speaking and in practice for most programming languages, "part of a program" refers to "portion of the source code (area of text)", and is known as lexical scope. In some languages, however, "part of a program" refers to "portion of run time (time period during execution)", and is known as dynamic scope. 

Both of these terms are somewhat misleading – they misuse technical terms, as discussed in the definition – but the distinction itself is accurate and precise, and these are the standard respective terms. Lexical scope is the main focus of this article, with dynamic scope understood by contrast with lexical scope.

In most cases, name resolution based on lexical scope is straightforward to use and to implement, as in use one can simply read backwards in the source code to determine to which entity a name refers, and in implementation one can simply maintain a list of names and contexts when compiling or interpreting a program. Basic difficulties arise in name masking, forward declarations, and hoisting, while considerably subtler ones arise with non-local variables, particularly in closures.


