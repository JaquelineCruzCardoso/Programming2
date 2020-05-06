# :sparkles: Jaqueline Cruz Cardoso :sparkles:
## Describe concepts and characteristics of the classification of programming paradigms:
#### Declarative:
- [*Functional:*](https://www.geeksforgeeks.org/introduction-of-programming-paradigms/)
The functional programming paradigms has its roots in mathematics and it is language independent. The key principal of this paradigms is the execution of series of mathematical functions. The central model for the abstraction is the function which are meant for some specific computation and not the data structure. Data are loosely coupled to functions.The function hide their implementation. Function can be replaced with their values without changing the meaning of the program. Some of the languages like perl, javascript mostly uses this paradigm.

- [*Dataflow:*](https://towardsdatascience.com/computer-programming-c5e5793eb250)
models a program as a directed graph of the data flowing between operations implementing dataflow principles and architecture.

- [*Logic:*](https://towardsdatascience.com/computer-programming-c5e5793eb250)
a paradigm in which program statements express facts and rules about problems within a system of formal logic

- [*Constraint-based:*](http://wiki.theprovingground.org/constraint-based-programming)
Programming with constraints allows users to model and specify problems with uncertain, incomplete information and to solve combinatorial problems. Constraint-based programming languages include theoretical properties, conceptual simplicity, and practical success. The idea behind constraint programming is to solve problems by stating constraints, such as conditions or properties. These conditions or properties need to be satisfied in order to solve the problem. Constraints can be considered pieces of partial information and describe properties of unknown objects and the relationship between them. The unknown objects are then modeled as variables. As a constraint program is successfully run the constraint solver stores, combines, and simplifies the constraints to come up with a solution.

#### Imperative:
- [*Von Neumann:*](http://www.computinghistory.org.uk/det/3665/John-von-Neumann/)
is a design model for a stored-program digital computer that uses a processing unit and a single separate storage structure to hold both instructions and data. It is named after the mathematician and early computer scientist John von Neumann. Such computers implement a universal Turing machine and have a sequential architecture. The terms "von Neumann architecture" and "stored-program computer" are generally used interchangeably.

- [*Interpreted (Scripting):*](https://whatis.techtarget.com/definition/interpreted-script)
An interpreted program, sometimes called a script, is a program whose instructions are actually a logically sequenced series of operating system commands, handled one at a time by a command interpreter. In turn, the command interpreter requests services from the operating system. The writer of the interpreted program need not be concerned by low-level storage management considerations. On the other hand, an interpreted program can´t be as efficient as a compiled program, which has been processed by a language compiler. A language compiler converts source statements into something close to the strings of 0's and 1's that a processor ultimately is given to work on. Because this work is already done before a compiled program is run, it runs much more quickly.

- [*Object-oriented:*](https://towardsdatascience.com/computer-programming-c5e5793eb250)
termed by Alan Kay-based on the concept of objects, which can contain data, in the form of fields (attributes or properties), and code, in the form of methods (procedures). In this paradigm code can be structured as reusable components, some of which may share properties or behaviors.


## Identify the implementation methods of the programming paradigms:

- [*Interpreted Programming:*](https://www.freecodecamp.org/news/compiled-versus-interpreted-languages/)
Interpreters run through a program line by line and execute each command. Here, if the author decides he wants to use a different kind of olive oil, he could scratch the old one out and add the new one. Your translator friend can then convey that change to you as it happens.
Interpreted languages were once significantly slower than compiled languages. But, with the development of just-in-time compilation, that gap is shrinking.
Examples of common interpreted languages are PHP, Ruby, Python, and JavaScript.
- [*Compiled Programming:*](https://www.freecodecamp.org/news/compiled-versus-interpreted-languages/)
Compiled languages are converted directly into machine code that the processor can execute. As a result, they tend to be faster and more efficient to execute than interpreted languages. They also give the developer more control over hardware aspects, like memory management and CPU usage.
Compiled languages need a “build” step – they need to be manually compiled first. You need to “rebuild” the program every time you need to make a change. In our hummus example, the entire translation is written before it gets to you. If the original author decides that he wants to use a different kind of olive oil, the entire recipe would need to be translated again and resent to you.
Examples of pure compiled languages are C, C++, Erlang, Haskell, Rust, and Go.

## Describe concept and characteristics of data representation in structured programming language:
- [*Identifiers:*](http://aboutc.weebly.com/identifiers.html)
Identifiers are names for entities in a C program, such as variables, arrays, functions, structures, unions and labels. An identifier can be composed only of uppercase, lowercase letters, underscore and digits, but should start only with an alphabet or an underscore. If the identifier is not used in an external link process, then it is called as internal. Example: Local variable. If the identifier is used in an external link process, then it is called as external. Example: Global variable
An identifier is a string of alphanumeric characters that begins with an alphabetic character or an underscore character that are used to represent various programming elements such as variables, functions, arrays, structures, unions and so on. Actually, an identifier is a user-defined word. There are 53 characters, to represent identifiers. They are 52 alphabetic characters (i.e., both uppercase and lowercase alphabets) and the underscore character. The underscore character is considered as a letter in identifiers. The underscore character is usually used in the middle of an identifier. There are 63 alphanumeric characters, i.e., 53 alphabetic characters and 10 digits (i.e., 0-9).

- *[Variables:*](https://launchschool.com/books/ruby/read/variables)
Variables are used to store information to be referenced and manipulated in a computer program. They also provide a way of labeling data with a descriptive name, so our programs can be understood more clearly by the reader and ourselves. It is helpful to think of variables as containers that hold information. Their sole purpose is to label and store data in memory. This data can then be used throughout your program.

- [*Constants:*](https://press.rebus.community/programmingfundamentals/chapter/constants-and-variables/)
A constant is a value that cannot be altered by the program during normal execution, i.e., the value is constant. When associated with an identifier, a constant is said to be “named,” although the terms “constant” and “named constant” are often used interchangeably. This is contrasted with a variable, which is an identifier with a value that can be changed during normal execution, i.e., the value is variable.

- *[Reserved Words:*](https://beginnersbook.com/2014/01/c-keywords-reserved-words/)
In C, we have 32 keywords, which have their predefined meaning and cannot be used as a variable name. These words are also known as “reserved words”. It is good practice to avoid using these keywords as variable name. These are :
*if, else, switch, case, default* Used for decision control programming structure.
*break*  Used with any loop OR switch case.
*int, float, char, double, long* These are the data types and used during variable declaration.
*for, while, do* types of loop structures in C.
*void* One of the return type.
*goto* Used for redirecting the flow of execution.
*auto, signed, const, extern, register, unsigned* defines a variable.
*return* This keyword is used for returning a value.
*continue* It is generally used with for, while and dowhile loops, when compiler encounters this statement it performs the next iteration of the loop, skipping rest of the statements of current iteration.
*enum* Set of constants.
*sizeof* It is used to know the size.
*struct, typedef* Both of these keywords used in structures (Grouping of data types in a single record).
*union* It is a collection of variables, which shares the same memory location and memory storage.

- [*Types of data: primitives and composites (extended):*](https://dl.sumdu.edu.ua/textbooks/103395/597162/index.html)
Primitive:
 data types are predefined types of data, which are supported by the programming language. Programmers can use these data types when creating variables in their programs. Primitive data types can hold text messages, numbers and so on, but they don't readily accommodate higher levels of complexity.  For example, a programmer may create a variable called "name" and define it as a string data type. The variable will then store data as a string of characters.
Common examples of primitive data types:
Boolean (e.g. True or False)
Character (e.g. abc)
Date (e.g. 03/01/2017)
Double (e.g. 1.87651234355743E308)
Floating-point number (e.g. 1.23)
Integer (e.g. 123)
Long (e.g. 123456789)
Short (e.g. 0)
String (e.g. abc)
Void (e.g. no data)
A composite data type is one whose values are composed of component values (possibly values chosen from other data types.)  Example of composite data type is array. 
For instance, array-of-int values is a composite type, because an array-of-int value is comprised of some number of element values chosen from the int type.  Using composite data types, we can manage multiple pieces of related data as a single datum.
