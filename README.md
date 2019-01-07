# Fluidos para TD y GLSL

original CUDA

A lightweight 2d Semi-Lagrangian fluid solver for TouchDesigner. It features vorticity confinement, temperature, buoyancy, and obstacles.

The repo has a .toe project file and a .tox component file. The project file shows examples of impulses and obstacles: holding 1, 2, and 3 on the keyboard will add velocity, density, and temperature at the mouse position. The tox is just the core simulation component with inputs and outputs for the advection of velocity, density/temperature, and RGBA color fields.

I have added the shaders as separate files for easy editing and versioning, though they are not required to run either the .toe or .tox.


#### Licensing
touchFluid code is released under the [MIT License](https://github.com/kamindustries/touchFluid/blob/master/LICENSE).
