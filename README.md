To compile program use gcc instruction:

g++ -pie -std=c++20 -o task ./src/Main.cpp ./src/ComputerClub.cpp

To build with cmake use:

mkdir build
cd build
cmake ..
cmake --build .