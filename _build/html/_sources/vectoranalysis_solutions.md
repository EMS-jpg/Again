# Solutions to Vector Operations Sheet

All vector quantities on this sheet are denoted with an underline eg $\underline{r}$, $\underline{\hat{r}}$, $\underline{\nabla}$.

## Question 1
### (a)

$\phi=x^{2}+x y+y^{2}$

$$
\underline{\nabla} \phi=\left(\frac{\partial \phi}{\partial x}, \frac{\partial \phi}{\partial y}, \frac{\partial \phi}{\partial z}\right)=(2 x+y, x+2 y, 0)
$$

### (b)

$$
\begin{aligned}
& \phi=r=\sqrt{x^{2}+y^{2}+z^{2}} \\
& \frac{\partial \phi}{\partial x}=\frac{1}{2}\left(x^{2}+y^{2}+z^{2}\right)^{-1 / 2} 2 x=\frac{x}{r}
\end{aligned}
$$

Similary, $\frac{\partial \phi}{\partial y}=y, \frac{\partial \phi}{\partial z}=\frac{z}{r}$.

$$
\Rightarrow \underline{\nabla} =\frac{1}{r}(x, y, z)=\frac{\underline{r}}{r}=\underline{\hat{r}}
$$

## Question 2

$r^{n}=\left(x^{2}+y^{2}+z^{2}\right)^{\frac{n}{2}}$

$$
\frac{\partial r^{n}}{\partial x}=\frac{n}{2}\left(x^{2}+y^{2}+z^{2}\right)^{\frac{n}{2}-1} \cdot 2 x=n x r^{n-2}
$$

Similarly, $\frac{\partial r^{n}}{\partial y}=n y r^{n-2}, \quad \frac{\partial r^{n}}{\partial z}=n z r^{n-2}$

$$
\Rightarrow \text { grad } r^{n}=n r^{n-2}(x, y, t)=n r^{n-2} \underline{r}
$$


## Question 3


$$
\begin{aligned}
&\phi=x^{2} y z^{3}, \quad \underline{n}=\left(\frac{1}{3}, \frac{2}{3}, \frac{2}{3}\right) \\
\\
\operatorname{grad} \phi & =\left(2 x y z^{3}, x^{2} z^{3}, 3 x^{2} y z^{2}\right) \\
\underline{n} \cdot \operatorname{grad} \phi & =\frac{2}{3} x y z^{3}+\frac{2}{3} x^{2} z^{3}+2 x^{2} y z^{2} \\
& =\frac{2}{3} x z^{2}(y z+x z+3 x y)
\end{aligned}
$$



## Question 4

$$
\phi=x^{2} y z+4 x z^{2} \\
\underline{\nabla} \phi=\left(2 x y z+4 z^{2}, x^{2} z, x^{2} y+8 x z\right)
$$

At $P=(1,-2,-1)$, 
$$
\begin{aligned}
& \underline{\nabla} \phi=(4+4,-1,-2-8)=(8,-1,-10) \\
& \underline{a}=(2,-1,-2) \\
& |\underline{a}|=\sqrt{4+1+4}=\sqrt{9}=3
\end{aligned}
$$

The unit vector in direction of 

$$ \underline{a}=\hat{a}=\frac{1}{3}(2,-1,-2)$$.

The directional derivative, 
$$
\begin{aligned}
& =\underline{\hat{a}} \cdot \underline{\nabla} \phi \\
& =\frac{1}{3}[16+1+20]=\frac{37}{3}
\end{aligned}
$$

Since $\underline{\hat{a}} \cdot \nabla \phi>0, \phi$ is increasing at $P$ in the direction of $\underline{a}$. 

## Question 5



$$
\begin{aligned}
\phi= &x \sin x y+z \cos x y \\
\underline{\nabla} \phi= & (\sin x y+x y \cos y-y z \sin x y) \underline{i} +\left(x^{2} \cos x y-x z \sin x y\right) \underline{j}+\cos x y \underline{k} \\
\underline{a}= & (-1,1,-1) \\
|\underline{a}|= & \sqrt{1+1+1}=\sqrt{3} \\
\Rightarrow \underline{\hat{a}} = & \frac{1}{\sqrt{3}}(-1,1,-1)
\end{aligned}
$$

