#chapter4 

If $$w(t) = u(t) + iv(t)$$ Where $u$ and $v$ are real-valued, the definite integral of $w(t)$ over an interval $a\leq t\leq b$ is defined as $$\int_{a}^{b}w(t)dt = \int_{a}^{b}u(t)dt + \int_{a}^{b}v(t)dt$$ The next follows from above $$Re\int_{a}^{b} w(t) dt = \int_{a}^{b} Re[w(t)]dt$$ and $$Im\int_{a}^{b} w(t) dt = \int_{a}^{b} Im[w(t)]dt$$

It is important to note that $u(t)$ and $v(t)$ are real valued functions thus integrations is easy.

---

Complex integration holds the property of $$\int_{a}^{b} w(t) dt = \int_{a}^{c}w(t)dt + \int_{c}^{b}w(t)dt$$ Also, the fundamental theorem of calculus, involving antiderivatives, can, moreover be extended so as to apply to integrals of the above type. Suppose two functions $$w(t) = u(t) + iv(t)\quad and\quad W(t) = U(t) +iV(t)$$
are continouus ont he interval $a\leq t\leq b$. If $W'(t) = w(t)$ when $a\leq t\leq b$, then $U'(t) = u(t)$ and $V'(t) = v(t)$. Hence, in view of defintion, $$\int_{a}^{b}w(t)dt = [U(t)]_{a}^{b} + i[V(t)]_{a}^{b} = [U(b) + iV(b)] - [U(a) + iV(a)]$$ That is, $$\left.\int_{a}^{b}w(t)dt = W(b) - W(a) = W(t)\right]_{a}^{b}$$

---

###### Example
Since $$\frac{d}{dt}\left( \frac{e^{it}}{i}\right) = \frac{1}{i}\frac{d}{dt}e^{it} = \frac{1}{i}ie^{it} = e^{it}$$
We can see that $$\int_{0}^{\frac{\pi}{4}}e^{it}dt = \left.\frac{e^{it}}{i}\right]_{0}^{\pi/4} = \frac{e^{i\pi /4}}{i}-\frac{1}{i} = \frac{1}{i}\left( \cos\frac{\pi}{4} + i\sin\frac{\pi}{4} - 1\right) = \frac{1}{i}\left( \frac{1}{\sqrt{2}} + \frac{i}{\sqrt{2}} - 1\right)$$ $$= \frac{1}{\sqrt{2}} +\frac{1}{i}\left( \frac{1}{\sqrt{2}} - 1\right)$$

Since, $1/i = -i$ 
$$\int_{0}^{\frac{\pi}{4}}e^{it}dt = \frac{1}{\sqrt{2}} + i\left( -\frac{1}{\sqrt{2}} + 1\right)$$

---

The mean value theorem for inegrals does not carry over either.