**This is a technique used when all other techniques of integration fail.**
****
For $I(\alpha) = \int _{a}^{b}f(x, \alpha) \, dx$ where $\alpha$ is a parameter and a and b are constants.
$\frac{dI}{d\alpha} = \frac{d}{d\alpha}\int _{a}^{b}f(x,\alpha) \, dx = \int _{a}^{b}\frac{\partial}{\partial \alpha}f(x,\alpha) \, dx$ 
This is also known as Leibnit'z rule.
****
For $I(\alpha) = \int _{a}^{b}f(x,\alpha) \, dx$  where $\alpha$ is a parameter and a and b are functions of parameters.
$a=f_{1}(\alpha)$
$b=f_{2}(\alpha)$
$\frac{d}{d\alpha}\int _{a}^{b}f(x,\alpha) \, dx = \int _{a}^{b} \frac{\partial}{\partial \alpha}f(x,\alpha) \, dx + f(b,\alpha)\frac{db}{d\alpha}-f(a,\alpha)\frac{da}{d\alpha}$
This is also known as Leibnit'z rule for parameter functions.
****
**Steps to find integral using DUIS**
1. Let I equal to given integral.
2. Differentiate both sides with respect to a ( parameter ).
3. Apply DUIS rules.
4. Integrate I' to get function with a.
5. Put suitable value of a such that I = 0.

[[Integral Calculus]]