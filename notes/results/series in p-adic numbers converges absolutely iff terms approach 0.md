## Theorem
Let $\{a_n\}\subset \mathbb Q_p$ be a sequence of [[p-adic field|p-adic]] numbers. Then $$\sum_{n=0}^\infty a_n$$ [[absolute convergence|converges absolutely]] if and only if the [[limit]] $$\lim_{n\to\infty}|a_n|_p = 0.$$

## Proof
The forward direction is the usual [[limit test]]. Suppose that $\lim\limits_{n\to\infty}|a_n|_p = 0$. Then given any $k\in \mathbb N$, there exists $N\in\mathbb N$ such that if $n > N$, then $|a_n|_p < p^{-k}$. Now let $m>n>N$. Then if we define the $\ell$th partial sum by $$s_\ell = \sum_{i=0}^\ell a_i$$ for any $\ell\in\mathbb N$, then $$|s_m-s_n|_p = \left|\sum_{i=n+1}^ma_i\right|_p\leq \max_{n<i\leq m}\{|a_i|_p\}< p^{-k},$$ and we have the desired result. 