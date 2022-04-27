---
layout: post
title:  "Centroids"
date:   2022-04-25 19:09:35 -0500
categories: Engineering
visible: 1
---

# Centroids
## Mon-Mar-28-2022
#engineering

### Centroid Basics
- Centroids are the center of gravity/the center of mass of an object.
- A centroid will be graphically represented by $\oplus$ and will be represented in coordinates by $(\bar{x},\bar{y})$
- The centroid is the place where the object will feel the point of applied force due to gravity
- an object will be in a state of equilibrium if balanced on the centroid
- centroids are used in both [[Intro to Statics]] and [[Rigid Body Statics]] for theoretical calculations regarding the interactions of forces on an object
- You can determine the centroid of a 3D object by taking a cross section view of it.

### Centroid Location for Simple Geometry
On a symmetrical object the centroid will be on the line of symmetry
	- If the shape has ONE line of symmetry then the centroid will be somewhere on the line
	- If the shape has TWO OR MORE lines of symmetry then the centroid will be where the intersections of those lines of symmetry are

##### Square/Rectangle
The centroid on a square or rectangle can be found through

$\Large\bar{x} = \frac{base}{2}$

and

$\Large\bar{y} = \frac{height}{2}$

##### Right Triangle
The centroid of a right triangle can be located by:

$$\Large\bar{x} = \frac{base}{3}$$

and

$$\Large\bar{y} = \frac{height}{3}$$

##### Semicircle
The centroid of a semicircle will be located

$$\Large\frac{4r}{3\pi}$$

units away from the line of symmetry

##### Other Simple Geometries
More simple centroids can be found on the internet but a good resource is this. [CENTROIDS](https://calcresource.com/centroids-list.html)

### Centroid Location on Complex Shapes
##### Equations to Find Complex Centroids
$$\Large\bar{x} = \frac{\Sigma\left(\bar{x}_iA_i\right)}{\Sigma A_i}$$

$$\Large\bar{y} = \frac{\Sigma\left(\bar{y}_iA_i\right)}{\Sigma A_i}$$

$$\Large\bar{z} = \frac{\Sigma\left(\bar{z}_iA_i\right)}{\Sigma A_i}$$

##### Steps to Find the Centroid of a Complex Shape
1. Divide your complex shape into smaller simpler shapes
2. Determine your referance axis
3. Calculate the area of each simple shape
4. Calculate the centroid of each simple shape [[Centroids#Centroid Location for Simple Geometry]]
5. Determine the distance of the centroids of the simple shapes from your reference axis (these values will be your $\bar{x}$ and $\bar{y}$)
6. Multiply each simple shapes area by its distance from centroid to reference axis (make sure you keep x and y axis separate)
7. Add together all of the products, this value is the top of your numerator
8. Sum all of the areas together, this is the denominator
9. Divide all the summed products of centroids and area by the summed area for each axis, and that is your centroid coordinates

##### Random Facts
Most common structural elements (I-Beam, L-Beam, C-Beam) can be broken down into smaller simpler shapes to aid in finding the centroid.
