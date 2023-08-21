

Supported features:
~~~~~~~~~~~~~~~~~~~

NxN Matrices:
'''''''''''''

-  Transpose
-  Scale
-  NxN Matrix Multiplication
-  NxN Matrix \* N Dimensions Vector Multiplication
-  4x4 Perspective Projection Matrix
-  lookAt 4x4 Matrix
-  Translation (3x3, 4x4)
-  Rotation (2x2, 3x3, 4x4)
-  Shear (2x2, 3x3, 4x4)
-  Project
-  Unproject
-  Orthographic Projection
-  Perspective Projection
-  lookAt 4x4 matrix
-  Determinant 2x2, 3x3, 4x4
-  Inverse 2x2, 3x3, 4x4

N Dimensions Vectors:
'''''''''''''''''''''

-  Dot Product
-  Cross Product (3D, No 7D as of now)
-  2D get angle of vector
-  2D -90 degree rotation
-  2D +90 degree rotation
-  Refraction
-  Reflection
-  Negate
-  Normalize
-  Linear Interpolation
-  Max Vector/Scalar
-  Min Vector/Scalar
-  Clamp
-  Transform 
-  Barycentric 
-  isInSameDirection test
-  isInOppositeDirection test
-  3D Vector swizzling, similar to GLSL
-  3D Vector idenitities

Quaternions:
''''''''''''

-  Normalize
-  Dot Product
-  Rotation
-  Conjugate
-  Inverse
-  Negate
-  Rotate X, Y, Z
-  Arbitary Axis Rotation
-  From angle Rotation
-  To Rotation Matrix (4x4)
-  From Rotation Matrix (4x4)
-  Cross Product
-  Vector3D, Scalar Multiplication
-  Logarithm
-  Exponential
-  Power
-  Liner Interpolation (LERP)
-  Spherical Interpolation (SLERP)
-  Spherical Interpoliaton No Invert
-  Quaternion Splines (SQUAD)

Plane:
''''''

-  Define using

   -  3 Vectors
   -  Point and Normal
   -  Manual input

-  Dot Product
-  Normalize
-  Best fit normal and D value
-  Distance from plane to a point
-  Point location
-  Output
-  Flip

Ray:
''''

-  Rotate using Matrix
-  Rotate using Quaternions
-  Translate
-  Output

Legendre Polynomial (Experimental, not complete):
'''''''''''''''''''''''''''''''''''''''''''''''''

-  For spherical harmonics
-  (l - m)PML(x) = x(2l - 1)PML-1(x
-  Irradiance maps
