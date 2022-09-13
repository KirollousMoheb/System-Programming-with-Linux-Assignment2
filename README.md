# System-Programming-with-Linux-Assignment2
## Static Linking Commands
### $ gcc -c *.c
### $ ar -rs mylib.a fact.o fib.o rand.o
### $ gcc -c  main.c
### $ gcc -o myexe main.o ./mylib.a
### $ ./myexe

## Dynamic Linking Commands

### $ gcc -shared -fpic -o mylib.so fib.c rand.c fact.c
### $ gcc -o myexe main.c ./mylib.so
### $ ./myexe

