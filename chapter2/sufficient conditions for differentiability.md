#chapter2 
### Conditions for Differentialbility 
Let the funciton $$f(z) = u(x,y) + iv(x,y)$$ be defined throughout some $\epsilon$ neighborhood of a point $z_0 = x_0 +iy_0$, and suppose that
* the first-order partial derivatives of the functions $u$ and $v$ with respect to $x$ and $y$ exist everywhere in the neighborhood
* those partial derivatives are continuous at $(x_0, y_0 )$ and satisfy the [[Cauchy-Riemann]] equations $$u_x = v_y\quad\quad u_y = -v_x$$ at $(x_0 , y_0 )$, Then $f'(z_0 )$ exists, its value being $$f'(z_0 ) = u_x + iv_x$$where the right-hand side is to be evaluated at $(x_0 , y_0 )$.


---

#### Example 1
Consider the function $$f(z) = e^{x}e^{iy} = e^x (\cos y + ie^{x}\sin y)$$ where $z = x + iy$ and $y$ is to be taken in radians when $\cos y$ and $\sin y$ are evaluated. Here $$u(x, y) = e^x \cos y\quad and\quad v(x,y) = e^x \sin y$$
Since $u_x = v_y$ and $u_y = -v_x$ everywhere and since thse derivatives are everywhere continuous, the conditions in the above theorem are satisfied at all points in the complex plane. Thus $f'(z)$ exists everywhere, and $$f'(z) = e^x \cos y + ie^x \sin y$$ Note that $f'(z) = f(z)$ for all $z$.

---

#### Example 2
It also follows from our theorem that the function $f(z) = \vert z\vert^2$, whose components are $$u(x,y) = x^2 + y^2\quad and \quad v(x,y) = 0$$ has a derivative at $z = 0$. In fact, $f'(0) = 0 + i0 = 0$. This function cannot have a derivative at any nonzero point since the [[Cauchy-Riemann]] equations are not satisified at such points.