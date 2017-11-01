# Math 2D
## Chapter 10.1
### Derivatives
* $(fg)'=f'g+fg'$
* $(\frac{f}{g})'=\frac{f'g-fg'}{g^2}$
* $\tan x'=\sec^2x$
* $\sec x'=\sec x\tan x$
* $\csc x'=-\csc x \cos x$
### Trigonometry
* $\sin^2x+\cos^2x=1$
* $1+\cot^2 x=\csc^2 x$
* $\tan^2 x+1=\sec^2 x$
* $\sin 2x=2\sin x \cos x$
* $\cos 2x=\cos^2x-\sin^2x=2\cos^2x-1=1-\sin^2x$
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

$$\vec{a}\cdot\vec{b}=\begin{vmatrix}
i & j & k \\
a_1 & a_2 & a_3 \\
b_1 & b_2 & b_3
\end{vmatrix}
=i\begin{vmatrix}
a_2&a_3\\b_2&b_3\end{vmatrix}
+j\begin{vmatrix}
a_1&a_3\\b_1&b_3\end{vmatrix}
+k\begin{vmatrix}
a_1&a_2\\b_1&b_2\end{vmatrix}
=<a_2b_3-a_3b_2, a_3b_1-a_1b_3, a_1b_2-a_2b_1>$$
The vector $\vec{a}\times\vec{b}$ is orthogonal to both $\vec{a}$ and $\vec{b}$
$|\vec{a}\times\vec{b}|=|\vec{a}|\vec{b}|\sin\theta$
## Chapter 12.5
### Line:
$$\vec{r}=\vec{r}_0+t\cdot\vec{v}$$
$$<x,y,z>=<x_0,y_0,z_0>+t\cdot<a,b,c>$$
$$\begin{cases}
x=x_0+at\\
y=y_0+bt\\
z=z_0+ct
\end{cases}$$
$$\frac{x-x_0}{a}=\frac{y-y_0}{b}=\frac{z-z_0}{c}$$
### Skew Lines:
Neither intersect nor parallel
### Plane
$\vec{n}$=>Normal Vector
A plane through $P(x_0,y_0,z_0) with $\vec{n}=<a,b,c>$ is

$$a(x-x_0)+b(y-y_0)+c(z-z_0)=0$$
### Find Angles between two plance:
Find the angle between normal vectors
### Find plane pass through $P_1$ $P_2$ and $P_3$
$\vec{n}=\vec{P_1P_2}\times\vec{P_2P_3}$ and with $P_1$
### Distance from $P(x_1,y_1,z_1)$ to plane $ax+by+cz=0$
$$D=\frac{|ax_1+by_1+cz_1+d|}{\sqrt{a^2+b^2+c^2}}$$
### Find the distance between two lines:
1. Find normal vector
2. Establish a plane
3. Use formula

## Chapter 13.3
### Arc Length in 3D
$$l=\int_a^b{\sqrt{(\frac{\mathrm{d}x}{\mathrm{d}t})^2+(\frac{\mathrm{d}y}{\mathrm{d}t})^2+(\frac{\mathrm{d}z}{\mathrm{d}t})}}\mathrm{d}t$$

if we assume $\vec{r(t)}=<f(t),g(t),h(t)>$=>$\vec{r'(t)}=<f'(t),g'(t),h'(t)>$

$$l=\int_a^b{|\vec{r'(t)}|\mathrm{d}t}$$