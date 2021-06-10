# Small C compiler

## About the project
Small C compiler was a very interesting project assigned by our professor at the Compilers Lecture.
For this assignment we had to develop a compiler (based on C/C++ Syntax) able to do the following:

 - Arithmetic Expressions
 - Comparisson
 - Boolean operations (AND, OR)
 - Blocks [] {}
 - Types: Int, Float, String, Boolean.
 - Control flows: If, While, Do While, For
 - End of line with ;
 - Variable assignation and declaration on same line

## How it works?
For this it was required the use of PLY, a Python package that allows us to use Lex and Yacc for the lexical analysis but also the parsing phase. 

## Setup
Disclaimer: I ran this setup using a Linux based OS, specifically Pop OS. If you face trouble setting everything up on Windows or MacOS I highly suggest you to try on a Linux based OS.

1. Make sure to have Python > 2.7.x installed on your computer.
2. Install the PLY package using PIP:


> **pip install ply**

## Usage
This is a C Syntax Based compiler, so in order to try it out, go to your project folder where small_compiler.py is and use the following command:

    small_compiler.py <YOUR_C_PROGRAM.C>

This will generate several files, if your source code compiled succesfully all you have to do now is type:

    ./a.out

This will execute your C program. 

Hope this works for you!
