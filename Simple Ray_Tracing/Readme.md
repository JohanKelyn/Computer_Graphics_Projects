# Ray Tracing Program

This Ray Tracing Program is a compilation of different small assignments for my class in computer graphics at NYU during the Fall 2020.
In this project, I will implement a basic raytracer using C++ and use it to render spheres, planes, and triangular meshes with different projections (Orthographic or Perspective), and different shading displays. I will add more features to the ones described below to make this project more complete. For a more detailled explanation of the concepts described here, please refer to the [Computer Graphics](https://github.com/danielepanozzo/cg) repository and the book <strong>Fundamental of Computer Graphics</strong> by Steve-Marschner

## Preparing the Environment and Submission

Follow the instructions on the [general instructions page](https://github.com/danielepanozzo/cg/blob/master/RULES.md) to set up what you need to run this project locally.

## Using Eigen

Please  note that I used the external math library eigen to do all math calculations. Please see below a Getting Started](http://eigen.tuxfamily.org/dox/GettingStarted.html) page for a reference of the basic matrix operations supported.

## Features and Tasks

The points below are a the sequence of steps that I took to build this ray tracing program.

* Ray Tracing a Sphere with Parallel Projection
* Ray Tracing a Parallelogram with Parallel Projection
* Ray Tracing a Sphere with Perspective Projection
* Ray Tracing a Parallelogram with Perspective Projection
* Adding Shading Components (Ambient, Specular, and Diffuse)
* RGB components
* Field of View and Perspective Camera
* Shadow Rays
* Reflection & Refraction
* Depth of Field
* Reading External Json Files and Triangulated Meshes
* Adding AABB Trees for Better Performance

## Final Output

These are the possible outcomes, you can create with this simple ray tracing program

![](img/bunny.png?raw=true)

![](img/dragon.png?raw=true)

![](img/raytrace.png?raw=true)
