Change of variables in double integrals by Jacobian
*Theorem:* Let R and S be regions of xy plane and uv plane respectively. Let $x=g(u,v)$ and $y=h(u,v)$ be two transformations such that each point in R has unique image in S. If $f(x,y)$ is continuous on R and $J=\frac{\delta(x,y)}{\delta(u,v)}\neq 0$ on R then 
$$
\iint_{R}f(x,y)dxdy=\iint_{S}f[g(u,v),h(u,v)]|J|dudv
$$
Where 
$$
dxdy=|J|dudv=\begin{vmatrix}
\frac{\delta x}{\delta u}&\frac{\delta x}{\delta v} \\ \\
\frac{\delta y}{\delta u}&\frac{\delta y}{\delta v}
\end{vmatrix} dxdy
$$
****
Includes:
1. Area under curves
2. Volume under curves
3. Centre of gravity
4. Moment of inertia
[[Multiple Integration]]