At $P=(\frac{\pi}{2},2,0)$

$$
\begin{aligned}
\nabla \phi= & (\sin \pi+\pi \cos \pi-0) \underline{i}+\left(\pi^{2} / 4 \cos \pi-0\right) \underline{j} +\cos \pi \underline{k} \\
= & \left(-\pi,-\frac{\pi^{2}}{4},-1\right)
\end{aligned}
$$

The component of grad $\phi$ in direction of $\underline{a}$ is

$$
\hat{a} \cdot \nabla \phi=\frac{1}{\sqrt{3}}\left(\pi-\frac{\pi^{2}}{4}+1\right)
$$

## Question 6

### (a).

$$
\begin{aligned}
& \underline{A}=(x y, y z, 0) \\
\operatorname{div} \underline{A} & =\frac{\partial}{\partial x}(x y)+\frac{\partial}{\partial y}(y z)+\frac{\partial}{\partial z}(0) \\
& =y+z \\
\end{aligned}
$$

$$
\begin{aligned}
& \operatorname{curl} \underline{A}=\left|\begin{array}{ccc}
\underline{i} & \underline{j} & \underline{k} \\
\frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\
x y & yz & 0
\end{array}\right| \\
\\
& = \underline{i}\left[\frac{\partial}{\partial y}(0)-\frac{\partial}{\partial z}(y z)\right]- \underline{j}\left[\frac{\partial}{\partial x}(0)-\frac{\partial}{\partial x}(x y)\right] + \underline{k}\left[\frac{\partial}{\partial x}(y z)-\frac{\partial}{\partial y}(x y)\right] \\
& =(-y, 0,-x)
\end{aligned}
$$

### (b).

$$
\begin{aligned}
\underline{A} & =(z, x, y) \\
\operatorname{div} \underline{A} & =\frac{\partial}{\partial x}(z)+\frac{\partial}{\partial y}(x)+\frac{\partial}{\partial z}(y)=0 \\
\operatorname{curl} \underline{A} & =\left|\begin{array}{ccc}
\underline{i} & \underline{j} & \underline{k} \\
\frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\
z & x & y
\end{array}\right| \\
& =\left(\begin{array}{ll}
1,1,1
\end{array}\right)
\end{aligned}
$$


## Question 7

$\underline{A}=f(r) \underline{r}=(f x, f y, f z)$.

$$
\begin{aligned}
\underline{\nabla} \cdot \underline{A} & =\frac{\partial}{\partial x}(f x)+\frac{\partial}{\partial y}(f y)+\frac{\partial}{\partial z}(f z) \\
& =\frac{\partial f}{\partial x} x+f+\frac{\partial f}{\partial y} y+f+\frac{\partial f}{\partial z} z+f \\
& =3 f(r)+x \frac{\partial f}{\partial x}+y \frac{\partial f}{\partial y}+z \frac{\partial f}{\partial z}
\end{aligned}
$$

By the chain rule, $\frac{\partial f}{\partial x}=\frac{d f}{d r} \frac{\partial r}{\partial x}$

$$
\begin{aligned}
& \frac{\partial r}{\partial x}=\frac{\partial}{\partial x}\left(x^{2}+y^{2}+z^{2}\right)^{\frac{1}{2}}=\frac{1}{2}\left(x^{2}+y^{2}+z^{2}\right)^{-\frac{1}{2}} \cdot 2 x=\frac{x}{r} . \\
& \Rightarrow \frac{\partial f}{\partial x}=\frac{x}{r} \frac{d f}{d r} .
\end{aligned}
$$

Similarly, $\frac{\partial f}{\partial y}=y \frac{d f}{d r}, \quad \frac{\partial f}{\partial z}=\frac{z}{r} \frac{d f}{d r}$

