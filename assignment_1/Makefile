CC=gcc
DEPS=average.h
OBJ=main.o average.o

%.o: %.c $(DEPS)
	$(CC) -c -o $@ $<

main: $(OBJ)
	$(CC) -o $@ $^
