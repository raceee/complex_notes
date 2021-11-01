#chapter2
If $f'(z)$ exists then we know that the Cauchy Riemann equations are satisfied.

### Cauchy-Riemann Equations
Suppose that $$f(z) = u(x,y) + iv(x,y)$$
and that $f'(z)$ exists at a point $z_0 = x_0 + i y_0$. Then the first-order partial derivatives of $u$ and $v$ must exist at $(x_0 , y_0)$, and they must satisfy the Cauchy-Riemann equations $$u_x = v_y\quad\quad u_y = -v_x$$ there. Also, $f'(z_0 )$ can be written $$f'(z_0 ) = u_x + iv_x$$, where these partial derivatives are to be evaluated at $(x_0 , y_0 )$.

---

#### Example 1
We have the function $$f(z) = z^2 = x^2 - y^2 + i2xy$$ is differentiable everywhere and that $f'(z) = 2z$. To verify that the Cauchy-Riemann equaitons are satisfied everywhere write $$u(x,y) = x^2 - y^2\quad and\quad v(x,y) = 2xy$$
Thus $$u_x = 2x = v_y \quad\quad u_y=-2y=-v_x$$
Then the CR equations are satisfied and the derivative exists.

---

#### Note 
* that the CR equations do not ensure the existence of $f'(0)$. 
* The CR equations alone are not suffiecient to ensure the existence of the derivative of a function $f(z)$ at that point.
* Since the CR equations are necessary conditions for the existence of the derivative of a function $f$ at a point $z_0$, they can often be used to located points at which $f$ does *not* have a derivative.