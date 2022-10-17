## Theorem (for [[group|groups]])
Let $p_1^{k_1}p_2^{k_2}\cdots p_r^{k_r} = N$ be [[prime factorization is unique|prime factorization]] of $N\in \mathbb N$. For natural numbers $m,n$ such that $m$ divides $n$, define a [[group homomorphism]] $\pi_{m,n}:\mathbb Z/n\mathbb Z\to\mathbb Z/m\mathbb Z$ given by $$\pi_{m,n} (u + n\mathbb Z) = (u + \mathbb m\mathbb Z)$$ for all $u \in \mathbb Z$. That is, we send the [[left coset]] of $u$ in $\mathbb Z/n\mathbb Z$ to the [[left coset]] of $u$ in $\mathbb Z/m\mathbb Z$. Now for $M = M_1M_2$, we get a [[group homomorphism]] $\mathbb Z/M\mathbb Z\to (\mathbb Z/M_1\mathbb Z\times \mathbb Z/M_2\mathbb Z)$ given by $$c\mapsto (\pi_{M,M_1}(c), \pi_{M,M_2}(c)).$$ If $M_1$ and $M_2$ are [[coprime]], then this is an [[group homomorphism|isomorphism.]]

Applying [[induction]], we obtain an [[group homomorphism|isomorphism]] with the [[direct sum]] $$\mathbb Z/N\mathbb Z \to \bigoplus_{i=1}^r \mathbb Z/p_i^{k_i}\mathbb Z$$ given by $$c\mapsto (\pi_{N,p_1^{k_1}}(c),\cdots \pi_{N,p_r^{k_r}}(c)).$$
## Proof
#write_proof Just need to show that the things we claim are [[group homomorphism|homomorphisms]] are yes and then do the [[induction]].

## Theorem (for [[ring|rings]])
Let $R$ be a [[commutative]] [[ring]] and let $\{I_i\}_{i=1}^n$ be a collection of [[ring ideal|ideals]] of $R$ that are pairwise [[comaximal ring ideals|comaximal]]. Then $$R/\left(\bigcap_{i=1}^n I_i\right) = \bigoplus_{i=1}^n R/I_i.$$ Moreover, the [[intersection of ring ideals is an ideal|intersection]] of the $I_i$ is [[ring homomorphism|isomorphic]] to their [[product of ring ideals|product]]: $$\bigcap\limits_{i=1}^n I_i\cong\prod_{i=1}^n I_n.$$ The [[ring homomorphism|isomorphism]] is given by $$r + \left(\bigcap\limits_{i=1}^n I_i\right) \mapsto (r + I_1, \dots, r+I_n).$$
## Proof
#write_proof [[induction]] [[kernel of ring homomorphism]] [[surjective]] [[first isomorphism theorem for rings]]