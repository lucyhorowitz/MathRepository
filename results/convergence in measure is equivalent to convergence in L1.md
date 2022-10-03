## Theorem
Let $(X,\Sigma,\mu)$ be a (finite) [[measure space]] and let $\{f_n\}_{n\in\mathbb N}$ be a sequence of functions $f_n: X\to \mathbb R$ such that there exists $g\in L_1(\mu)$ for which $|f_n|\leq g$ for all $n$. Then $f_n$ [[sequence convergence|converges]] to $f \in$ [[Lp space|L]]$_1(\mu)$ if and only if $f_n$ [[convergence in measure|converges in measure]] to $f$.

## Proof
Suppose that $f_n$ [[sequence convergence|converges]] to $f$ in $L_1(\mu)$. Fix $n \in\mathbb N$ and $\varepsilon > 0$ and define the set $$E_{n,\varepsilon} = \{x \mid |f_n(x) - f(x) | > \varepsilon\}.$$ Since $f_n \to f$ in $L_1(\mu)$, we know that $||f_n-f||_1 \to 0$ as $n \to \infty$. Moreover, $$||f_n-f||_1 = \int_X |f_n-f| \text d\mu \geq \int_{E_{n,\varepsilon}} |f_n -f| = \varepsilon\mu(E_{n,\varepsilon})$$ because of the [[monotonicity of the integral]] and the fact that $E_{n,\varepsilon} \subseteq X$. We then have $$\mu(E_{n,\varepsilon}) \leq \frac{||f_n-f||_1}{\varepsilon}.$$ For every $\varepsilon$, we then have as $\mu(E_{n,\varepsilon})\to 0$ as $n \to \infty$, as desired.

Now suppose that $f_n$ [[convergence in measure|converges in measure]] to $f$. Fix $n \in\mathbb N$ and $\varepsilon > 0$ and define the set $$E_{n,\\varepsilon} = \{x \\mid |f_n(x) - f(x) | > \varepsilon\}.$$ Let $M = \int_X |2g|$, where $g$ is the function given in the problem statement that dominates the $f_n$. Then 

$$\begin{align*}

||f_n-f||_1 &= \int_X |f_n-f|\text d\mu \\

&=\int_{E_{n,\varepsilon}} |f_n-f|\text d\mu + \int_{X\setminus E_{n,\varepsilon}} |f_n-f| \text d\mu \\

&< int_{E_{n,\\varepsilon}} |f_n-f|\text d\mu + \varepsilon \mu(X\setminus E_{n,\varepsilon})\\

&\leq M\mu(E_{n\varepsilon}) + \varepsilon\mu(X\setminus E_{n,\varepsilon}) \\

&\leq M\mu(E_{n,\varepsilon}) + \varepsilon \mu(X) \\

&= M\mu(E_{n,\varepsilon}) + \varepsilon.

\end{align*}$$

Because $f_n$ converges to $f$ in measure, the first term in the last line can be made small by appropriate choice of $n$, and the second term in the last line can be made small by appropriate choice of $\varepsilon$. 
