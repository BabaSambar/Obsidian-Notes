**The gamma function ( Euler's second integral ) is defined as:**
$\Gamma(n) = \int _{0}^{\infty} x^{n-1}e^{-x}\, dx$  for n > 0
****
**Properties of gamma function**
1. $\Gamma(n) = (n-1)!$
2. $\Gamma(n) = n\Gamma(n-1)$
3. $\Gamma(0) = \infty$
4. $\Gamma(n)=\int _{0}^{\infty} e^{-x^2}x^{2n-1} \, dx$
5. $\Gamma\left( \frac{1}{2} \right) = \sqrt{ \pi }$ 
6. $\int _{0}^{\infty} e^{-kx}x^{n-1} dx = \frac{\Gamma(n)}{k^n}$
7. $\Gamma(P)\Gamma(1-P) = \frac{\pi}{\sin P\pi}$
8. $\int_{0}^{\infty}e^{-x^m}x^{mn-1} \, dx = \frac{\Gamma(n)}{m}$
9. $\int _{0}^{\infty}\frac{x^n}{a^x} \, dx = \frac{\Gamma(a+1)}{{\ln a}^{n+1}}$
****
**Examples reducible to standard form**
1. For $\int _{0}^{\infty}e^{-ax^m}x^n \, dx$ substitute $ax^m = t$ and use definition of gamma function.
2. For $\int _{0}^{\infty}a^{bx^2}x^n \, dx$ put $a^{bx^2} = e^{-t}$ and use gamma function.
3. For $\int _{0}^{1}\log(ax)^mx^n \, dx$ put $ax = -t$ and use gamma function.
****
**Duplication formula of gamma function**
$\Gamma(m)\Gamma\left( m+\frac{1}{2} \right) = \frac{\sqrt{ \pi }}{2^{2m-1}}\Gamma(2m)$

[[Integral Calculus]]