The integral should be converted to polar form if:
1. It contains $x^2+y^2$ term
2. The region of integration is circular or elliptical boundaries
Put $x=r\cos \theta$ and $y=r\sin \theta$
And thus: $\theta=\arctan\left( \frac{y}{x} \right)$ 
And $dxdy = |J|d\theta dr=|\frac{\delta(x,y)}{\delta(r,\theta)}| = r dr d\theta$
****
The integral converts to:
$$
I=\iint_{R}F(r, \theta)r dr d\theta
$$
To find the limits of r, draw a radial strip in region of integration R from pole (r=0) over which r varies from $r_{1}=f_{1}(\theta)$ to $r_{2}=f_{2}(\theta)$
Rotate the strip from $\theta=\alpha$ to $\theta=\beta$
Thus the integral can convert into two forms:
$$
I=\int _{\theta=\alpha}^{\theta=\beta}\int _{r=f_{1}(\theta)}^{r=f_{2}(\theta)} F(r,\theta)r\, dr  \, d\theta 
$$
$$
I=\int _{r=\alpha}^{r=\beta}\int _{\theta=f_{1}(r)}^{\theta=f_{2}(r)} f(r,\theta)\, dr  \, d\theta 
$$
****
**Table of curves and their limits**
1. $x^2+y^2=a^2$ : $r=0$ to $r=a$ and $\theta=0$ to $\theta=2\pi$
2. $x^2+y^2=2ax$ or $r=2a\cos \theta$ : $r=0$ to $r=2a$ and $\theta=-\frac{\pi}{2}$ to $\theta=\frac{\pi}{2}$
3. $\frac{x^2}{a^2}+\frac{y^2}{b^2}=1$ : Put $x=ar\cos\theta$ and $y=-br\sin\theta$ and $dxdy=abr dr d\theta$, $r=0$ to $r=1$ and $\theta=0$ to $\theta=2\pi$
4. For a triangle, $y=0, x=a,x=y$ : $x=r\cos\theta = a$, $r=0$ to $r=a\sec \theta$, $\theta=0$ to $\theta=\frac{\pi}{4}$
5. For cardioid, $r=a(1+\cos\theta)$ : $r=0$ to $r=a(1+\cos\theta)$, $\theta=0$ to $\theta=2\pi$

[[Double integration]]