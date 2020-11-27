#!/bin/bash

# Execute simple commands for generate calc file

yacc -d calc.y
lex calc.l
cc lex.yy.c y.tab.c -o calc -ll
./calc

rm calc lex.yy.c y.tab.c y.tab.h
