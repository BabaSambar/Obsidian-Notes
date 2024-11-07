
_**Determination of limits of individual integrals**_

**Case 1 : When R is rectangle**
![[Rectangle limit double integral.png]]
R = $\{ (x,y): a\leq x \leq b, c\leq y\leq d \}$
$$
\iint_{R}f(x,y)dxdy=\int _{a}^{b} \left[ \int _{c}^{d}f(x,y) \, dy  \right]dx = \int _{c}^{d} \left[ \int _{a}^{b}f(x,y) \, dx  \right]\, dy 
$$
If limits of integrals are constants, the order of integration is not important.

**Case 2 : When R is not a rectangle**
1. If inner limits are functions of x:
![[Vertical strip for double integration.png]]
In this case, draw the strip parallel to y-axis within region R.
The lower end of strip touches the curve $y=\phi_{1}(x)$ and upper curve touches the curve $y=\phi_{2}(x)$.
Thus:
$$
\iint_{R}f(x,y)dxdy=\int _{x=a}^{x=b}\left[ \int _{y=\phi_{1}(x)}^{y=\phi_{2}(x)}f(x,y) \, dy  \right] \, dx 
$$
2. If inner limits are function of y:
![[Horizontal strip for double integration.png]]
In this case, draw strip parallel to x-axis within region R.
The lower end of the strip touches the curve $x=\phi_{1}(y)$ and upper end touches the curve $x=\phi_{2}(y)$.
Thus:
$$
\iint_{R}f(x,y)dxdy=\int _{y=c}^{y=d}\left[ \int _{x=\phi_{1}(y)}^{x=\phi_{2}(y)} f(x,y)\, dx  \right] \, dy 
$$

[[Double integration]]