
CC = gcc

# Executables
ex1 = process_creation
ex5 = output_program
ex6 = simple_program


src1 = process_creation.c
src5 = file1.c file2.c
src6 = simple_program.c

all: $(ex1) $(ex5) $(ex6)

$(ex1): $(src1)
	$(CC) $(src1) -o $(ex1)


$(ex5): $(src5)
	$(CC) $(src5) -o $(ex5)


$(ex6): $(src6)
	$(CC) $(src6) -o $(ex6)

