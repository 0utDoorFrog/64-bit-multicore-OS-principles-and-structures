all: output.exe

a.o: a.c
	gcc -c a.c

b.o: b.c
	gcc -c b.c

output.exe: a.o b.o
	gcc -o output.exe a.o b.o