## Theorem
Let $(X,\Sigma,\mu)$ be a [[measure space]] and let $\pi$ be the [[positive variation]] of $\mu$ and $\nu$ the [[negative variation]]. Then $X = P \cup N$ where $P$ and $N$ are disjoint sets such that for every $A\in\Sigma$ with $A\subseteq P$, we have $\nu(A) = 0$ and similarly for $\pi$, with every [[measurable]] subset of $N$ being $\pi$-null.
## Proof
Let $\{A_n\}_{n\in\mathbb N}$ be a sequence of [[measurable]] sets such that $\mu(A_n) \geq \pi(X) - \frac{1}{2^n}$. We define $P$ in terms of the [[limit supremum]] of the $A_n$: Let $$P = \limsup_{n\to\infty} A_n = \bigcap_{n\in\mathbb N} \bigcup_{k=n}^\infty A_k$$ so that $x \in P$ if and only if $x$ is in infinitely many of the $A_n$. Let $N = X\setminus P$. Suppose for the sake of contradiction that there exists [[measurable]] $B\subset P$ such that $\nu(B) > 0$. Choose $n_0$ so that $\sum\limits_{k=n_0}^\infty \frac{1}{2^k} < \nu(B)$, which can be done because the [[tail of convergent series converges to zero|tail of the series goes to zero]]. By definition of $A_n$, it follows that $$\nu(A_n) \leq \frac{1}{2^n} + \pi(A_n) -\pi(X) \leq \frac{1}{2^n}.$$ Because $B\subset P$, we have $B \subset\bigcup\limits_{k=n_0}^\infty A_k$. Thus by [[monotonicity of measure]], $$\nu(B)\leq \sum_{k=n_0}^\infty \nu(A_k)\leq \sum_{k=n_0}^\infty \frac{1}{2^k}< \nu(B),$$ a contradiction. A similar argument holds for $\pi$.   