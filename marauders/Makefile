CC = g++
CFLAGS = -Wall
PROG = v2

SRCS = v2.cpp imageloader.cpp
LIBS = -lglut -lGL -lGLU

all: $(PROG)

$(PROG):	$(SRCS)
	$(CC) $(CFLAGS) -o $(PROG) $(SRCS) $(LIBS) `pkg-config --cflags --libs freealut`

clean:
	rm -f $(PROG)
