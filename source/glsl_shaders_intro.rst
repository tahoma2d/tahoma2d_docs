.. _GLSL_SHADERS_INTRO:

Intro To Shaders
===========================================

Tahoma2D features a flexible and powerful usage of OpenGL with your GPU using a C like shading language called glsl. This is not meant to be a full tutorial on linear algebra nor how opengl works, you can refer to sites such as `The book of shaders <https://thebookofshaders.com/>`_, `Learn OpenGL <https://learnopengl.com/>`_, as well as the `official spec <https://registry.khronos.org/OpenGL/specs/gl/GLSLangSpec.4.60.pdf>`_ for GLSL.

OpenGL Introduction
-----------------------
OpenGL is an API for rendering graphics through your GPU. It used to have a very complex and inflexible fixed-function pipeline where you had to do to it all directly, but these days you just need to use shaders.

.. OpenGL Images

.. image:: _static/glsl_shaders_intro/RenderingPipeline.png
   :width: 500
   :alt: Pipeline

All you need to be concerned about are Vertex and Fragment shaders. The depth of OpenGL is rather limited to the basics such as affine transformations because Tahoma2D is strictly 2D, not 3D.


How Tahoma2D Uses GLSL
-----------------------
There are a few terms to be familiar with.

#. World Space, the entire screen itself.
#. Output Space which is anything that is outputed onto the canvas. If it uses fx, it has a boundary box surrounding it.
#. Input space, what you input to a vfx node such as a level.


outputToWorld would be placing the output boundaries onto the world space.

First the ports vert is calculated because it needs to know input. Then is the bbox vert. Lastly is the frag shader.

You are NOT supposed to return anything with the main function. All you need to worry about is filling in variables its going to look for.

Example
----------------------
Add later.
