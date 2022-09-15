# Future-Projects
A bunch of future projects/additions to current projects that I plan to make

## 1: RayMarchingRender
-a ray marching render with normals and shadows\
-possibly add physics and ability to do intersections with shapes and cutaways\
-start with a 2d visulaizer in java and then impliment in 3d with unity

### What is Ray Marching?
Pretty much, instead of using polygons to render 3d objects, raymarching uses signed distance functions or SDFs. 
These are mathematical functions that take a point in space and tell you how far that point is from the nearest surface of a mathematically defined shape. 
With just this information, we can evaluate what the camera should see. In essence, instead of a sphere being made up of
hundreds of polygons, we can have a sphere with infinite resolution regardless of how close to the surface we get. Using this technique, we can create 
some pretty fantastical visualizations that wouldn't be possible using traditional render methods.\
Like this:\
![example](https://user-images.githubusercontent.com/85074410/188332624-40669a16-1a81-44f8-bad2-eb217fc77fad.gif)

### What is the diffrence between Raymarching, Raycasting, Raytracing and Rasterization?
#### Raytracing Vs. Raycasting:
Ray casting is distinct from ray tracing, with ray casting being a rendering algorithm which would never recursively trace secondary rays, while ray tracing is capable of doing so. Ray casting is also simple to use compared to other rendering algorithms such as ray tracing.\
![slide007](https://user-images.githubusercontent.com/85074410/188332936-88ed2316-86b2-4ded-afe6-ee38a25ad89b.jpg)
#### Raytracing Vs. Rasterization:
![rasterization-vs-raytracing-l](https://user-images.githubusercontent.com/85074410/188333031-95518c1e-71d3-4f6a-b205-9a86fba375a1.jpg)
#### Raytracing Vs. Raymarching:
<img width="464" alt="Diagram2" src="https://user-images.githubusercontent.com/85074410/188333087-af8e2111-e7ee-480c-a418-0de3274e8514.png">


### Great Resources(Basic to Advanced):
-[Coding Adventure: Ray Marching](https://www.youtube.com/watch?v=Cp5WWtMoeKg)  Sebastian Lague\
-[Ray Marching for Dummies!](https://www.youtube.com/watch?v=BNZtUB7yhX4)   SimonDev\
-[Ray Marching for Dummies!](https://www.youtube.com/watch?v=PGtv-dBi2wE&t=1602s) The Art of Code\
-[Ray Marching Math](https://michaelwalczyk.com/blog-ray-marching.html) Michael Walczyk\

## 2: Create Physics Based Animation Editor Tool
-discription comming soon

## 3: Create producural music generation using AbeltonLive and Unity
-discription comming soon

## 4: Create a auto-login system for students at Milton Academy
-discription comming soon

## 5: Improve Projection Perspective Project
-make it work in a simulated enviorment\
-make it work on non planar surfaces\
-allow camera to be at diffrent angles\
-allow projector to be at diffrent angles

https://user-images.githubusercontent.com/85074410/163735232-982fe0c4-acb8-48e7-9a14-53c3ca268162.mp4 


