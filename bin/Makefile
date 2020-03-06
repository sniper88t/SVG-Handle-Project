INC = /root/Dev/svg/include
XML_PATH = /usr/include/libxml2

# Standard common makefile
main: main.o
	gcc -o main main.o libsvgparse.so -lxml2 -lm

main.o: main.c
	gcc -c -fpic main.c -I$(INC) -I$(XML_PATH) -o main.o

clean:
	rm all main.o