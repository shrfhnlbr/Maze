# The Maze

The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!

The Maze was written in C using the SDL2 library. Development was performed using Ubuntu 20.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~20.04) 4.8.4

### About SDL2 

Simple DirectMedia Layer is a cross-platform development library designed to provide low-level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D.

## Installation 
```sh
git clone https://github.com/shrfhnlbr/Maze.git
```
## Usage 
* Execute ./maze or type make run 
* Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
* Use right and left arrow keys to turn the camera around (keys d and a serve the same function)

## Compilation
```sh
gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```

## Demo
(https://www.youtube.com/watch?v=1vjDGEZQohk)

![Screenshot (2)](https://github.com/shrfhnlbr/Maze/assets/113669428/6b9c79e7-113b-4a1b-ba76-c32a86130e00)

## NOTE:
The maze is still under development. Any contributions are greatly welcome.
