# Game Checkers

## Idea

Welcome to our checkers game project made in C++! This program offers a fun and interactive experience, allowing players to compete in a classic checkers game. The implementation is carried out using the C++ programming language, with a graphical interface (GraPic) for a more immersive user experience.
Caractéristiques clés :

    - Graphical Display: The game is made visually attractive thanks to a simple and neat graphical interface, providing players with an enjoyable gaming experience.
    
    - Distinct Players: Players are distinguished by colors, with blue pawns on one side and yellow pawns on the other. This visual distinction makes the board easier to understand and adds a strategic dimension to the game.
    
    - Ease of use: The keys are extremely simple, left click to remove a pawn and right click to place it on the desired square.

![image](image/Checker1.jpg)
![image](image/Checker2.jpg)

However, there are no constraints on the movements, which means that they must be placed correctly, even as in the real game!

# GrAPiC 

## Starting

Linux, Windows and Mac instruction :

http://licence-info.univ-lyon1.fr/grapic

## Introduction

GrAPiC is a small, easy-to-use framework to add graphical functionalities to your C/C++ code. 
Its main goal is to provide easy graphical functions to be used in introduction courses of algorithm and programming in C/C++. 
It is based on SDL2 but to use it you need to know only few very simples functions. 
The Grapic archive comes with the needed SDL part, you do not have to install SDL. Just unzip and enjoy ! 

## Starting

Compiling from the github (which is not the standard way).

* On Linux you need to install:
- g++
- doxygen
- zip
- lib-sdl2-dev lib-sdl2 sd2_image... sdl2_ttf...

1. sudo apt install g++ premake4 zip doxygen libsdl2-dev libsdl2-mixer-dev libsdl2-image-dev
2. make premake
3. make
(4. script/make_linux_test.sh): to test the archive doc/download/grapic-linux.tgz
(5. script/make_web.sh): to create the zip files in doc/download or to sync everything to the webpage (need passwd).


* On windows
0. Install CB 20
1. run premake-cb20.bat to generate the projects files    or     run premake-lifami.bat to generate lifami projects 
2. open build/windows-cb20/grapic.workspace

## Best way to make a projet in windows

(windows): 
 - Open build/windows-cb20/grapic.workspace in CodeBlocks
 - In the left part (Management) of the logiciel, double clic in the projet of yours choice (it's those in /apps)
 - Finally clic in the green arrow in the top of the screen

![OpenFolder](image/OpenFolder.jpg)
![OpenFile](image/OpenFile.jpg)

## Put your new project in GraPic

Add your directory with your cpp files in "apps" and add the path in "premake4".