$$
\begin{aligned}
\Rightarrow \underline{\nabla} \cdot \underline{A} & =3 f(r)+\frac{x^{2}}{r} \frac{d f}{d r}+\frac{y^{2}}{r} \frac{d f}{d r}+\frac{z^{2}}{r} \frac{d f}{d r} \\
& =3 f(r)+\frac{r^{2}}{r} \frac{d f}{d r} \\
& =3 f(r)+r \frac{d f}{d r}
\end{aligned}
$$


$$
\begin{aligned}
& \underline{\nabla} . \underline{A} = 0 \Rightarrow 3 f+\frac{r d f}{d r}=0 \\
& \Rightarrow r\frac{d f}{d r}=-3 f . \\
& \Rightarrow \frac{1}{f} \frac{d f}{d r}=-\frac{3}{r} . \\
& \Rightarrow \int \frac{1}{f} d f=-3 \int \frac{1}{r} d r . \\
& \begin{aligned}
\Rightarrow \ln f & =-3 \ln r+\ln c \quad \quad \text{Where } c \text{ is a constant.} \\
& =\ln r^{-3}+\ln c \\
& =\ln \left(\frac{c}{r^{3}}\right) \\
\Rightarrow f & =\frac{c}{r^{3}}
\end{aligned}
\end{aligned}
$$



## Question 8 

$$
\begin{aligned}
& \underline{v}=(x+2 y+a z, \quad b x-3 y-z, 4 x+c y+2 z) \\
& \text { curl } \underline{v}=\left|\begin{array}{ccc}
\underline{y} & \underline{j} & \underline{k}\\
\frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\
x+2 y+a z & b x-3 y-z & 4 x+c y+2 z
\end{array}\right| \\
\\
& =\underline{i}(c+1)-\underline{j}(4-a)+\underline{k}(b-2) \\
\end{aligned}
$$

If curl $\underline{v}=0$ then $a=4, b=2, c=-1$.

$$
\begin{aligned}
& \underline{v}=\underline{\nabla}\phi=\left(\frac{\partial \phi}{\partial x}, \frac{\partial \phi}{\partial y}, \frac{\partial \phi}{\partial z}\right) \\
& \frac{\partial \phi}{\partial x}=x+2 y+4 z \\
\end{aligned}
$$

$$
\begin{align}
& \Rightarrow \phi(x, y, z)=\frac{x^{2}}{2}+2 x y+4 x z+f(y, z) \label{eq8.1}\\
\end{align}
$$
$$
\frac{\partial \phi}{\partial y}=2 x-3 y-z . \text { from } \underline{v}=\nabla \phi .
$$

from \ref{eq8.1}, $\frac{\partial \phi}{\partial y}=2 x+\frac{\partial f}{\partial y}$.

comparing, $\frac{\partial f}{\partial y}=-3 y-z$.


Integrating, $f=-\frac{3}{2} y^{2}-y z+g(z)$.

Subsituting in \ref{eq8.1}, 

$$
\begin{align}
\phi(x, y, z)=\frac{x^{2}}{2}+2 x y+4 x z-\frac{3 y^{2}}{2}-y z+g(z) \label{eq8.2}.
\end{align}
$$

from $\underline{v}=\nabla \phi, \quad \frac{\partial \phi}{\partial z}=4 x-y+2 z$.

from \ref{eq8.2}, $\frac{\partial \phi}{\partial z}=4 x-y+\frac{d y}{d z}$

comparing, $\frac{d g}{d z}=2 z . \quad \Rightarrow g=z^{2}+c \quad c=$ constant.

Substituting in \ref{eq8.2},

$$
\phi(x, y, z)=\frac{x^{2}}{2}+2 x y+4 x z-\frac{3 y^{2}}{2}-y z+z^{2}+c
$$

## Question 9. 

