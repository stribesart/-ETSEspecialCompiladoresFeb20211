# parte del makefile
calculadora:	AnalizadorLexico.l AnalizadorSintactico.y
		        bison -d AnalizadorSintactico.y
		        flex AnalizadorLexico.l
		        gcc AnalizadorSintactico.tab.c lex.yy.c -lfl
