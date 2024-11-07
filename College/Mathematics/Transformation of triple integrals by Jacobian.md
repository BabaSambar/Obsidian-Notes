**Polar co-ordinates**
Put $x=r\sin \theta \cos \phi$, $y=r\sin\theta \sin \phi$, $z=r\cos \phi$ and $dxdydz=|J|d\theta d\phi dr=|\frac{\delta(x,y,z)}{\delta(r,\theta,\phi)}|=r^2\sin \theta d\theta d\phi dr$
$$
I=\iiint_{V}f(x,y,z)dxdydz=\iiint_{V}F(r,\theta,\phi)r^2\sin \theta d\theta d\phi dr
$$
****
**Cylindrical co-ordinates**
Put $x=\rho \cos \phi$, $y=\rho \sin \phi$, $z=z$ and $x^2+y^2=\rho^2$
$dxdydz=|J|d\rho d\phi dz=|\frac{\delta(x,y,z)}{\delta(\rho,\phi,z)}|d\rho d\phi dz=\rho d\rho d\phi dz$ 
$$
I=\iiint_{V}f(x,y,z)dxdydz=\iiint_{V}F(\rho,\phi,z)\rho d\rho d\phi dz
$$
****
**Some standard limits**
1. For complete sphere: $x^2+y^2+z^2=a^2$, $r$ varies from $r=0$ to $r=a$, $\theta$ varies from $\theta=0$ to $\theta=\pi$, $\phi$ varies from $\phi=0$ to $\phi=2\pi$
2. For hemisphere $x^2+y^2+z^2=a^2$ $z\geq 0$, $r$ varies from $r=0$ to $r=a$, $\theta$ varies from $\theta=0$ to $\theta=\frac{\pi}{2}$, $\phi$ varies from $\phi=0$ to $\phi=2\pi$
3. For ellipsoid $\frac{x^2}{a^2}+\frac{y^2}{b^2}+\frac{z^2}{c^2}=1$, Put $x=ar\sin \theta \cos \phi$, $y=br\sin \theta \sin \phi$, $z=cr\cos \theta$, $dxdydz=abcr^2dr d\theta d\phi$ where $r$ varies from $r=0$ to $r=1$, $\theta$ varies from $\theta=0$ to $\theta=\pi$ and $\phi$ varies from $\phi=0$ to $\phi=2\pi$

[[Triple integration]]