$$
\begin{aligned}
& \nabla^{2} r ^{n}=\frac{\partial^{2}}{\partial x^{2}}\left(r^{n}\right)+\frac{\partial^{2}}{\partial y^{2}}\left(r^{n}\right)+\frac{\partial^{2}}{\partial z^{2}}\left(r^{n}\right) \\
& r^{n}=\left(x^{2}+y^{2}+z^{2}\right)^{\frac{n}{2}} \\
& \frac{\partial\left(r^{n}\right)}{\partial x}= \frac{n}{2}\left(x^{2}+y^{2}+z^{2}\right)^{\frac{n}{2}-1} \cdot 2 x=n x r^{n-2} \\
\frac{\partial^{2}}{\partial x^{2}}\left(r^{n}\right)&=\frac{\partial}{\partial x}\left(n x\left(x^{2}+y^{2}+z^{2}\right)^{\frac{n}{2}-1}\right) \\
&=n\left(x^{2}+y^{2}+z^{2}\right)^{\frac{n}{2}-1}+n x\left(\frac{n}{2}-1\right)\left(x^{2}+y^{2}+t^{2}\right)^{\frac{n}{2}-2} \cdot 2 x \\
&=n r^{n-2}+n x^{2}(n-2) r^{n-4}
\end{aligned}
$$

Similarly, $\frac{\partial^{2}}{\partial y^{2}}(r^n)=n r^{n-2}+n y^{2}(n-2) r^{n-4}$.

$$
\begin{aligned}
& \frac{\partial^{2}}{\partial z^{2}}\left(r^{n}\right)=n r^{n-2}+n z^{2}(n-2) r^{n-4} \\
\\
\Rightarrow \nabla^{2} r^{n} & = n r^{n-2}+n x^{2}(n-2) r^{n-4}+n r^{n-2}+n y^{2}(n-2) r^{n-4} +n r^{n-2}+n z^{2}(n-2) r^{n-4}\\
& =3 n r^{n-2}+n(n-2) r^{n-4}\left(n^{2}+y^{2}+z^{2}\right) \\
& =3 n r^{n-2}+n(n-2) r^{n-4} r^{2}\\
& =r^{n-1}(3 n+n(n-1)) \\
& =n(3+n-2) r^{n-2} \\
& =n(n+1) r^{n-2}\\
\end{aligned}
$$

## Question 10
### (a)

$$
\begin{aligned}
\operatorname{curl}(\Omega \underline{F})=\left|\begin{array}{ccc}
\underline{i} & \underline{j} & \underline{k} \\
\frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\
\Omega f_{1} & \Omega f_{2} & \Omega f_{3}
\end{array}\right|
\end{aligned}
$$


