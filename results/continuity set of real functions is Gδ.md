## Theorem
For every function $f:\mathbb R\to \mathbb R$, the set $X$ of points at which $f$ is [[continuous]] is [[Gδ]].
## Proof
If $x \in X$, then for all $n \in \mathbb N$ there exists by definition of [[continuous|continuity]] an [[open]] neighborhood $U_{x,n}$ of $x$ such that $$|f(x)-f(y)| < \frac{1}{n}$$ for all $y \in U_{x,n}$. Fix $n$, and let $$V_n = \bigcup_{x\in X} U_{x,n}.$$ This set is [[open]] as the union of [[open]] sets. Then let $$V = \bigcap_{n\in\mathbb N} V_n = \bigcap_{n\in\mathbb N}\bigcup_{n\in\mathbb N} U_{x,n}.$$ This is a [[Gδ]] set.

Let $y \in X$. Then $y \in U_{x,n}$ for all $n$, so it is in $V_n$ for all $n$, and therefore it is in $V$. Thus $X \subseteq V$. Now let $y \in V$. Then for all $n$, $y \in V_n$. Thus there exists $x \in X$ such that for every $n$, $y \in U_{x,n}$, and therefore $y \in X$. Thus $V \subseteq X$, and consequently $V=X$, QED.