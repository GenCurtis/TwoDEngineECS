# TwoDEngine 3.5
This is a research oriented two-dimensional game engine. The original TwoDEngine was writtne in C#. This version is completely re-written in F# and is intended for teaching and research into functional programming and .NET as platform for game development.
It is currently in use as a teaching and research tool at Purdue University

## Status
A fully functional version has been released along with an example game (Asteroids)

## System Architecture
The engine uses the FSFramework library to load and resolve references to plugins at run-time.
All game engine functionality is in plugins. Currently provided plugins support:
* 2D Graphics including image drawing and tranforms.
* USB Input from keyboards, mice and game controllers
* Bitfont (Anglecode) text rendering including kerning
* Simple collision detectiuon using bounding circles
* 

## Research and Results
This version is deliberately non-optimized. 
Despite that, it reachs a 4 fps frame rate with 10,000 moving and rotating sprites.

Further research will invovle tuning, execution parallelization and extended functionality

## Future expansion
* Experimental exapndable scene graph
* Full 2D Physics engine with circle and AABB bounding volumes
* Sound support
* Porting to platforms besides Windows 

