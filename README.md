# Simple-make v1.0
This is a simple utility program which is made to be used like a makefile

COMMANDS:

COMP: Specify the name of the compiler to be used
FLAGS: Supply various compiler flags
LIBS: Variuos libraries to be linked
LPATH: Path to non standard libraries 
IPATH: Path to non standard header files
SRC: Specify the source files to be compiled
OUT: The filename of the output produced can be specifed with this option

INSTALLATION:(Under Linux)

1. Make sure you have python 3 installed
2. Edit the top line of the source file pointing to the path where you have python installed


USAGE:

1. smake 

This will try to find the file make.conf that it will process

2. smake filename

This will try to find the file 'filename' that it will process
