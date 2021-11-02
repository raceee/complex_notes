#chapter3
We must now go over the identities and derivatives of the popular inverse trig functions. Suppose that we have two complex variables namely $w$ and $z$. We write $$w = \sin^{-1} z \quad \quad z = \sin w$$

Recalling the construction of $\sin$ $w = sin^{-1} z$ when $$z = \frac{e^{iw} - e^{-iw}}{2i}$$
We can solve this equation and put it in the form $$(e^{iw})^2 - 2iz(e^{iw}) - 1 = 0$$ Then solving for $e^{iw}$ $$e^{iw} = iz + (1 -z^2 )^{1/2}$$ Where $(1-z^2)^{1/2}$ is, of course, a double-valued function of $z$. Taking logarithms of each side of equation (1) and recalling that $w = \sin^{-1}z$, we arrive 
$$\sin^{-1} z = -i\log[iz + (1-z^2 )^{1/2}$$
and following soon after
$$\cos^{-1} z = -i\log [z + i(1-z^2 )^{1/2}]$$
$$\tan^{-1} z = \frac{i}{2}\log \frac{i+z}{i-z}$$ The derivatives of these functions are as follows

$$\frac{d}{dz}\sin^{-1} z = \frac{1}{(1-z^2)^{1/2}}$$
$$\frac{d}{dz}\cos^{-1} z = \frac{-1}{(1-z^2)^{1/2}}$$
$$\frac{d}{dz}\tan^{-1} z = \frac{1}{1 + z^2}$$

---

The inverse sign is a multivalued function since it has a [[logarithm function]] with in it (much like the [[trig functions]]). Meaning that we need to choose a [[branch]] to make it a single value.
$$\sin^{-1} (z) = -i\log [iz + (1 - z^2 )^{1/2}]$$ $$\cos^{-1}(z) = -i\log[z + i(1-z^2)^{1/2}]$$
$$\tan^{-1}(z) = \frac{i}{2}\log\frac{i+z}{i-z}$$
The derivatives of these are 

$$\frac{d}{dz}\sin^{-1}z = \frac{1}{(1-z)^{1/2}}$$
$$\frac{d}{dz}\cos^{-1}z = \frac{-1}{(1-z^2)^{1/2}}$$
$$\frac{d}{dz} \tan^{-1}z = \frac{1}{1 + z^2}$$


## Homework Question in Section 40
Derive $\sin^{-1}z$
$$\sin^{-1}z = -\log[iz + (1 - z^2 )^{1/2}$$
$$\frac{d}{dz}\sin^{-1}z = -i\frac{d}{dz}\log(iz + (1 - z^2 )^{1/2}$$
Derivative of $\log$ is $1/z$ so we use the chain rule.

$$= -i\frac{1}{[iz + (1 - z^2)^{1/2}]} *\frac{d}{dz}[iz + (1 - z^2 )^{1/2}]$$

$$= -i\frac{1}{[iz + (1 - z^2)^{1/2}]}(i + \frac{1}{2}(1 - z^2)^{-1/2}(-2z))$$
Resulting
$$= \frac{1}{(1 - z^2)^{1/2}}$$