CC=g++
CFLAGS=-g -Wall -pedantic -m32 -I../include/

all: hdd.o pentry.o mbr.o ext2fs.o

hdd.o: hdd.cpp
	$(CC) $(CFLAGS) -c -o $@ $^
	
pentry.o: pentry.cpp
	$(CC) $(CFLAGS) -c -o $@ $^

mbr.o: mbr.cpp
	$(CC) $(CFLAGS) -c -o $@ $^

ext2fs.o: ext2fs.cpp
	$(CC) $(CFLAGS) -c -o $@ $^

clean:
	rm -rf *.o