$$
\begin{align}
& = \underline{i}\left[\frac{\partial}{\partial y}\left(\Omega f_{3}\right)-\frac{\partial}{\partial z}\left(\Omega F_{2}\right)\right]-\underline{j}\left[\frac{\partial}{\partial x}\left(\Omega f_{3}\right)-\frac{\partial}{\partial z}\left(\Omega f_{1}\right)\right] +\underline{k}\left[\frac{\partial}{\partial x}\left(\Omega\left(f_{2}\right)-\frac{\partial}{\partial y}\left(\Omega f_{1}\right)\right]\right. \\
& =\underline{i}\left[\Omega \frac{\partial f_{3}}{\partial y}+f_{3} \frac{\partial \Omega}{\partial y}-\Omega \frac{\partial f_{2}}{\partial z}-f_{2} \frac{\partial \Omega}{\partial z}\right] -\underline{j}\left[\Omega \frac{\partial F_{3}}{\partial x}+f_{3} \frac{\partial \Omega}{\partial x}-\Omega \frac{\partial f_{1}}{\partial z}-f_{1} \frac{\partial \Omega}{\partial z}\right] + \underline{k}\left[\frac{\Omega f_{2}}{\partial x}+ f_{2} \frac{\partial \Omega}{\partial x}-\Omega \frac{\partial f_{1}}{\partial y}- f_{1} \frac{\partial \Omega}{\partial y}\right] \label{eq10.1} \\
\end{align}
$$


$$
\begin{aligned}
\operatorname{\Omega curl \underline{F}} =\Omega\left|\begin{array}{lll}
\underline{i} & \underline{j} & \underline{k} \\
\frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\
f_{1} & f_{2} & f_{3}
\end{array}\right| 
\end{aligned}
$$

$$
\begin{align}
& =\underline{i}\left[\Omega \frac{\partial f_3}{\partial y}-\Omega \frac{\partial f_{2}}{\partial z}\right]-\underline{j}\left[\Omega \frac{\partial f_{3}}{\partial x}-\Omega \frac{\partial f_{1}}{\partial z}\right] +\underline{k}\left[\frac{\partial f_{2}}{\partial x}-\Omega \frac{\partial f_{1}}{\partial y}\right] \label{eq10.2}
\end{align}
$$

$$
\begin{aligned}
& \operatorname{grad} \Omega=\left(\frac{\partial \Omega}{\partial n}, \frac{\partial \Omega}{\partial y}, \frac{\partial \Omega}{\partial z}\right)\\
& \underline{F} \times \operatorname{grad} \Omega=(\operatorname{grad} \Omega) \underline{F} \\
& = \Omega\left|\begin{array}{lll}
\underline{i} & \underline{j} & \underline{k} \\
\frac{\partial \Omega}{\partial x} & \frac{\partial \Omega}{\partial y} & \frac{\partial \Omega}{\partial z} \\
f_{1} & f_{2} & f_{3}
\end{array}\right| 
\end{aligned}
$$

$$
\begin{align}
& =\underline{i}\left[f_{3} \frac{\partial\Omega }{\partial y}-f_{2} \frac{\partial \Omega }{\partial z}\right]-\underline{j}\left[f_{3}\frac{\partial \Omega  }{\partial x}- f_{1} \frac{\partial \Omega }{\partial z}\right] +\underline{k}\left[f_{2} \frac{\partial \Omega }{\partial x}- f_{1} \frac{\partial \Omega }{\partial y}\right] \label{eq10.3}
\end{align}
$$

comparing \ref{eq10.1}, \ref{eq10.2} and \ref{eq10.3}, it is clear that

$
\operatorname{curl}(\Omega \underline{F})=\Omega \operatorname{curl \underline{F}} - \underline{F} \times \operatorname{grad} \Omega
$

In $\underline{\nabla}$ notation:

$$
\underline{\nabla} \times(\Omega \underline{F})=\Omega \underline{\nabla} \times \underline{F}- \underline{F} \times \underline{\nabla} \Omega
$$




### (b). 

grad $\Omega=\left(\frac{\partial \Omega}{\partial x}, \frac{\partial \Omega}{\partial y}, \frac{\partial \Omega}{\partial t}\right)$.

$$
\begin{aligned}
& \text { curl grad} \Omega=\left|\begin{array}{ccc}
\underline{i} & \underline{j} & \underline{k}\\
\frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\
\frac{\partial \Omega}{\partial x} & \frac{\partial \Omega}{\partial y} & \frac{\partial \Omega}{\partial z}
\end{array}\right| \\
& =\underline{i}\left[\frac{\partial^{2} \Omega}{\partial y \partial z}-\frac{\partial^{2} \Omega}{\partial z \partial y}\right]-j\left[\frac{\partial^{2} \Omega}{\partial x \partial z}-\frac{\partial^{2} \Omega}{\partial z \partial x}\right] +\underline{k}\left[\frac{\partial^{2} \Omega}{\partial x \partial y}-\frac{\partial^{2} \Omega}{\partial y \partial x}\right] \\
&=(0,0,0) \\
\Rightarrow & \operatorname{curl} \operatorname{grad} \Omega=0
\end{aligned}
$$

in $\underline{\nabla}$ notation:

$$
\begin{aligned}
& \underline{\nabla} \times(\underline{\nabla} \Omega)=\underline{0} \\
\end{aligned}
$$


$ \underline{H} = \phi \operatorname{grad} \psi$


Put $\Omega=\phi, \underline{F} =$ grad $\psi$ in part $(a)$.

$$
\begin{aligned}
\operatorname{curl} H & =\operatorname{curl}(\phi \operatorname{grad} \psi) \\
& =\operatorname{curl}(\Omega \underline{f}) \\
& =\Omega \text { curl } \underline{f} - \underline{F} \times \operatorname{grad} \Omega \\
& =\phi \operatorname{ curl} \operatorname{grad } \psi -\operatorname{grad} \psi \times \operatorname{grad} \phi \\
& =-\operatorname{grad} \psi \times \operatorname{grad} \phi
\end{aligned}
$$

since $\operatorname{ curl} \operatorname{grad } \psi = 0$ by part $(b)$.

$\underline{H}$ is parallel to $\operatorname{grad} \psi$.

curl $\underline{H}$ is perpendicular $\operatorname{grad } \psi$.

$\Rightarrow$ curl $\underline{H}$ is perpendicular to $\underline{H}$ (where neither varies).

$$
\underline{H}=x^{2} y \underline{r}=x^{2} y(x, y, z)
$$


Let $\phi=x^{2} y$, then $\operatorname{grad} \psi=(x, y, z)$.

$$
\begin{aligned}
& \Rightarrow \frac{\partial \psi}{\partial x}=x \Rightarrow \psi=\frac{x^{2}}{2}+f(y, z) \\
& \frac{\partial \psi}{\partial y}=y=\frac{\partial f}{\partial y} \Rightarrow f=\frac{y^{2}}{2}+g(z) \\
& \Rightarrow \psi =\frac{x^{2}}{2}+y^{2}+g(z) . \\
& \frac{\partial \psi}{\partial z}=z=\frac{d g}{d z} \Rightarrow g=\frac{z^{2}}{2}+\text { constant. }
\end{aligned}
$$

$\Rightarrow$ we can take $\psi =\frac{x^{2}}{2}+\frac{y^{2}}{2}+\frac{z^{2}}{2}=\frac{1}{2} r^{2}$.

$$
\begin{aligned}
\text { curl } \underline{H} & =\left|\begin{array}{ccc}
\underline{i} & \underline{j} & \underline{k} \\
\frac{\partial}{\partial x} & \frac{\partial}{\partial y } & \frac{\partial}{\partial z} \\
x^{3} y & x^{2} y^{2} & x^{2} y z
\end{array}\right| \\
\\
= & \underline{i}\left(x^{2} z-0\right)-\underline{j}(2 x y z-0)+\underline{k}\left(2 x y^{2}-x^{3}\right) . \\
& =\left(x^{2} z,-2 x y z, 2 x y^{2}-x^{3}\right) \\
\underline{H} \cdot \operatorname{curl} \underline{H} & =x^{3} y \cdot x^{2} z-x^{2} y^{2} 2 x y z+x^{2} y z\left(2 x y^{2}-x^{3}\right) \\
& =x^{5} y z-2 x^{3} y^{3} z+2 x^{3} y^{3} z-x^{5} y z=0 .
\end{aligned}
$$

$\Rightarrow \underline{H}$ and $\operatorname{curl} \underline{H}$ are perpendicular.

## Question 11. 

$\underline{A}=\left(x^{2} y, y^{2} z, z^{2} x\right)$.

### (a)

$$
\begin{aligned}
& \underline{\nabla} \cdot \underline{A}=\frac{\partial}{\partial x}\left(x^{2} y\right)+\frac{\partial}{\partial y}\left(y^{2} z\right)+\frac{\partial}{\partial z}\left(z^{2} x\right) \\
& =2 x y+2 y z+2 z x
\end{aligned}
$$

### (b)

$$
\begin{aligned}
\underline{\nabla}(\underline{\nabla} \cdot \underline{A})= & \underline{i} \frac{\partial}{\partial x}(2 x y+2 y z+2 z x)+\underline{j} \frac{\partial}{\partial y}(2 x y+2 y z+2 z x) +\underline{k} \frac{\partial}{\partial z}(2 x y+2 y z+2 z x) \\
= & (2 y+2 z, 2 x+2 z, 2 y+2 x).
\end{aligned}
$$

### (c)

$$
\begin{aligned}
& \underline{\nabla} \times \underline{A}=\left|\begin{array}{ccc}
\underline{i} & \underline{k} & \underline{z}\\
\frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial z}{\partial z} \\
x^{2} y & y^{2} z & z^{2} x
\end{array}\right| \\
& =\underline{i}\left(0-y^{2}\right)-\underline{j}\left(z^{2}-0\right)+\underline{k}\left(0-n^{2}\right) \\
& =\left(-y^{2},-z^{2},-x^{2}\right) \text {. }
\end{aligned}
$$

