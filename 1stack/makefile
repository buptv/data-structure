CXX = g++
CXXFLAGS = -g -I. -Wall
SRCS = main.cpp stack.cpp
OBJECTS = $(SRCS:%.cpp=%.o)
TARGETS = $(SRCS:%.cpp=%)
MAIN = main

obj : $(TARGETS)
	@for target in $(TARGETS); \
	do                        \
	$(CXX) $(CXXFLAGS) -c $$target.cpp; \
	done;\
	$(CXX) $(CXXFLAGS) -o $(MAIN) $(OBJECTS)	
clean:
	-rm -f $(TARGETS) $(OBJECTS)