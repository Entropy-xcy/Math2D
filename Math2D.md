# Math 2D

## Overview
* 10.1 Curves Defined by parametric Equations

* 10.2 Calculus with Parametric Curves

* 10.3 Polar Coordinates

* 12.1 Three-Dimensional Coordinate System

* 12.2 Vectors

* 12.3 The Dot Product

* 12.4 The Cross Product

* 12.5 Equations of Lines and Planes

* 12.6 Cylinders and Quadric Surfaces

* 13.1 Vector Functions and Space Curves

* 13.2 Derivatives and Integrals of Vector Functions

* 13.3 Arc length and Curvature

* 13.4 Motion in Space: Velocity and Acceleration

* 14.1 Functions of Several Variables

* 14.2 Limits and Continuity

* 14.3 Partial Derivatives

* 14.4 Tangent Planes and Linear Approximation

* 14.5 The Chain Rule

* 14.6 Directional Derivatives and the Gradient Vector

* 14.7 Maximum and Minimum Values

* 14.8 Lagrange Multipliers

* 15.1 Double Integrals over Rectangles

* 15.2 Double Integrals over General Region

* 15.3 Double Integrals in Polar Coordinates

## Prerequisite Knowledge

### Derivatives

- $(fg)'=f'g+fg'$
- $(\frac{f}{g})'=\frac{f'g-fg'}{g^2}$
- $\tan x'=\sec^2x$
- $\sec x'=\sec x\tan x$
- $\csc x'=-\csc x \cos x$

### Trigonometry

- $\sin^2x+\cos^2x=1$
- $1+\cot^2 x=\csc^2 x$
- $\tan^2 x+1=\sec^2 x$
- $\sin 2x=2\sin x \cos x$
- $\cos 2x=\cos^2x-\sin^2x=2\cos^2x-1=1-\sin^2x$
### Integration by parts
$$\int{u\mathrm{d}v}=uv-\int{v\mathrm{d}u}$$

## Chapter 10.1
### Concavity Test
$$\frac{\mathrm{d}^2y}{\mathrm{d}x^2}$$
## Chapter 10.2
$$\frac{\mathrm{d}y}{\mathrm{d}x}=\frac{\frac{\mathrm{d}y}{\mathrm{d}t}}{\frac{\mathrm{d}x}{\mathrm{d}t}}$$

<br>

$$\frac{\mathrm{d}^2y}{\mathrm{d}x^2}=\frac{\frac{\mathrm{d}}{\mathrm{d}t}(\frac{\mathrm{d}y}{\mathrm{d}x})}{\frac{\mathrm{d}x}{\mathrm{d}t}}$$
### Cycloid
$$\begin{cases}x_p = r(\theta-\sin\theta)\\y_p=r(1-\cos\theta)\end{cases}$$
### Arc length
$$\int_a^b \sqrt{(\frac{\mathrm{d}x}{\mathrm{d}t})^2+(\frac{\mathrm{d}y}{\mathrm{d}t})^2}\mathrm{d}t$$
## Chapter 10.3
$$\begin{cases}x=r\cos\theta \\ y=r\sin\theta\end{cases}$$

<br>

$$\begin{cases}x^2+y^2=r^2 \\ \tan\theta=\frac{y}{x}\end{cases}$$
### Symetric rules
* Unchanges when $\theta$ replaced by $-\theta$:
    * symetric about x axis
* Unchanged when r replaced by -r or $\theta$ replaced by $\theta+\pi$:
    * symetric about the pole(origin)
* Unchanged when $\theta$ replaced by $(\pi-\theta)$:
    * symetric about y axis
### Tangents
$$\frac{\mathrm{d}y}{\mathrm{d}x}=\frac{\frac{\mathrm{d}r}{\mathrm{d}\theta}\sin\theta+r\cos\theta}{\frac{\mathrm{d}r}{\mathrm{d}\theta}\cos\theta-r\sin\theta}$$

## Chapter 12.1-12.4
### *Right Hand Rule*
### Distance
$$P_1(x_1,y_1,z_1),P_2(x_2,y_2,z_2)$$

$$P_1P_2=l=\sqrt{(x_2-x_1)^2+(y_2-y_1)^2+(z_2-z_1)^2}$$

