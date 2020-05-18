### Conditionals on C (lenguage of programming)

The conditional operator is kind of similar to the if-else statement as it does follow the same algorithm as of if-else statement but the conditional operator takes less space and helps to write the if-else statements in the shortest way possible.
- Syntax:

The conditional operator is of the form
variable = Expression1 ? Expression2 : Expression3
It can be visualized into if-else statement as:

_if(Expression1)_
_{_
    _variable = Expression2;_
_}_
_else_
_{_
   _ variable = Expression3;_
_}_


# Loops

A Loop executes the sequence of statements many times until the stated condition becomes false. A loop consists of two parts, a body of a loop and a control statement. The control statement is a combination of some conditions that direct the body of the loop to execute until the specified condition becomes false. The purpose of the loop is to repeat the same code a number of times.

**Types of Loops**
Depending upon the position of a control statement in a program, a loop is classified into two types:

1. Entry controlled loop

2. Exit controlled loop

In an entry controlled loop, a condition is checked before executing the body of a loop. It is also called as a pre-checking loop.

In an exit controlled loop, a condition is checked after executing the body of a loop. It is also called as a post-checking loop.


**_While Loop_**
A while loop is the most straightforward looping structure. The basic format of while loop is as follows:

while (condition) {
             statements;
}

**_Do-While loop_**
A do-while loop is similar to the while loop except that the condition is always executed after the body of a loop. It is also called an exit-controlled loop.

The basic format of while loop is as follows:

 do {
  statements
} while (expression);


**_ For loop_**
A for loop is a more efficient loop structure in 'C' programming. The general structure of for loop is as follows:

for (initial value; condition; incrementation or decrementation ) 
{
  statements;
}
