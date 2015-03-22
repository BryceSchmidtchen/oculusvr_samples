Oculus Rift DK2 minimum OpenGL setup
================

A minimum setup application for Oculus Rift DK2 development with OpenGL and SDL2 as window manager. While the entire code could be squashed into a single file, a separate OculusVR class exists to handle all OVR initialization and processing. Along with it comes a separate ShaderManager with Shader class for cleaner shader loading. The application also handles dismissal of healt warning and provides head tracking recenter functionality at a keystroke.

![Screenshot](http://kondrak.info/images/vrcam_bb2.png?raw=true)

Usage
-----
Run <code>CameraBounds.exe</code>

Press R while "ingame" to recenter tracking position.

How to build
-------
The application was built using VS2013. It should work out of the box with SDK 0.4.4. To compile, you need to set a OCULUS_SDK environment variable which points to the root directory of your Oculus SDK.

Dependencies
-------
This project uses following external libraries:

- GLee library for extensions (c)2011 Ben Woodhouse
- stb_image library for image handling (c) Sean Barret
- SDL2 library for window/input 
