#chapter2 
Assuming that $z_0 \neq 0$, we shall in this section use the coordinate transformation $$x = r\cos\theta\quad\quad y = r\sin\theta$$This change of coordinate system also demands a change in the [[Cauchy-Riemann]] equations that being $$ru_r = v_\theta \quad \quad u_\theta = -rv_r$$ at $z_0$.

---

### Sufficient Conditions for Polar Functions
Let the fucntion $$f(z) = u(r, \theta ) + iv(r, \theta )$$
be defined throughtout some $\epsilon$ neighborhood of a nonzero point $z_0 = r_0 \exp(i\theta_0 )$, and suppose that
* the first-order partial derivatives of the functions $u$ and $v$ with respect to $r$ and $\theta$ exist everwhere in the neighborhood
* those partial derivatives are continuous at $(r_0 , \theta_0)$ and satisfy the polar form $$ru_r = v_\theta \quad \quad u_\theta = -rv_r$$

Then $f'(z_0 )$ exists, its value being $$f'(z_0 ) = e^{-i\theta}(u_r + iv_r)$$ where the right-hand side is to be evaluated at $(r_0 , \theta_0)$.

---

#### Example 2
The theorem can be used to show that any [[branch]] $$f(z) = \sqrt{r}e^{i\theta /2}\quad (r > 0, \alpha < \theta < \alpha + 2\pi)$$
of the square root function $z^{1/2}$ has a derivative everywhere in its domain of definition. Here $$u(r, \theta ) = \sqrt{r}\cos \frac{\theta}{2}\quad and\quad v(r, \theta ) = \sqrt{r}\sin \frac{\theta}{2}$$
Inasmuch as $$ru_r = \frac{\sqrt{r}}{2}\cos \frac{\theta}{2} = v_\theta\quad and \quad u_\theta = -\frac{\sqrt{r}}{2}\sin \frac{\theta}{2} = -rv_r$$ and since the remaining conditions in the theorem are satisified, the derivative $f'(z)$ exists at each point where $f(z)$ is defined. The theorem also tells us that $$f'(z) = e^{-i\theta}\left( \frac{1}{2\sqrt{r}}\cos \frac{\theta}{2} + i\frac{1}{2\sqrt{r}} \sin\frac{\theta}{2}\right)$$
$$f'(z) = \frac{1}{2\sqrt{r}}e^{-i\theta}\left( \cos \frac{\theta}{2} + i \sin\frac{\theta}{2}\right) = \frac{1}{2\sqrt{r}e^{i\theta / 2}} = \frac{1}{2f(z)}$$