## Theorem
Let $(X,\Sigma, \mu)$ be a [[measure space]] and let $f \in$ [[Lp space|L]]$_1(X,\mu)$. Then for all $\varepsilon > 0$, there exists $\delta > 0$ such that $$\int_A |f|\text d\mu < \varepsilon$$ for every $A$ such that $\mu(A) < \delta$.
## Proof
Let $g_n = \begin{cases}f(x) & |f(x)| \leq n \\ 0 & \text{ otherwise.} \end{cases}$ Then the $g_n$ [[pointwise convergence|converge pointwise]] to $|f|$, and moreover $|g_n| \leq f$ for all $n$. So by the [[dominated convergence theorem]], we have $\int |g_n|\text d\mu \to \int |f|\text d\mu$, which [[limit of difference is difference of limits|implies]] that $$I_n = \int_{\{x\mid |f(x)| > n\}}|f|\text d\mu = \int |g_n - f|\text d\mu  \to 0.$$ Then for all $\varepsilon > 0$, there exists $N$ such that $I_n \leq \varepsilon$ for all $n \geq N$. Let $\delta = \mu(\{x\mid |f(x)| > N\})$. 

The set $\{x\mid |f(x)| > N\}$ is one set of [[measure space|measure]] $\delta$ that works, but we must show that the result holds for all sets of measure less than or equal to $\delta$. 

Consider such a set $A$. Then $$\begin{align*}\int_A |f|\text d\mu &= \int_{A\cap \{x\mid |f(x)| > N\}}|f| \text d\mu + \int_{A\setminus \{x\mid |f(x)| > N\}} |f|\text d\mu \\
&\leq I_N < \delta.\end{align*}$$ Intuitively, the set $\{x\mid |f(x)| > N\}$ is the set of [[measure space|measure]] $\delta$ on which $|f|$ takes the largest possible values, so its integral will be as large as possible.