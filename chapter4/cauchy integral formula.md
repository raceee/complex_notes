#chapter4 

#### Theorem
let $f$ be [[analytic]] everywhere inside an on a simple closed contour $C$, taken in the positive sense. If $z_0$ is any point interior to $C$, then $$f(z_0 ) = \frac{1}{2\pi i}\int_{C}\frac{f(z)dz}{z - z_0}$$

---

There is an extension of the cauchy integral formula

#### Theorem
Let $f$ be [[analytic]] inside and on a simple closed [[contour]] $C$, taken in the positive sense. If $z_0$ is any point interior to $C$, then $$f^{(n)}(z_0) = \frac{n!}{2\pi i}\int_{C}\frac{f(z)dz}{(z-z_0)^{n+1}}\quad (n=0,1,2,\dots )$$

---

This extension has some consequences
#### Theorem 1
If a funciton $f$ is [[analytic]] at a given point, then its derivatives of all orders are analytic there too.

##### Corollary
If a function $f(z) = u(x,y) + iv(x,y)$ is analytic at a point $z = (x,y)$, then the component functions $u$ and $v$ have continuous partial derivatives of all orders at that point.

---

#### Theorem 2
Let $f$ be continuous on a domain $D$. If $$\int_{C}f(z)dz = 0$$ for every closed contour $C$ in $D$, then $f$ is analytic throughout $D$.

---
#### Theorem 3
Suppose that a function $f$ is analytic inside and on a positively oriented circle $C_R$, ventered at $z_0$ and with radius $R$. If $M_R$ denotes the maximum value of $\vert f(z)\vert$ on $C_R$, then $$\vert f^{(n)}(z_0) \vert\leq \frac{n!M_R}{R^n}\quad (n = 1,2,\dots )$$