CFLAGS=-O2 -g -Wall
CC=gcc
PROGNAME=dtbTool-lineage

all: $(PROGNAME)

%.o: %.c
	$(CC) $(CFLAGS) -c $<

$(PROGNAME): dtbtool-lineage.o
	$(CC) -g -o $(PROGNAME) dtbtool-lineage.o

clean:
	rm -f *.o $(PROGNAME)
