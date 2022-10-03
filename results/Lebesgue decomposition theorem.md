## Theorem
Let $(X,\Sigma)$ be a [[measurable|measurable space]] and let $\mu$ and $\nu$ be nonnegative, finite [[measure space|measures]] on $(X,\Sigma)$. Then $\nu$ can be decomposed into a [[singular measure|singular]] part and an [[absolute continuity of measure|absolutely continuous]] part with respect to $\mu$. That is, there exist [[measure space|measures]] $\nu_a$ and $\nu_s$ such that $\nu = \nu_a+\nu_s$ and $\nu_a \ll \mu$ and $\nu_s \perp \mu$. 
## Proof
Let $\mathcal N\subset \Sigma$ be the collection of sets $N$ for which $\mu(N)=0$. Let $\{A_n\}_{n\in\mathbb N}$ be a sequence of sets in $\mathcal N$ converging to a $\mu$-null set whose $\nu$-measure is $\sup\limits_{A\in \mathcal N}\nu(A).$ One such set is $A = \bigcup\limits_{n\in\mathbb N} A_n$. Now let $$\nu_s(B) = \nu(A\cap B) \text{ and } \nu_a(B)= \nu((X\setminus A)\cap B).$$ We have that $\mu\equiv 0$ outside $X\setminus A$ and $\nu_s\equiv 0$ outside $A$, so clearly $\mu$ and $\nu_s$ are [[singular measure|singular.]] Now let $B$ be a set with $\mu(B)=0$, and suppose for the sake of contradiction that $\nu_a(B) > 0$. Then $\nu((X\setminus A)\cap B) > 0$, which implies that $\mu(((X\setminus A)\cap B))\cup A) = 0$ and $\nu(A) < \nu(((X\setminus A) \cap B))\cup A)$, contradicting the definition of $A$ as the $\mu$-null set with the largest $\nu$-[[measure space|measure]]. Thus $\nu_a\ll \mu$.