### (d).

$$
\begin{aligned}
\underline{\nabla} & \times(\underline{\nabla} \times \underline{A})=\left|\begin{array}{lll}
\underline{i} & \underline{j} & \underline{k} \\
\frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\
-y^{2} & -z^{2} & -x^{2}
\end{array}\right| \\
& =\underline{i}(0+2 z)-\underline{j}(-2 x-0)+\underline{k}(0+2 y) \\
& =(2 z, 2 x, 2 y) .
\end{aligned}
$$



### (e). 

$\underline{\nabla}^{2} \underline{A}=\left(\underline{\nabla}^{2} A_{1}, \underline{\nabla}^{2} A_{2}, \underline{\nabla}^{2} A_{3}\right)$

$$
\begin{aligned}
\underline{\nabla}^{2} A_{1} & =\frac{\partial^{2}}{\partial x^{2}}\left(x^{2} y\right)+\frac{\partial^{2}}{\partial y^{2}}\left(x^{2} y\right)+\frac{\partial^{2}}{\partial z^{2}}\left(x^{2} y\right) \\
& =\frac{\partial}{\partial x}(2 x y)+\frac{\partial}{\partial y}\left(x^{2}\right)+\frac{\partial}{\partial z}(0) \\
& =2 y
\end{aligned}
$$

