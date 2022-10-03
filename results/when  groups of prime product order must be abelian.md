## Theorem
Let $p$ and $q$ be primes such that $p > q$. Then unless $p \equiv 1\pmod q$, every [[group]] of [[order of a group|order]] $pq$ must be [[abelian]].
## Proof
Let $G$ be a [[group]] of order $pq$ and let $n_p(G)$ be the number of [[Sylow p-subgroup|p-Sylow subgroups]] of $G$. By the [[Sylow theorems]], we know that $n_p(G)$ divides $q$ and $n_p(G) \equiv 1\pmod p$. Because $q$ is prime, this implies that $n_p(G) = 1$ and [[unique p-Sylow subgroups are normal|therefore]] it is [[normal subgroup|normal]] in $G$. Denote this group by $P_p$. 

Let $P_q$ be a [[Sylow p-subgroup|q-Sylow subgroup]] of $G$. Because $P_p$ is [[normal subgroup|normal]], we can define $\rho: P_q\to \text{Aut}(P_p)$ an [[group action|action]] of $P_q$ on $P_p$ given by $\rho(a)\cdot x = axa^{-1}$ for $x\in P_p$ and $a\in P_q$. Because $q$ does not divide the [[order of a group|order]] of the [[automorphism group]] of $P_p$ (it is $p-1$),  this means that $\rho$ is trivial for all $a\in P_q$ and $x\in P_p$. Thus $axa^{-1}=x$, and $G$ is [[abelian]].  

The map $P_p\times P_q\to G$ given by $(x,a)\mapsto xa$ is a [[group homomorphism]].

If the non[[abelian]] group exists, then it is unique.