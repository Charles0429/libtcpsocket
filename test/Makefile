all: server.test client.test

server.test:
	gcc -g -o server.test server.c ../src/socket.c

client.test:
	gcc -g -o client.test client.c ../src/socket.c

clean:
	rm -f server.test
	rm -f client.test
