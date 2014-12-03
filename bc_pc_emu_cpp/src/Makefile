# remote git test. simply change this line.

# TODO:
# 1.
# Check is it working under linux 

## headers subdirs
IDIRS = -I. -I./sys

##CC=gcc   
##CFLAGS=-c -Wall $(IDIRS) 

CXX=g++
CXXFLAGS=-c -Wall $(IDIRS) 

LDFLAGS=
LDLIBS=

## all source subdirs for linker and compilator
VPATH = sys

EXECUTABLE := bc_pc_emu_cpp.exe

.PHONY : all clean rebuild

all : bc_pc_emu_cpp.exe

bc_pc_emu_cpp.exe : Timer.o bc_pc_emu_cpp.o 
	$(CXX) -o bc_pc_emu_cpp.exe Timer.o bc_pc_emu_cpp.o


clean : 
	rm -f *.o
	rm -f *.d
	rm -f $(EXECUTABLE)

	
rebuild: clean everything






##########################################
### working, from vario project
#
#
## remote git test. simply change this line.
#
## TODO:
## 1.
## Check is it working under linux 
#
### headers subdirs
#IDIRS = -I./comm -I./sensor -I./sys -I./timer -I./ui/display -I./ui/kbd -I./ui/sound
#
###CC=gcc   
###CFLAGS=-c -Wall $(IDIRS) 
#
#CXX=g++
#CXXFLAGS=-c -Wall $(IDIRS) 
#
#LDFLAGS=
#LDLIBS=
#
### all source subdirs for linker and compilator
#VPATH = comm sensor sys timer ui/display ui/kbd ui/sound
#
#EXECUTABLE := v_pc.exe
#
#.PHONY : all clean rebuild
#
#all : v_pc.exe
#
#v_pc.exe : CommStack.o BMP085Sensor.o Timer.o Display.o DisplaySDL.o Keybd.o Sound.o v_pc.o 
#	$(CXX) -o v_pc.exe CommStack.o BMP085Sensor.o Timer.o Display.o DisplaySDL.o Keybd.o Sound.o v_pc.o
#
#
#clean : 
#	rm -f *.o
#	rm -f *.d
#	rm -f $(EXECUTABLE)
#
#	
#rebuild: clean everything




############################################
### eclipse orig
#
#CXXFLAGS =	-O2 -g -Wall -fmessage-length=0
#
#OBJS =		bc_pc_emu_cpp.o
#
#LIBS =
#
#TARGET =	bc_pc_emu_cpp.exe
#
#$(TARGET):	$(OBJS)
#	$(CXX) -o $(TARGET) $(OBJS) $(LIBS)
#
#all:	$(TARGET)
#
#clean:
#	rm -f $(OBJS) $(TARGET)
#