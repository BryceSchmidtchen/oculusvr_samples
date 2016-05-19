Oculus Rift minimum OpenGL instanced rendering
================

This is a demonstration of instanced VR rendering in OpenGL. Press R during the demo to toggle between standard (one scene draw per eye) and instanced (single draw for both eyes) rendering. Contrary to other examples, this demo uses single render target for both eyes.

![Screenshot](http://kondrak.info/images/vr_minimum.png?raw=true)

Usage
-----
Run <code>InstancedRender.exe</code>

Press SPACE while "ingame" to recenter tracking position.

How to build
-------
The application was built using VS2015. To compile, you need to set a OCULUS_SDK environment variable which points to the root directory of your Oculus SDK.

Dependencies
-------
This project uses following external libraries:

- GLEW OpenGL extension library
- stb_image library for image handling (c) Sean Barret
- SDL2 library for window/input 
