Project Objective

The objective of this project is to understand and implement the internal working of a compiler by building essential compiler modules from scratch. The repository demonstrates how source code is transformed through multiple compilation phases into structured intermediate representations.

The project covers:

Lexical Analysis
Syntax Parsing
Symbol Table Management
Expression Evaluation
Abstract Syntax Tree (AST) Construction
Intermediate Code Generation (ICG)
Programming Exercises
PE1 – Lexical Analyzer

Implementation of a complete lexical analyzer for the C programming language using FLEX/LEX.

Achievements
Recognizes valid C tokens
Identifies:
Keywords
Identifiers
Constants
Operators
String literals
Character literals
Punctuators
Converts source code into a token stream representation

This phase demonstrates the front-end scanning phase of a compiler.

PE2 – Syntax Parser

Implementation of a parser using YACC/Bison for validating the syntax of a simplified C language subset.

Achievements
Parses:
Variable declarations
Arithmetic expressions
Relational expressions
if / if-else statements
do-while loops
Nested blocks
Detects syntax errors with line information
Validates grammatical correctness of programs

This phase demonstrates context-free grammar parsing and syntax validation.

PE3 – Symbol Table Implementation

Implementation of a compiler symbol table for storing identifier metadata.

Achievements
Tracks:
Variable names
Functions
Parameters
Types
Scope levels
Storage classes
Memory sizes
Records declaration and usage information
Supports scoped symbol management

This module represents the semantic information management phase of the compiler.

PE4 – Expression Evaluation & Semantic Checking

Implementation of expression evaluation using YACC/Bison integrated with symbol table updates.

Achievements
Evaluates arithmetic expressions
Updates symbol table values dynamically
Detects:
Undeclared variables
Type mismatches
Semantic inconsistencies
Produces meaningful compiler error messages

This phase introduces semantic analysis and runtime expression handling.

PE5 – Abstract Syntax Tree (AST)

Implementation of Abstract Syntax Tree generation for arithmetic expressions.

Achievements
Constructs AST nodes for expressions
Represents hierarchical program structure
Performs postorder traversal
Produces Reverse Polish notation output

This phase demonstrates how compilers internally represent program structure before optimization and code generation.

PE6 – Intermediate Code Generation (ICG)

Implementation of three-address code generation for arithmetic expressions and assignments.

Achievements
Generates quadruple-based intermediate code
Creates temporary variables automatically
Produces low-level intermediate representation
Converts expressions into compiler-friendly instruction format

This phase demonstrates the transition from syntax trees to machine-independent intermediate code.

Assignments
Assignment 1 – Extended Parser

Extension of the syntax parser to support additional C language constructs.

Added Features
for loops
while loops
switch statements
Variable initialization
Multi-dimensional arrays

This assignment expands parser complexity and improves grammar handling capabilities.

Assignment 2 – AST & ICG for Control Statements

Extension of AST construction and intermediate code generation for control-flow statements.

Added Features
if-else statements
do-while loops
Relational condition handling
Control-flow representation

This assignment demonstrates compiler handling of branching and looping constructs.
