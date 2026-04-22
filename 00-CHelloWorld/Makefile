all: hello

hello: hello.c
	clang -std=c2x hello.c -o hello

run: hello
	./hello

clean:
	rm -f hello output.txt
