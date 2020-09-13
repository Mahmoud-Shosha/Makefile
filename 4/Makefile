all: run

run: main.o func1.o func2.o
	gcc main.o func1.o func2.o -o $@

main.o: main.c
	gcc -c $^ -o $@

func1.o: func1.c
	gcc -c $^ -o $@

func2.o: func2.c
	gcc -c $^ -o $@
	

clean:
	rm -f *.o run