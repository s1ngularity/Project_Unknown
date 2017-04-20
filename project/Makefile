# makefile for test program
# variables:
COMPILER = g++
TARGET = main
SRC = src
FLAGS = -std=c++11

all:
	$(COMPILER) $(FLAGS) -I"include/interface" -I"include/model" -I"include/utils" -I"include/controller" src/**/*.cpp src/main.cpp 
	
testing:
	$(COMPILER) $(FLAGS) -I"include" -I"include/interface" -I"include/model" -I"include/utils" -I"include/controller" src/**/*.cpp test/src/*.cpp -pthread -lpthread test/src/gtest_main.a
