# compiler-design-grammar-implementation
CDGI runs a mini-C Compiler whose grammar is designed with Lex and Yacc.
To run the same on a Linux terminal, follow the steps:
1) Perform Lexical Analysis:
```
$lex tokens.l
```
2) Implementation of Grammar:
```
$yacc grammar.y
```
3) Compilation:
```
$gcc y.tab.c -ll -ly
```
4) Testing Output:
```
$./a.out <filename>
```
