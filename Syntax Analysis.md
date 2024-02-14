# Syntax Analysis

- Token stream -> parser -> parser tree (syntax tree)

- Top-down parser:
    1. LL(1) parser

- Bottom-up parser:
    1. LR(0)
    2. SLR
    3. LALR
    4. CLR/LR(1)
    5. Operator Precedence

- A parser uses a stack and a parser table apart from the symbol table

## Top-down Parser (LL(1) Parser)

- It requires an LL(1) table with LL(1) grammar.
