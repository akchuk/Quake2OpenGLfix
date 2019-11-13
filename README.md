# Quake2OpenGLfix
Fixes crash on Windows 10 when running Quake 2 in OpenGL instead of Software Renderer

Apparently some old OpenGL code is broken in Quake 2 and changing "%s" to "%p" appears to have fixed it.

This code is only for ref_gl.dll so you shouldn't need the full Quake 2 (3.21) source code.

Hope this helps people with Quake 2 crashing on Windows 10!
