**Continuous mass distribution:**
$$
\bar{x} = \frac{\int x \, dm }{\int  \, dm }
$$
$$
\bar{y}=\frac{\int y \, dm }{\int  \, dm }
$$
$$
\bar{z}=\frac{\int z \, dm }{\int  \, dm }
$$
****
**Centre of gravity of an arc:**
$y=f(x)$, $ds$ be elementary arc at point $P(x,y)$.
If $\rho$ is density at point $P(x,y)$ then mass of this element is: $dm=\rho ds$
Thus centre of gravity will be:
$$
\bar{x}=\frac{\int x\rho \, ds }{\int \rho \, ds }
$$
$$
\bar{y}=\frac{\int y\rho \, ds }{\int \rho\, ds }
$$

Note:
1. If $y=f(x)$ then $ds=\sqrt{ 1+\left( \frac{dy}{dx} \right)^2 }dx$
2. If $x=f(y)$ then $ds=\sqrt{ 1+\left( \frac{dx}{dy} \right)^2 }dy$
3. If $x=f_{1}(t), y=f_{2}(t)$ then $ds=\sqrt{ \left( \frac{dx}{dt} \right)^2+\left( \frac{dy}{dt} \right)^2 }dt$
4. If $r=f(\theta)$ then $ds=\sqrt{ r^2+\left( \frac{dr}{d\theta} \right)^2 }d\theta$
5. If $\theta=f(r)$ then $ds=\sqrt{ 1+r^2\left( \frac{d\theta}{dr} \right)^2 }dr$
****
**Centre of gravity of plane lamina:**
If $\bar{x},\bar{y}$ are co-ordinates of centre of gravity of plane bounded by curve C and density $\rho$, then $dm=\rho dA$, $dA=dxdy$
Thus centre of gravity will be:
$$
\bar{x}=\frac{\iint_{R}x\rho dxdy}{\iint_{R}\rho dxdy}
$$
$$
\bar{y}=\frac{\iint_{R}y\rho dxdy}{\iint_{R}\rho dxdy}
$$
For polar form, put $dA=r d\theta dr$, $x=r\cos\theta$, $y=r\sin \theta$:
$$
\bar{x}=\frac{\iint_{R}r\cos\theta\rho r{d\theta dr}}{\iint_{R}\rho rd\theta dr}
$$
$$
\bar{y}=\frac{\iint_{R}r\sin \theta\rho r d\theta dr}{\iint_{R}\rho r d\theta dr}
$$
****
**Centre of gravity of solid:**
Put $dm=\rho dv=\rho dxdydz$
$$
\bar{x}=\frac{\iiint_{V}x\rho dxdydz}{\iiint_{V}\rho dxdydz}
$$
$$
\bar{y}=\frac{\iiint_{V}y\rho dxdydz}{\iiint_{V}\rho dxdydz}
$$
$$
\bar{z}=\frac{\iiint_{V}z\rho dxdydz}{\iiint_{V}\rho dxdydz}
$$
For polar form:
Put $x=r\sin \theta \cos \phi$, $y=r\sin\theta \sin \phi$, $z=r\cos \theta$
For cylindrical form:
Put $x=u\cos \phi$, $y=u\sin \phi$, $z=z$

[[Application of multiple integration]]