$$
\begin{aligned}
\underline{\nabla}^{2} A_{2} & =\frac{\partial^{2}}{\partial x^{2}}\left(y^{2} z\right)+\frac{\partial^{2}}{\partial y^{2}}\left(y^{2} z\right)+\frac{\partial^{2}}{\partial z^{2}}\left(y^{2} z\right) \\
& =\frac{\partial}{\partial x}(0)+\frac{\partial}{\partial y}(2 y z)+\frac{\partial}{\partial z}\left(y^{2}\right)\\
& =2 z
\end{aligned}
$$

$$
\begin{aligned}
\underline{\nabla}^{2} A_{3} & \left.=\frac{\partial^{2}}{\partial x^{2}}\left(z^{2} x\right)+\frac{\partial^{2}}{\partial y^{2}} z^{2} x\right)+\frac{\partial^{2}}{\partial z^{2}}\left(z^{2} x\right) \\
& =\frac{\partial}{\partial x}\left(z^{2}\right)+\frac{\partial}{\partial y}(0)+\frac{\partial}{\partial z}(2 z x)\\
& =2 x .
\end{aligned}
$$

$$
\Rightarrow \underline{\nabla}^{2} \underline{A}=(2 y, 2 z, 2 x) .
$$

Using $(b)$ and $(d)$,

$$
\begin{aligned}
& \underline{\nabla}(\underline{\nabla} \cdot \underline{A})-\underline{\nabla} \times(\underline{\nabla} \times \underline{A})=(2 y+2 z, 2 x+2 z, 2 y+2 x) - \left(2z, 2x, 2y\right) \\
&=(2y , 2 z, 2 x) \\
&=\underline{\nabla}^{2} \underline{A} \text { from } (e) \\
& \Rightarrow \underline{\nabla}(\underline{\nabla} \cdot \underline{A})-\underline{\nabla} \times(\nabla \times A)=\underline{\nabla}^{2} \underline{A} .
\end{aligned}
$$

or:

$$
\underline{\nabla}^{2} \underline{A}=\operatorname{grad}(\operatorname{div} \underline{A})-\operatorname{curl}\operatorname{curl} A
$$




```python

```
