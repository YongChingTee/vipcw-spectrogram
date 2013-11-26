CC=gcc
GTKFLAGS=`pkg-config --libs --cflags gtk+-2.0`

all: receiver_bars.c
	$(CC) receiver_bars.c $(GTKFLAGS) -o receiver_bars

clean:
	rm -rf receiver
