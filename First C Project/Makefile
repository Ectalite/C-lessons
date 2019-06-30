#First Makefile ever, don't blame me
export PATH := bin:$(PATH)
BIN=/usr/bin/

prog: src/main.o
	gcc -o main src/main.o
main.o: src/main.c
	gcc -c src/main.c -o src/main.o
clean:
	rm -f src/*.o main
test:
	@echo $$PATH
install:
	cp main /usr/bin/
remove:
	rm /usr/bin/main
