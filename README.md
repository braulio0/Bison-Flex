# Flex, Bison, Yacc Sample Code

## Compile project

```bash
	flex -l test.l
	bison -dv test.y 
	gcc -o test test.tab.c lex.yy.c -lfl
```


## Run build 

```bash
./test
```

