CC = gcc
CFLAG = -std=c11
SOURCE = HelloWorld.c
OBJ = HelloWorld.o
BIN = HelloWorld.exe

all:$(BIN)
	.\$(BIN) 
HelloWorld.exe: HelloWorld.o 
	$(CC) -Wall HelloWorld.o -o HelloWorld.exe
HelloWorld.o: HelloWorld.c
	$(CC) -c HelloWorld.c -o HelloWorld.o $(CFLAG)
clean:
	$(RM) -f HelloWorld *.o
	$(RM) -f HelloWorld *.txt
	$(RM) -f HelloWorld *.exe