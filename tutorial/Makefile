CC=cc
CFLAGS=-Wall -g -I$PATH_TO_LIBMHD_INCLUDES -L$PATH_TO_LIBMHD_LIBS

all:
	$(CC) $(CFLAGS) hellobrowser.c -o hellobrowser -lmicrohttpd

clean:
	rm -f hellobrowser
