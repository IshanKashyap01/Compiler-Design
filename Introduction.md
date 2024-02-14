# Introduction to Compiler Design

- High level code -> preprocessor -> Compiler -> assembly code -> assembler ->
machine code -> loader & linker

## Phases of Compiler

1. Lexical Analysis (high-level code)

2. Syntax Analysis (token stream)

3. Semantic Analysis (parser/syntax tree)

4. ICG (annotated parser tree)

5. Intermediate code optimization (intermediate code)

6. Code generation (intermediate code)

7. Assembly code optimization (assembly code)

## Error Handling

- Every phase will report its errors to the error handler and interact with the
symbol table

- Following are the types of errors:

1. Lexical (invalid sequence of characters)

2. Syntax

3. Semantic (undeclared variables, type casting errors etc.)
