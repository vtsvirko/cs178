#runCount3s:   countThrees.o readInt32BitLE.o
#	g++ countThrees.o readInt32BitLE.o -o runCount3s

#Count3s: countThrees.c readInt32BitLE.c readInt32BitLE.h
#	g++ -c countThrees.c readInt32BitLE.c

#clean: rm*.o 

#OUT = Count3s
#CC = gcc
#CFILES := $(wildcard *.c)

#$(OUT):
#	$(CC) -o $(OUT) $(CFILES)

#runCount3s:
#	./$(OUT)

Count3s: countThrees.c readInt32BitLE.h readInt32BitLE.c
	gcc -o Count3s countThrees.c readInt32BitLE.c
runCount3s:
	./Count3s
