## Theorem
Suppose $f \in L^1$, the set of functions with finite [[Lebesgue integral]]. Then for every $\varepsilon > 0$, there exists a set $E$ of finite [[Lebesgue measure]] such that $$\int_{E^C} |f| < \varepsilon.$$
## Proof
Let $B_k$ be the ball in $\mathbb R^n$ of radius $k$ for $k \in \mathbb N$, and let $f_k(x) = f(x) \chi_{B_k}(x)$, where $\chi_{B_k}$ is the [[characteristic function]] of $B_k$. Then for all $k$, $$\text{im}(\text{supp}((f_k))\subseteq \text{im}(\text{supp}((f_{k+1}))$$ where $\text{im}(f)$ denotes the [[image]] of $f$ and $\text{supp}(f)$ denotes its [[support]]. Without loss of generality, assume that $f \geq 0$. We have $\lim\limits_{k\to\infty} f_k(x) = f(x)$, so by the [[monotone convergence theorem]], $$\lim_{n\to\infty} f_kd\mu = \int fd\mu.$$ By the [[additivity of limit|additivity of the limit]], it [[sequence convergence|follows]] that for all $\varepsilon > 0$, there exists $k_0$ such that $$\int_{B_{k_0}^C}fd\mu = \int(f-f_n)d\mu < \varepsilon.$$ QED.