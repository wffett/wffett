bin/main: bin/main.o bin/game.o
	g++ -g -o bin/main bin/main.o bin/game.o -std=c++11 -Wall -pedantic -lncurses

bin/main.o: src/main.cpp
	mkdir -p bin
	g++ -g -c -o bin/main.o src/main.cpp
bin/game.o: src/game.cpp
	mkdir -p bin
	g++ -g -c -o bin/game.o src/game.cpp


clean:
	rm -rf bin/