### Scalar
$$\vec{v}=<a,b,c>$$
$$|\vec{v}|=\sqrt{a^2+b^2+c^2}$$
### Unit Vector ($|\vec{u}|=1$)
$$\vec{u}=\frac{\vec{v}}{|\vec{v}|}$$
### Dot product
$\vec{a}=<a_1,a_2,a_3>,\vec{b}=<b_1,b_2,b_3>$
1. $$\vec{a}\cdot\vec{b}=a_1b_1+a_2b_2+a_3b_3=|\vec{a}||\vec{b}|\cos\theta$$
2. $$\cos\theta=\frac{\vec{a}\cdot\vec{b}}{|\vec{a}||\vec{b}|}$$
### Orthogonal=>  perpendicular=>  $\theta=\frac{\pi}{2}$
### Projection
#### Scalar projection of $\vec{b}$ onto $\vec{a}$
$$Comp_{\vec{a}}^{\vec{b}}=\frac{\vec{a}\cdot\vec{b}}{|\vec{a}|}$$
#### Vector projection of $\vec{b}$ onto $\vec{a}$
$$Proj_{\vec{a}}^{\vec{b}}=\frac{\vec{a}\cdot\vec{b}}{|\vec{a}|^2}\cdot\vec{a}$$
### Cross Product
$\vec{a}=<a_1,a_2,a_3>,\vec{b}=<b_1,b_2,b_3>$

$$\vec{a}\cdot\vec{b}=\begin{vmatrix}i & j & k \\a_1 & a_2 & a_3 \\b_1 & b_2 & b_3\end{vmatrix}=i\begin{vmatrix}a_2&a_3\\b_2&b_3\end{vmatrix}-j\begin{vmatrix}a_1&a_3\\b_1&b_3\end{vmatrix}+k\begin{vmatrix}a_1&a_2\\b_1&b_2\end{vmatrix}=<a_2b_3-a_3b_2, a_3b_1-a_1b_3, a_1b_2-a_2b_1>$$
The vector $\vec{a}\times\vec{b}$ is orthogonal to both $\vec{a}$ and $\vec{b}$

$|\vec{a}\times\vec{b}|=|\vec{a}|\vec{b}|\sin\theta$

## Chapter 12.5
### Line:
$$\vec{r}=\vec{r}_0+t\cdot\vec{v}$$

$$<x,y,z>=<x_0,y_0,z_0>+t\cdot<a,b,c>$$

$$\begin{cases}x=x_0+at\\y=y_0+bt\\z=z_0+ct\end{cases}$$

$$\frac{x-x_0}{a}=\frac{y-y_0}{b}=\frac{z-z_0}{c}$$

### Skew Lines:
Neither intersect nor parallel
### Plane
$\vec{n}$=>Normal Vector
A plane through $P(x_0,y_0,z_0) $ with $\vec{n}=<a,b,c>$ is

$$a(x-x_0)+b(y-y_0)+c(z-z_0)=0$$
### Find Angles between two planes:
Find the angle between normal vectors
### Find plane pass through $P_1$ $P_2$ and $P_3$
$\vec{n}=\vec{P_1P_2}\times\vec{P_2P_3}$ and with $P_1$
### Distance from $P(x_1,y_1,z_1)$ to plane $ax+by+cz+d=0$
$$D=\frac{|ax_1+by_1+cz_1+d|}{\sqrt{a^2+b^2+c^2}}$$
### Find the distance between two lines:
1. Find normal vector (By cross product the two velocity vectors of two lines)
2. Establish a plane
3. Use formula

## Chapter 13.3
### Arc Length in 3D
$$l=\int_a^b{\sqrt{(\frac{\mathrm{d}x}{\mathrm{d}t})^2+(\frac{\mathrm{d}y}{\mathrm{d}t})^2+(\frac{\mathrm{d}z}{\mathrm{d}t})}}\mathrm{d}t$$

