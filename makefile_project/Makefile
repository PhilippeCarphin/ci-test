
all: main

main.o:main.c
	gcc -c $< -o $@

main:main.o
	gcc $^ -o $@

test:main
	./$<
