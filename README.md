# 3D Prinint Support Density Analysis

## Background
When transform CAD design into actual part, 3D printing is one of the fastest options. <br>
But when it come to the strong, light-weight and high chemical resistance, titanium is well-known in this area. <br>

It is also best in biocompatibility, which make it an ideal materials for medical applications such as implant device. <br>
By the way, titatnium is difficult metal to work with machining method due to its low thermal conductivity. <br>
Which mean all the heat generated during machining process will be stored in the machining tool. <br>
Wear rate would be accerelated.

With all above reason. 3D Printing will be considered as one of the best method to fabricate titanium part. <br>
One issue when perform 3D printing is "Support Design", if support point have low density in some specific point it can make our part will be failed during printing process. 


## Data Set
- 3D support point in 3D printing part in X, Y, Z cartesian coordinate.

## Objective
- Finding anormaly/ noise in 3D support points by unsupervised algorithm
  - Density Based Clustering (DBSCAN)
