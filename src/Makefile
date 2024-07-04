CXXFLAGS =	-O2 -g -Wall 

OBJS =		ftail.o

LIBS =

TARGET =	ftail

$(TARGET):	$(OBJS)
	$(CXX) -o $(TARGET) $(OBJS) $(LIBS)
	strip $(TARGET)

all:	$(TARGET)

clean:
	rm -f $(OBJS) $(TARGET)
