#eternal 
Given a direct lattice of points **$R$**, a point G is a point in the reciprocal lattice *if and only if* $$e^{iG\cdot R}=1$$
The inner product should either be $0$ or $2\pi n$.j

We *claim* that the primitive lattice vectors of reciprocal lattice $b_{i}$ are defined to have to following property $$a_{i} \cdot b_{j} = 2\pi \delta_{ij}$$
if we construct $b_{i}$ in the following way: $$b_{1}=\frac{2\pi a_{2}\times a_{3}}{a_{1}\cdot (a_{2}\times a_{3})}$$
permute the index. It's obvious that, for example, $$a_{1}\cdot b_{1} = 2\pi$$ $$a_{2}\cdot b_{1} = 0$$

In this definition, we have $G\cdot R=m_{1}n_{1}+m_{2}n_{2}+m_{3}n_{3}$, where $G$ and $R$ are the combination of promitive lattice vectors $b_{i}$ and $a_{i}$, respectively: $$G = m_{1}b_{1}+m_{2}b_{2}+m_{3}b_{3}$$
$$R = n_{1}a_{1}+n_{2}a_{2}+n_{3}a_{3}$$
$n_{i}$ is integer, then $m_{i}$ has to be integer.

Using the Poisson summation formula, we have the equation $$F[\rho (r)]=\sum_{R}e^{ik\cdot R}=\frac{(2\pi)^D}{v}\sum_{G}\delta^D(k-G)$$
where $\rho(r)$ represent the points of real lattice (delta function), while $\delta^{D}(k-G)$ only diverges at reciprocal lattice points.

For periodic $\rho(r)$, $\rho(r)=\rho(r+R)$ for any lattice vector $R$. We have $$F[\rho (r)]=\sum_{R}\int_{unit-cell}e^{ik\cdot (x+R)}\rho(x+R)=(2\pi)^D\sum_{G}\delta^D(k-G)S(k),$$
where $S(k)=\int_{unit-cell}dx\ e^{ik\cdot x}\rho(x)$ is the structure factor.

So now we can describe the periodic functions of real lattice in the language of reciprocal lattice.

When we have a 2D or 3D reciprocal lattice, to present the spectrum with 1D $k$ parameter, sometimes we draw the spectrum along a line coneecting some important points in the $k$-space. The graph we get is called [[Spaghetti Diagram]].


