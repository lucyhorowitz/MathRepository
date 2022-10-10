## Theorem
Let $X$ be a [[locally compact]] [[topological space]] and let $G$ be a [[compact]] [[topological group]] [[group action|acting]]  [[continuous|continuously]] on $X$. Then for a fixed [[continuous]] function $f:X\to \mathbb C$ with [[compact support]], the map $G\to \mathbb C$ that sends $g\in G$ to any [[integral]] $\int_X fg^{-1}(x)dx$ on $X$ is [[continuous]].

## Proof
Consider the function $\phi:G\times X \to \mathbb C$ given by $\phi(g,x) = f(gx)$. Because the [[support]] of $f$ is [[compact]], so too must be the [[support]] of $\phi$ as a subset of $G\times X$. 

For all $\varepsilon > 0$ and $g_0\in G$, there exists a [[neighborhood]] of $g_0$ in $G$ such that $$\max_{x\in X} \left| \phi(g,x) - \phi(g_0,x)\right| < \varepsilon$$ which implies that $\phi$ is [[continuous]]. 

#write_proof 