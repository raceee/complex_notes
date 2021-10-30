#chapter3 
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