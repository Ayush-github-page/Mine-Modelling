# Mine-Modelling
An AutoCAD made 3D mine comprising orebody, decline, drives and cross-cuts rendering a realistic mine 
Name: Ayush Tiwari | Roll no. 21MI31010 | Documentation of 'Mine Modeling' Project for CDC verification

Objective:
To design a mine and all its associated features such as Decline, drives, cross-cuts, essentially meaning a
working mine's entire features, provided with initial edge points of ore body.
At last providing with all the extracted ore body's volume and length details.
(All those information being available in excel format in GitHub link provided below)

Process:

All of the work involves and is based on CAD software: AutoCAD

Provided with the initial 2D edge points of ore body at different levels (depths), as in image 1 (and also
available on GitHub), an ore body is to be constructed by joining the edge points using spline.

When we have the closed edge boundary of ore body at three different levels, the edges are lofted to form
a 3D ore body.

Following it, is to form the decline:
A straight line having at end point a semi-circle. This unit keeps repeating till we have reached
the bottom of the orebody. Then, the whole of the segments are joined together and lofted in the
shape of saw-horse along the entire segment.

Now the part of drives:
a spline is to be created following ore body shape, along the periphery of ore body and lofted by a
rectangle shape to entire length of spline.
This is to be repeated at three levels of depth: 120m, 60m, 0m.

For the cross-cuts part, it was simpler:
Simply, cuboid shaped surface were to be attached to the to drive ends

For the extraction cross-cuts part too,
cuboid shaped surface inclined at 60deg to horizontal were to the attached to sides of cross-cuts

For making of stopes, shapes of stope were formed and sliced from the ore body giving both the left out
and extracted part.


Outcome: A 3D mine with all the features of ore body, decline, cross-cuts, extraction cross-cuts and stopes.
