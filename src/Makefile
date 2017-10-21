CFLAGS= -Wall -Os -I/usr/include
LDFLAGS=-lwiringPi -lwiringPiDev -lpthread -lm -lrt -lcrypt

all: xvcd

xvcd: gpio.o xvcd.o
	$(CC) -o $@ $^ $(CFLAGS) $(LDFLAGS)

clean:
	rm -rf *.o xvcd

