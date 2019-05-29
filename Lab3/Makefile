
# TODO: add targets to compile Stack.c

#Make an executable 
Stack: Stack.o
	gcc -Wall -Wextra -o Stack Stack.c
#compile the Stack.o
Stack.o: 
	gcc -Wall -Wextra -c Stack.c

# TODO: add a target for each .input file in the Data directory to run the compiled Stack program with the tests in ./Data
test1: Stack Data/test1.input 
	./Stack < Data/test1.input

test2: Stack Data/test2.input 
	./Stack < Data/test2.input

test3: Stack Data/test3.input 
	./Stack < Data/test3.input
# TODO: add a target that can run all the tests above.
test: test1 test2 test3