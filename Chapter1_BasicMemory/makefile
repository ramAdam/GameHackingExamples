#g++ -o main game-BasicMem.cpp -I/usr/local/include -L/usr/local/lib -lallegro_main -lallegro -lallegro_dialog -lallegro_font -lallegro_ttf -lallegro_primitives


LIBS = -lallegro_main -lallegro -lallegro_dialog -lallegro_font -lallegro_ttf -lallegro_primitives

LIB_DIR = "-L/usr/local/lib"
INCLUDE_DIR = "-I/usr/local/include"
#CFLAGS = -I$(INCLUDE_DIR)
SOURCE = game-BasicMem.cpp
EXE = game-BasicMem 

$(EXE): $(SOURCE)
	g++ $(SOURCE) $(INCLUDE_DIR) $(LIB_DIR) $(LIBS) -o $@
