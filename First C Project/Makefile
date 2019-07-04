#First Makefile ever, don't blame me
export PATH := bin:$(PATH)
BIN=/usr/bin/

helloworld: src/main.o src/hello.o
	gcc -o helloworld src/main.o src/hello.o
main.o: src/main.c
	gcc -c src/main.c -o src/main.o
hello.o: src/hello.c
	gcc -c src/hello.c -o src/hello.o
clean:
	rm -f src/*.o helloworld
test:
	@echo $$PATH
install:
	cp main /usr/bin/
remove:
	rm /usr/bin/helloworld
