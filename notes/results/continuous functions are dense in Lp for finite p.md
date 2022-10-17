## Theorem
Let $(X,\Sigma,\mu)$ be a [[regular]] finite [[measure space]] and let $1 \leq p < \infty$. Then the [[continuous]] functions in $\mathbb R^n$ are [[dense]] as a subset of [[Lp space|Lp]]. #todo: are these the right conditions?
## Proof
For any $A\subset X$, we will show that the [[characteristic function]] $\chi_A$ can be approximated by a continuous function. Then because the [[simple functions are dense in Lp]], we will have the result.

Given $\varepsilon > 0$, choose sets $K,G\subset X$ such that $K$ is [[compact]], $G$ is [[open]], $K\subset A\subset G$, and $\mu(G) -\mu(K) < \varepsilon$. Using [[Lusin's theorem]], choose a [[continuous]] function $f:X\to \mathbb R$ such that $f$ is $1$ on $K$, $0$ on $X\setminus G$, and between $0$ and $1$ elsewhere. Then $||f - \chi_A||_p\leq \varepsilon^{1/p}$, which can be made as small as desired by suitable choice of $\varepsilon$. 

Note that this is [[continuous functions are not dense in L-infinity|not true]] in $L_\infty$. 