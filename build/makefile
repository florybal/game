#OBJS specifies which files to compile as part of the project
OBJS = ../src/*

#OBJ_NAME specifies the name of our exectuable
OBJ_NAME = game

INCLUDE_DIR = -I ./../SDL2/include

LIBRARY_DIR = -L ./../SDL2/lib

#This is the target that compiles our executable
all :
	g++ $(OBJS) $(INCLUDE_DIR) $(LIBRARY_DIR) -Wall -w -W -mwindows -lmingw32 -lSDL2main -lSDL2 -lSDL2_image -o $(OBJ_NAME)

clean :
	rm -f $(OBJ_NAME).exe 

