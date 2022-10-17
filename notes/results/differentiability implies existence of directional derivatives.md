## Proposition
Let $U \subset \mathbb R^n$ be [[open]]. Suppose $f: U\to\mathbb R^m$ is [[differentiable]] at $a\in U$. Then all [[directional derivative|directional derivatives]] of $f$ exist at $a$ and for all $v \in \mathbb R^n$, $$\frac{\partial f}{\partial v}(a) = Df(a)(v).$$
## Proof
By definition of [[differentiable|total derivative]]] and the fact that it is a [[linear transformation]], 
$$\begin{align*}0 &= \lim\limits_{h\to 0}\frac{f(a+hv) - f(a)-Df(a)(hv)}{||h||}\\&=  \lim\limits_{h\to 0}\frac{f(a+hv)-f(a)-hDf(a)(v)}{||h||} \\&= \lim\limits_{h\to 0}\frac{f(a+hv)-f(a)}{||h||} - Df(a)(v) \\ &= \frac{\partial f}{\partial v}(a) - Df(a)(v).\end{align*}$$