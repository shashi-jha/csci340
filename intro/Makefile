all: 	cpu mem io threads
clean:
	rm -f cpu mem io threads
cpu: cpu.c common.h
	gcc -o cpu cpu.c -Wall
mem: mem.c common.h
	gcc -o mem mem.c -Wall
io: io.c common.h
	gcc -o io io.c -Wall
threads: threads.c common.h common_threads.h
	gcc -o threads threads.c -Wall -pthread
