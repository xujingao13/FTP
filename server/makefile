
all: server

server : server.o
	cc -o server server.o -Wall

server.o : server.c server.h
	cc -c server.c -Wall

clean :
	rm server server.o