# Open GL Q3 BSP Renderer

This project was started as a way of getting back up to speed with OpenGL. It 
is written in C++.

It uses PhysicsFS (https://icculus.org/physfs/) to handle file system requirements 
and IMGUI for interface purposes.

It requires the following libraries:

- SOIL2 https://github.com/SpartanJ/SOIL2/
- GLEW (2.1.0) http://glew.sourceforge.net/
- GLFW (3.3.2) https://github.com/brackeen/glfm
- GLM https://github.com/g-truc/glm

TODO:

- [ ] Allow specifying of path to Q3 data files
- [ ] Provide map selection method
- [ ] Render skyboxes
- [ ] Generate texture atlases and update UV coordinates for vertices
