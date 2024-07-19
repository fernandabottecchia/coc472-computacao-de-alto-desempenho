CC = cc
CFLAGS = -std=c99 -Wall -O3 -pg
LDFLAGS = -lm

jacobi: jacobi.c
	$(CC) $(CFLAGS) -o jacobi jacobi.c $(LDFLAGS)

clean:
	rm -f jacobi gmon.out
