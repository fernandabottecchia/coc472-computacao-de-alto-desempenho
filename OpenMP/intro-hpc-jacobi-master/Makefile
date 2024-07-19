CC = cc
CFLAGS = -std=c99 -Wall -fopenmp
LDFLAGS = -lm

jacobi: jacobi.c
	$(CC) $(CFLAGS) -o jacobi jacobi.c $(LDFLAGS)

clean:
	rm -f jacobi
