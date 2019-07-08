#First Makefile ever, don't blame me
export PATH := bin:$(PATH)

helloworld: main.o
	gcc -o helloworld src/main.o
main.o: src/main.c
	gcc -c src/main.c -o src/main.o
clean:
	rm -f src/*.o helloworld
test:
	@echo $$PATH
install:
	cp helloworld /usr/bin/
remove:
	rm /usr/bin/helloworld
