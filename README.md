
windows + r = executer
dann cmd eingeben = terminal

https://github.com/
https://www.python-kurs.eu/kurs.php
https://python-programmieren.com/
https://de.wikihow.com/Mit-Programmierung-in-Python-beginnen
http://www.pythonmania.de/
https://wiki.python.org/moin/GermanLanguage
https://wiki.python.org/moin/BeginnersGuide/NonProgrammers

IDLE = Script, Shell fuehrt aus (Speichern, Run module)
len heisst length, also die Länge eines Vektors beziehungsweise eines Strings. Ein String ist eine Abfolge von Buchstaben (characters)


CODE: wird geschrieben auf Python IDLE (genau wie SHELL interpreter, mit extras)
Remember that when we type something at that prompt and hit Enter, Idle is:
    translating what we've typed
    talking to the computer
    then getting an answer from the computer and sending it back to us in a language that WE can understand



Home » Python Tutorial » Intro to Python
Intro to Python

Contents
Python is a high level, general purpose programming created by Guido Van Rossum. It was publicly released in 1991. By high level, we mean a language which hides nitty-gritty details from the programmer. Further, It also used to refer to a Computer language which is easy to understand for humans. Python is known for known for its simplicity and readability.
Features of Python
Python is Easy
Python is one of the easiest languages to get started with. Programs written in Python looks very much like the English language. Because of its simplicity, most entry-level programming courses use Python to introduce programming concepts to their students.
Python is Portable/Platform Independent
Python is portable which means we can run Python programs in the various different operating system without any changes.
Python is an Interpreted Language
Python is an Interpreted language. Languages like C, C++ are examples of compiled language.
Programs written in a high-level language are called source code or source program and the commands in the source code are called statements. A computer can’t execute a program written in high-level language, it only understands machine language which consists of 0s and 1s only.
There are two types of programs available to us to translate a high-level language to machine language:

    Compiler
    Interpreter

Compiler:
A compiler translates the entire source code into machine language in one go, the machine language is then executed.

program-execution-by-compiler
Interpreter:
An interpreter, on the other hand, translates high-level language into machine language line by line, which it then executes. Python Interpreter starts at the top of the file, translates the first line into machine language and then executes it. This process keeps repeating until the end of the file is reached.


OPERATORS: + - / *

a decimal number is called a float, if you want integers (ganze zahlen): type round(x/y) oder int(x/y) (bsp round(10/3) wird zu 3
These are called comparison operators.
== 	Equal to
!= 	Not equal to
< 	Less than
> 	Greater than
<= 	Less than or equal to
>= 	Greater than or equal to
the answer is going to be either True or False, something we call a Boolean

STRINGS:
When we use the word string in programming, we're talking about characters, like letters or symbols, or a bunch of characters put together, like words.
Rule: If you want Python to read a string, it must be inside quotes.
Concatenation is a little bit like adding - we use it to put strings together side by side.
And multiplying controls how many times we show a string.

Each of those characters has a position in the string, and that position is called an index. (square brackets) positions start from 0/zero bsp: [4] index = position 4
If it had quotes around it, Python would treat it like a string.
Without quotes, Python knows that it's a variable.RULES:Calculate once, keep the result to use later,Keep the same name, change the value

When we're assigning a value, we're saying "this equals that". That's a short sentence, so it only gets one equal sign: =
But when we're comparing values, we're asking "is this thing equal to that thing?". And that's a longer sentence, so it gets two equal signs: ==
