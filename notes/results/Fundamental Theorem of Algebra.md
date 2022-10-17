## Theorem
Let $n>0$ and let $$f(x) = x^n + c_1x^{n-1} + \cdots + c_{n-1}x + c_n$$ be a [[monic polynomial|monic]] [[polynomial]] of [[degree of polynomial|degree]] $n$ with complex coefficients. Then there exist $n$ complex numbers $x_i$ such that $f(x_i)=0$ for all $1\leq i\leq n$.
## Proof (algebraic topology version)
We use an [[induction]] on the [[degree of polynomial|degree]] of $f$ argument to show that if we have one root (namely $f(x)/(x-c)$), there must be $n$ roots.

Assume that $f(x) \neq 0$ on $S^1$ so that we may define  an function $\hat f:S^1\to S^1$ as $$\hat f(x) = f(x)/|f(x)|,$$ the [[norm|normalization]] of $f$ to the unit circle. We want to calculate the [[degree of polynomial|degree]] of $\hat f$. 

Suppose that $f(x)\neq 0$ for $|x| \leq 1$. Then we can define a [[homotopy]] $h:S^1\times I\to S^1$ by $$h(x,t) = f(tx)/|f(tx)|.$$ This shows that the constant map at $f(0)/|f(0)|$ is [[homotopy|homotopic]] to $\hat f$. Since [[homotopy preserves degree]] and the constant map has [[degree of polynomial|degree]] zero, $\hat f$ must therefore be of degree zero. 

Now suppose that $f(x)\neq 0$ for all $|x| \geq 1$. Then we can define another [[homotopy]] $j:S^1 \times I\to S^1$ by $$j(x,t) = k(x,t)/|k(x,t)|$$ where $$k(x,t) = t^nf(x/t) = x^n + t(c_1x^{n-1} + tc_2x^{n-2} + \cdots + t^{n-1}c_n).$$ Note that $k(x,0) = x^n$ and $k(x,1) = f(x)$.  Thus $j$ is a homotopy from $f$ to $\hat f$, meaning that the degree of $\hat f$ is $n$. 

It cannot be true that $\hat f$ is of degree $0$ and degree $n$, so $\hat f$ must be zero somewhere on $\mathbb C$. 