To create synthesis images (when doing ray tracing, for example), potential intersection points between light rays and scene objects (here cylinders, spheres and cones) must be computed. 
This is exactly what this project is about.

To do so, I need to write a 3 dimensional equation of the considered surface, and inject into it the equa-tion of the straight line representing the light ray. 

I’ll get a quadratic equation, with 0, 1, 2 or an infinite number of solutions that will give me the intersection points coordinates. The straight line is defined by the coordinates of a point by which it passes through and the coordinates of a parallel vector.

O being the origin of the coordinate system, and X,Y and Z the axis, the surfaces that must be handled in this project are:

•O-centered spheres,
•Cylinders of revolution around Z axis,
•Cones of revolution around Z axis whose apex is O.
