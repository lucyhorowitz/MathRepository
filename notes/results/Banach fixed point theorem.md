## Theorem
Let $(X,\rho)$ be a [[complete metric space]] and let $T: X\to X$ be a [[contraction mapping]]. Then $T$ has a unique fixed point, i.e. there exists unique $x_0 \in X$ such that $T(x_0) = x_0$.
## Proof
Let $x_0 \in X$ and define the sequence $\{x_n\}_{n\in\mathbb N}$ by $x_{n+1} = f(x_n)$.
- For $n \geq 1$, we have $\rho(x_n, x_{n+1})< r^n\rho(x_0,x_1)$.
- $f$ is [[continuous]]:
	- $f$ is [[Lipschitz]] continuous.
- $x_n$ converges to some $x \in X$:
	- $x_n$ is clearly [[Cauchy sequence|Cauchy]]. 
	- $X$ [[complete metric space|complete]] implies the existence of a [[sequence convergence|limit]] in $X$ for every [[Cauchy sequence|Cauchy]] sequence.
- $f(x_n)$ [[sequence convergence|converges]] to $f(x)$:
	- $f$ is [[continuous]].
	- [[continuous functions preserve limits in metric spaces|Continuous functions send convergent sequences to convergent sequences.]]
- $x = \lim\limits_{n\to\infty} x_n = \lim\limits_{n\to\infty} f(x_{n-1}) = f(x)$.


Suppose $y\in X$ is a fixed point of $f$ but that $x\neq y$.
- $\rho(x,y) = \rho(f(x),f(y)) < r\rho(x,y)$:
	- This follows from the definition of [[contraction mapping]].
	- This contradicts the fact that $r<1$. 
- $x = y$.

QED