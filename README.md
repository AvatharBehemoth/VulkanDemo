#Vulkan Graphics Engine
## https://www.youtube.com/watch?v=dpxb04QWsyI

### Description:
A simple graphics engine, which renders a model. It features a user controlable cameraviewpoint, with simple controls.
Requirements
The requirements were quite heavy. 
I have had to learn C++ which is, in many ways, quite different from C.
I had no prior experience with C before starting CS50. 
Nor have i had experience with C++ which is very much more complicated than C. 
The understanding of some of the functions built onto variables for instance was challenging.
C++ has different concepts than C. It is more expanded. As well as different in key areas.

I have had to learn some GLSL (SPIR V) for the shader instructions.
Some math knowledge, which i didnt have, was required, in order to compute various variables which define cameraviewpoint render vertices and texture on the model. 
Knowledge about SDL2 as well as about several libraries: GLM, TinyObjectloader, stb is absolutely necessary.
Ive also had to aquire a working knowledge of Blender, as i have had to create the model in Blender.
Blender is a complicated software suite with many features. But also many different versions which have differences from each other, not only in features but also in where and how these can be found and used.
All in all a daunting task, and i feel i have only scratched the surface.
The largest practical problems were: how to master the GLM commands so as to succesfully implement a movable camera. 
I have struggled severely with that, making the model or a point near the model the focus of the camera. 
This was very frustrating of course. So much so that frequent pauzes were necessary, and more knowlegde aquisition was done. 
So in that sense it was not an adaptation but adding new features. 

Timeframe
I have been working on aquiring the necessary skills since late august. 
First working on tutorials. 
Late september i started on the final project. 
Which is basically a very thorough adaptation of the tutorial from vulkan-tutorial.com.
The parts which have remained unchanged are the standard necessary Vulkan initialisation parts as well as the parts describing the buffers and binding etc (basically the housekeeping part).
Implementation
Since i used SDL2 some of the housekeeping/initialisation of Vulkan was automated. 
SDL2 also helped in creating the user input (wasd keys for movement of the camera).
But ive had to implement a camera for instance.
Also notice how this C++ file is written more like a C language program it does not use classes or namespaces. 
I have as yet not found a good learning resource to master those subjects. This due to being focussed on the graphics engine. 
The intent was at first to make this a small game. However Vulkan does not, for instance, generate text natively. 
Also making a "cockpit" would require a texture, which needs to be done in Blender. I am still working out how that is done.  