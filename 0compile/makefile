cc=g++
exe=main
obj=main.o one.o two.o three.o

$(exe):$(obj)
		$(cc) -o $(exe) $(obj)
main.o:main.cpp
		$(cc) -c main.cpp
one.o:one.cpp
		$(cc) -c one.cpp
two.o:two.cpp
		$(cc) -c two.cpp
three.o:three.cpp
		$(cc) -c three.cpp
clean:
		rm -rf *.o