if we assume $\vec{r(t)}=<f(t),g(t),h(t)>$=>$\vec{r'(t)}=<f'(t),g'(t),h'(t)>$

$$l=\int_a^b{|\vec{r'(t)}|\mathrm{d}t}$$
### Tangent Vector
$$\vec{T(t)} = \frac{\vec{r'(t)}}{\vec{|r'(t)|}}$$
$$|\vec{T(t)}|=1$$

### Normal Vector
$$\vec{N(t)} = \frac{\vec{T'(t)}}{|\vec{T'(t)|}}$$

### Binomal Vector
$$\vec{B(t)} = \vec{T(t)}\times\vec{N(t)}$$

### Normal Plane
Normal plane: The normal plane consists of all lines that are orthogonal to the tangent vector.
<br><br>
The normal vector of the normal plane is the tangent vector

$$\vec{n}=\vec{T}$$

### Osculating plane
The plane that comes the closest to containing the part of the curve near point P.
<br><br>
The normal vector of the osculating plane is the binomal vecotr

$$\vec{n} = \vec{B}$$

## Chapter 13.4
### Velocity
$$\vec{v(t)}=\vec{r'(t)}$$
### Speed
$$Speed = |\vec{v(t)}| = |\vec{r'(t)}|$$

## Chapter 14.1
### Level Curves / Contour Map
The level curves of a function $f$ of two variables are the curve with equations $f(x,y)=k$, where k is a constant (in the range of $f$).
### Functions of Three or more variables

## Chapter 14.2
### Limit of multi-var functions
### Prove the limit does not exist
Pick two different paths and show that the height or the value if the function is different if we transverse along these different paths.
### Tips
* Make sure the path you choose contains the point (a,b)
* It is highly recommended that one of the paths you choose is either by forcing x=0 and moving along y axis or forcing y=0 and moving along x axis.
* It is helpful to choose a path that makes the degree of the numerator and the denominator equal.

### Continuity
Sometimes we can use the concept of continuity for proving that the limit exist.
* If we have a region (two dimensional region in xy-plane) that the function is defined in that region, the function is continuous in that region. In other words, a function is continuous at any point inside its domain.
* Polynomials are continuous everywhere.
* Rational functions are continuous everywhere except where the denominator is zero.

## Chapter 14.3
### Partial Derivative
#### To Find $f_x$

Regard y as a constant and differentiate f(x,y) with respect to x.

#### To Find $f_y$

Regard x as a constant and differentiate f(x,y) with respect to y.

### Higher Derivatives

The notation $f_{xy}$ means, first we take the derivative with respect to x, and then we take the derivative with respect to y.

$f_{xy}=f_{yx}$

## Chapter 14.4

### Tangent Plane

The tangent plane to the surface S at $P(x_0,y_0,z_0)$ is

$$z-z_0=f_x(x_0,y_0)(x-x_0)+f_y(x_0,y_0)(y-y_0)$$

### Linear Approximation

$$f(x,y)=z\approx L(x,y)=f(a,b)+f_x(a,b)(x-a)+f_y(a,b)(y-b)$$

#### Theorem: If partial derivatives of $f_x$ and $f_y$ exist near (a,b) and are continuous at (a,b), then f is differentiable at (a,b)

## Chapter 14.5

#### Case1: Theorem:

Suppose that $z=f(x,y)$ is a differentiable function of x and y. Where $x=g(t)$ and $y=g(t)$ are both differentiable functions of t.

#### Then:

$$\frac{\mathrm{d}z}{\mathrm{d}t}=\frac{\partial z}{\partial x} \cdot \frac{\mathrm{d}x}{\mathrm{d}t}+ \frac{\partial z}{\partial y}\cdot\frac{\mathrm{d}y}{\mathrm{d}t}$$

#### Case2: Theorem:

$z=f(x,y)$ such that $x=g(s,t)$ and $y=h(s,t)$ 

$$\frac{\partial z}{\partial t}=\frac{\partial z}{\partial x}\cdot\frac{\partial x}{\partial t}+\frac{\partial z}{\partial y}\cdot\frac{\partial y}{\partial t}$$

$$\frac{\partial z}{\partial s}=\frac{\partial z}{\partial x}\cdot\frac{\partial x}{\partial s}+\frac{\partial z}{\partial y}\cdot\frac{\partial y}{\partial s}$$

### Implicit Differentiation

Suppose that an equation of form F(x,y)=0 defines y implicitly as a differentiable function of x, that is, y=f(x) where F(x,y)=0 or F(x, f(x))=0

$$\frac{\mathrm{d}y}{\mathrm{d}x}=-\frac{F_x}{F_y}$$

## Chapter 14.6

### Directional derivative

#### Theorem:

if f is a differentiable function of x and y, then f has a directional derivative in the direction of any vector $\vec{u}=<a,b>$ and:

$$D_u f(x,y)=f_x(x,y)a+f_y(x,y)b$$

### Gradient Vector:$<f_x,f_y>$

$$D_u f(x,y)=<f_x(x,y),f_y(x,y)>\cdot<a,b>=<f_x,f_y>\cdot\vec{u}$$

### Maximizing the directional derivative

#### Theorem:

If f is a differentiable function of two or three variables, the Maximum value of directional derivative is $|\nabla f|$ and it occurs when $\vec{u}$ has the same direction as the gradient vector

### Tangent planes to surfaces

An arbitrary point on the surface, the gradient vector at that point is perpendicular to any tangent vector to any curve C on S that passes through P.

#### Tangent Plane:

$$F_x(x_0,y_0,z_0)(x-x_0)+F_y(x_0,y_0,z_0)(y-y_0)+F_z(x_0,y_0,z_0)(z-z_0)=0$$

#### Normal Line:

$$\frac{x-x_0}{F_x(x_0,y_0,z_0)}=\frac{y-y_0}{F_y(x_0,y_0,z_0)}=\frac{z-z_0}{F_z(x_0,y_0,z_0)}$$

## Chapter 14.7

### First Derivative Test

if f has a local Max or Min at (a,b), and the first partial derivatives of f exist there, then $f_x(a,b)=0$ and $f_y(a,b)=0$

### Second Derivative Test

$$D=\begin{bmatrix}f_{xx}&f_{xy}\\f_{yx}&f_{yy}\end{bmatrix}=f_{xx}\cdot f_{yy}-(f_{xy})^2$$

(a) If D>0 and $f_{xx}(a,b)>0$, then $f(a,b)$ is a local Minimum

(b) If D>0 and $f_{xx}(a,b)<0$, then $f(a,b)$ is a local Maximum

(c) If D<0, then $f(a,b)$ is a saddle Point.

(d) If D=0, then $f(a,b)$ could be a local Maximum or a local Minimum or a saddle point

## Chapter 14.8

### The method of Lagrange Multipliers

To find the maximum and minimum values of $f(x,y,z)$ subject to constraint $g(x,y,z)=k$

$$\begin{cases}\nabla f(x,y,z)=\lambda\nabla g(x,y,z) \\ g(x,y,z)=k\end{cases}$$

### Two Constraints

$$\nabla f(x,y,z)=\lambda\nabla g(x,y,z)+\mu\nabla h(x,y,z)$$

## Chapter 15.1

### Double Integral & Fubini's Theorem 

$$\iint _Rf(x,y)\mathrm{d}A=\int_a^b\int_c^df(x,y)\mathrm{d}y \mathrm{d}x$$

$$\iint _Rf(x,y)\mathrm{d}A=\int_c^d\int_a^bf(x,y)\mathrm{d}x \mathrm{d}y$$

### Special Case

$$\iint_Rf(x,y)\mathrm{d}A=\iint_Rg(x)h(y)\mathrm{d}A=\int_a^bg(x)\mathrm{d}x\int_c^dh(y)\mathrm{d}y$$

### Average value

$$f_{average}=\frac{1}{A(R)}\iint f(x,y)\mathrm{d}A$$

## Chapter 15.2

### Type I

$$\iint_D f(x,y)\mathrm{d}A=\int_a^b\int_{g_1(x)}^{g_2(x)}f(x,y)\mathrm{d}y\mathrm{d}x$$

### Type II

$$\iint_Df(x,y)\mathrm{d}A=\int_c^d\int_{h_1(y)}^{h_2(y)}f(x,y)\mathrm{d}x\mathrm{d}y$$

## Chapter 15.3

### Change to polar coordinates in a double integral

$$\iint f(x,y)\mathrm{d}A=\int_{\alpha}^{\beta}\int_a^bf(r\cos\theta,r\sin\theta)r\mathrm{d}r\mathrm{d}\theta$$

### More Complicated Regions in polar Coordinates

if $f$ is continuous on polar region of the form $D=\lbrace(r,\theta)|\alpha<\theta<\beta, h_1(\theta)<r<h_2(\theta)\rbrace$ Then 

$$\iint_Df(x,y)\mathrm{d}A=\int_{\alpha}^{\beta}\int_{h_1(\theta)}^{h_2(\theta)}f(r\cos\theta,r\sin\theta)r\mathrm{d}r\mathrm{d}\theta$$

