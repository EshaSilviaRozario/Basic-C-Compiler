# C Compiler

A basic C compiler implementation written in [your language]. This project demonstrates the fundamental phases of compilation through a modular architecture.

## Overview

This compiler translates C source code into executable output by processing the code through four distinct phases: lexical analysis, parsing, semantic analysis, and intermediate code generation.

## Project Structure

```
c-compiler/
├── LEXICAL_ANALYZER/     # Tokenization and lexeme recognition
├── PARSER/               # Syntax analysis and AST construction
├── SEMANTIC_ANALYSIS/    # Type checking and symbol table management
├── ICG/                  # Intermediate code generation
└── README.md
```

### Folders

**LEXICAL_ANALYZER** - Converts source code into tokens. Recognizes keywords, identifiers, operators, literals, and special symbols.

**PARSER** - Builds a syntax tree from tokens by validating grammar rules. Implements recursive descent or other parsing techniques.

**SEMANTIC_ANALYSIS** - Performs type checking, validates variable declarations, manages the symbol table, and ensures semantic correctness.

**ICG** - Generates intermediate code (three-address code or similar representation) from the abstract syntax tree for further optimization or compilation.

## Features

- Tokenization with proper symbol recognition
- Recursive descent parsing for syntax validation
- Symbol table management for scope and type information
- Basic semantic error detection
- Intermediate code generation

## Building and Running

[Add your build instructions here. Example:]

```bash
# Compile the project
gcc -o compiler main.c [other source files]

# Run the compiler on a C source file
./compiler input.c -o output
```

## Usage

```bash
./compiler <input_file.c> [options]
```

## Supported Features

[List the C language features your compiler supports, such as:]

- Variable declarations and assignments
- Arithmetic and logical operations
- Control flow (if/else, loops)
- Function definitions and calls
- Basic data types (int, float, char, etc.)

## Example

```c
// example.c
int main() {
    int x = 5;
    int y = 10;
    printf("%d\n", x + y);
    return 0;
}
```



