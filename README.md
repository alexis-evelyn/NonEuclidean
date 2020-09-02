# NonEuclidean
A NonEuclidean rendering engine for Windows, written in C++ OpenGL.
To see what this code is about, check out this video:
https://youtu.be/kEB11PQ9Eo8

## Source Code Dependencies
Add glew-2.1.0 to the main directory

## Compile Help
Glew 2.1.0 can be found at https://github.com/nigels-com/glew

For OSX Glew Compile
```
cd auto
make
cd ../build
cmake ./cmake
make -j4
```

This game requires Windows.h, so it cannot work on anything other than Windows without modification

For This Game Compile
```
cd NonEuclidean
g++ -std=c++11 *.cpp
```

More to come in the future if I get past the Windows.h requirement in the future.

## Controls
* **Mouse** - Look around
* **AWSD** - Movement
* **1 - 7** - Switch between different demo rooms
* **Alt + Enter** - Toggle Fullscreen
* **Esc** - Exit demo
