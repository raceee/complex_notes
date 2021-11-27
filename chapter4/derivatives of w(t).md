#chapter4
Consider the complex valued function where $t$ is real $$\omega(t) = u(t) + iv(t)$$ Where $u(t)$ and $v(t)$ are the real and complex portions of the functions respectively. Then $$\omega'(t) = u'(t) + iv'(t)$$ Now let $z_0 = x_0 + iy_0$ and consider $$\frac{d}{dt}z_0\omega(t) = \frac{d}{dt} (x_0 +iy_0)(u(t) + iv(t))$$ After foiling the complex number with the real and imaginary parts of $\omega(t)$ we get $$\frac{d}{dt}z_0\omega(t) =z_0\omega'(t)$$

Mean value theorem $$\omega'(c) = \frac{w(b) - w(a)}{b-a}$$ does not hold anymore

###### Example
 Assuming that the functions $u(t)$ and $v(t)$ in expressions (1) are differentialable at $t$, let us prove that $$\frac{d}{dt}[w(t)]^2 = 2w(t)w'(t)$$
 We begin by $$[w(t)]^2 = (u + iv)^2 = u^2 - v^2 + i2uv$$ Then $$\frac{d}{dt}[w(t)]^2 = (u^2 - v^2 )' + i(2uv)'$$ $$= 2uu' - 2vv' + i2(uv' + u'v)$$ $$= 2(u + iv)(u'+iv')$$
 
 ---
 
 The Mean Value Theorem does not work anymore. Meaning that the number $c$ doesn't nessecarily mean that $c\in(a,b)$. Consider $$\vert w'(t)\vert = \vert ie^{it}\vert = 1$$ Then $$w'(c) = \frac{w(b) - w(a)}{b-a} = \frac{w(2\pi)-w(0)}{2\pi - 0} = \frac{e^{i2\pi}-e^{i0}}{2\pi} = \frac{1-1}{2\pi} = 0$$ Thus there is not number $c\in(a,b)$
 
 ---
 
 