all: client 

client : client.o
	cc -o client client.o -Wall

client.o : client.c client.h
	cc -c client.c -Wall

clean :
	rm client client.o