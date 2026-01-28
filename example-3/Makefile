TARGET = program
SRC = Kazino-Royal.cpp
OBJ = Kazino-Royal.o
CXX = g++
CXXFLAGS = -Wall -std=c++11

$(TARGET): $(OBJ)
    $(CXX) $(CXXFLAGS) -o $(TARGET) $(OBJ)

$(OBJ): $(SRC)
    $(CXX) $(CXXFLAGS) -c $(SRC) -o $(OBJ)

clean:
    rm -f $(OBJ) $(TARGET)

.PHONY: clean
