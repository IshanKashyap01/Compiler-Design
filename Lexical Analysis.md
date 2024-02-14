# Lexical Analysis

- character stream -> lexical analysis -> token stream

```C
// Following is a lexically correct code
int x = 10; // int, x, =, 10 and ;
int main()  // main, ( and )
{           // this is a token
    Int y;  // y and Int
}           // this is also a token
```

- If any of these tokens are invalid, it will report errors to the error handler

- Each token will be entered in the symbol table along with their information like
token name, string, line etc.

## Functionality of Lexical Analysis

1. Scans every character of the program/file

2. Recognises spaces, new lines, comments and tokens

3. Produces tokens and lexical errors if any

4. Stores some information about identifiers in the symbol table

5. Deletes spaces, new lines and comments, and stores tokens

6. Groups characters into tokens using the **Longest Prefix Rule** (Maximum Munch
Rule)

## Tokens

1. Identifiers

2. Keywords

3. Operators

4. Constants

5. Punctuation symbols

## Longest Prefix Rule

- The longest sequence of characters that form a valid string, is called a token

- For ex. ```main``` is a single token but ```()``` has two tokens

- ```+++``` is resolved into two tokens as ```++ +```
