---
layout: default
---

# Introduction
Who am I?

# Why these blogs
- to go through the same pain as students
- to have tutorials ready for students to use
- to give something back
- tutorials are never exactly what I want or what I think I need. Might as well write them myself, then, right. How hard can it be...
- Most of these tutorials, blogs come from my own meandering thoughts and ideas. There might not be any consistency or line to be discovered, other than these are the things that interest or fascinate me. 
- These blogs might help me to finish my projects, finally. To keep them up to date, to fix bugs, whatever...


[Link to another page](./another-page.html).

We offer the students a choice of 3 different topics in the first block of the second year, here at CMGT at BUas. These topics are Physics and AI, in which students focus on navigation and 2D physics, Tools in which the focus is on developing a pipeline for games, and Graphics. In the graphics track, students are tasked with writing a PBR renderer. They do this either on a Windows maching using DirectX12 or on a PS5 using Sony proprietary APIs. To guide the students in the right direction (we hope), we set up a few milestones for them across the weeks where each subsequent milestone builds on the previous one. Taking them from simple graphics applications (a clear screen), through more complicated examples (correctly displaying a GLTF scene), to PBR rendering. Extended goals include adding post processing effects and IBL to their solutions.

The following pages describe my attempts at doing the same thing, using OpenGL (x.x), DirectX 12 and Vulkan. The pages contain relevant information about the graphics side of creating these samples as well as links to the GitHub repository containing the code, assets, shaders and any other relevant files. Each of these samples stands on itself, they should work out of the box (famous last words...). Each of these are made and maintained using CLion on Windows (DX12, Vulkan, OpenGL) and Mac OS (Vulkan, OpenGL). Unfortunately, due to NDA agreements, I can't share the PS5 versions of the same samples.

All the samples can be built using CMake. You can either open the folder in CLion and work from there, or use CMake-GUI to generate Visual Studio projects for you. I will not go into the details of how to do that. Other have done that in a clear and understandable manner (LINKS).

We all stand on the shoulders of giants. I do consider myself a decent programmer, I don't consider myself a brilliant graphics programmer. I wouldn't have been able to create these samples without the help of those who came before me.

[00-framework](./_pages/00-framework.md) In order to render something to screen, we will need to set up windows, inputs, etc., etc. Here I explain a bit about the basic framework that I use for these samples. Along the way this framework will be expanded to add extra functionality.

[01-clear-screen](./_pages/01-clear-screen.md) This first sample is pretty basic. Windowing is set up, rendering contexts are set up and the screen is cleared to a single color.</br>

[02-colored-triangle](./_pages/02-colored-triangle.md) The second sample is more or less the "Hello World!" of graphics programming: the colored triangle. A single triangle where the different colors at each vertex are interpolated across the triangle.</br>

[03-lit-cube](./_pages/03-lit-cube.md) The third sample contains a single rotating cube that is lit using the Blinn-Phong lighting model.</br>

[04-texturing](./_pages/texturing.md) The fourth sample adds a single texture to the cube from the previous sample. </br>

[05-render-to-texture](./_pages/05-render-to-texture.md) In the fifth sample renders the output of the previous sample to a texture (rendertarget) before displaying that to the screen. This will eventually enable us to add a post-processing pipeline without too much effort.</br>

[06-imgui](./_pages/06-imgui.md) The sixth sample is an intermediate step and not an explicit milestone for our students. But as the samples get more and more complex, UI becomes a necessity. This sample shows how to integrate [ImGui](https://github.com/ocornut/imgui).</br>

[07-gltf-model-rendering](./_pages/07-gltf-model-rendering.md) The seventh sample shows how to render an arbitrary GLTF scene. </br>

## 08 - PBR rendering
[08-pbr-rendering](./_pages/08-pbr-rendering.md)
![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)The eight sample shows a basic PBR renderer. </br>

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

