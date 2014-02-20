SDL2 Pong
==========

Simple implementation of pong using SDL2.0

This is a single player game with the second paddle being controlled by an *extremely* simple AI.

![Pong on Kubuntu](img/sdl_pong2.png)

Controls
--------

* Up - move up
* Down - move down
* Escape - Exit

Controller Support
------------------
The game has very basic controller support. You can use the up and down buttons to move your paddle. I also introduced some basic haptic feedback when the ball hits a paddle or one of the players score a point.

Requirements
------------
You require the SDL2.0 development libraries along with the following extensions:
* SDL_ttf
* SDL_image

Building
--------
Simply Navigate to the src directory and type `make`

Executing
---------
Run `pong.exe`

Notes
-----
This was tested on a Linux machine (64bit) but should also work and compile on Windows and Mac OSX given the right development tools.
