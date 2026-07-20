Lexical Analyzer in C

Description

This project implements a simple Lexical Analyzer for the C programming language. It reads a C source file, identifies different types of tokens, and displays their corresponding token type.

A lexical analyzer is the first phase of a compiler that converts source code into meaningful tokens.

Features

- Identifies Keywords
- Identifies Identifiers
- Identifies Constants
  - Integer
  - Float
  - Character
  - String
- Identifies Operators
- Identifies Special Characters
- Displays tokenized output
- Detects common lexical errors


Files

- main.c - Main function
- lexical.c - Lexer implementation
- lexical.h - Function declarations and data structures
- input.c - Sample input file

How to Compile

gcc main.c lexical.c 

How to Run

./a.out input.c

Sample Output


Keyword      : int
Identifier   : main
Special Char : (
Special Char : )
Special Char : {
Keyword      : int
Identifier   : num
Operator     : =
Literal      : 100
Special Char : ;
Keyword      : return
Literal      : 0
Special Char : ;
Special Char : }


Concepts Used

- C Programming
- File Handling
- Structures
- Enumerations
- String Handling
- Character Handling (`ctype.h`)
- Compiler Design Basics


Author

Rosna Shaji
