## Simple SDL mini code
 
CC=gcc
 
CPPFLAGS= `pkg-config --cflags --libs sdl gtk+-3.0`
CFLAGS= -Wall -Wextra -Werror -std=c99 -O3
LDFLAGS=
LDLIBS= `pkg-config --libs sdl gtk+-3.0` -lSDL_image
 
SRC= OCR.c main.c
OBJ= ${SRC:.c=.o}
 
all: main
 
main: ${OBJ}
 
clean:
	rm -f *~ *.o
	rm -f main
 
# END
