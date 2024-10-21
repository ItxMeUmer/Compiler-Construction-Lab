# Compiler-Construction-Lab


**University Name**: University Of Engineering And Technology, lahore 
**Department**: Department of Computer Science

## Course Details
**Course Title**: Compiler Construction   
**Semester**: Fall 2024  
**Course Instructor**: Mr.Laeeq Khan Niazi

## Lab Overview
The **Compiler-Construction-Lab** is designed to provide hands-on experience in the development of a compiler. This lab complements the theoretical concepts discussed in lectures, guiding students through the stages involved in translating high-level programming code into executable machine code. 

## Stages of Compiler Construction

### 1. Lexical Analysis
This is the first phase of the compiler, where the source code is scanned to produce tokens. The lexical analyzer reads the input stream and divides it into meaningful elements like keywords, identifiers, operators, and literals using regular expressions.

### 2. Syntax Analysis
Also known as parsing, this phase checks for the correct syntactic structure of the code based on predefined grammar rules. It constructs a syntax tree (or parse tree) by applying parsing algorithms such as LL or LR parsers to the tokens produced by the lexical analyzer.

### 3. Semantic Analysis
In this phase, the compiler checks the semantic consistency of the syntax tree, ensuring that the code follows the language’s rules. It performs type checking, scope validation, and ensures that variables and functions are correctly defined and used.

### 4. Intermediate Code Generation
Once the semantic checks pass, the compiler generates an intermediate code, a low-level representation of the source program that is independent of machine architecture. This makes the code more flexible for further optimizations.

### 5. Code Optimization
This phase improves the intermediate code by making it more efficient without changing its output. Common optimizations include eliminating redundant instructions, folding constants, and optimizing loops to reduce execution time and memory usage.

### 6. Target Code Generation
In the final stage, the optimized intermediate code is translated into the machine language of the target architecture. This includes tasks like instruction selection, register allocation, and code emission.

---

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/ItxmeUmer/Compiler-Construction-Lab.git
