# A Calculator
## by Jakub (Kuba) Perlin

*All the code in this project has been written by me.*

---

This is a calculator accepting expressions using decimal numbers and integers and the five operators:

+ addition [left-associative]
+ subtraction [left-associative]
+ multiplication [left-associative]
+ cosine
+ factorial (for natural numbers only)

(listed in the order of increasing precedence)

**This project contains a custom lexer and a specialized parser generator based on the book "*Compilers: principles, techniques and tools (2nd edition)*".**

---

## Usage:

+ The calculator is a Windows console application. On start up, it takes some seconds to generate a parser, given the grammar specified in GRAMMAR.txt.
+ Put your queries, before running the calculator, in the input.txt file, which also contains formatting instructions.
  + You will also be able to specify more queries on runtime of the console application.
+ *Currently paths to the grammar and input files are hardcoded - go to main.cpp and modify them to your liking.*
