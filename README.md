# lexical-and-syntax-analyzer

Compile & run in the terminal:
(cd code)
- flex project.l
- bison -d project.y
- gcc -o a.out project.tab.c lex.yy.c
- ./a.out
 
For more information, read the english version of our report (**project en.pdf**).
