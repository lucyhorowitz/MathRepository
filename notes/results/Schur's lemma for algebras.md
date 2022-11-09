---
aliases: central character
---
## Theorem
Let $A$ be an [[algebra over a field|algebra]] over $\mathbb C$ of at most [[countable]] [[dimension of vector space|dimension]] as a $\mathbb C$-[[vector space]] and let $M$ be a [[simple module|simple]] $A$-module. Then
1. The only [[endomorphism|endomorphisms]] of $A$ are scalars. That is, [[module homomorphisms form a ring|the]] [[ring]] $\text{End}_A(M) =\mathbb C\cdot\text{id}_M \cong \mathbb C$.
2. The [[center of an algebra]] of $A$ "acts on $M$ by scalars." That is, there is an [[algebra homomorphism]] $\chi_M:Z(A) \to \mathbb C$ called the **central character** of $M$ such that $zm=\chi_m(z) \cdot m$ for all $z\in Z(A)$ and $m\in A$. 

## Proof
1. The fact that [[modules over countable-dimension algebras have countable dimension]] applied to our $M$ and $A$ implies that $\text{End}_A(M)$ is a $\mathbb C$-[[algebra over a field|algebra]] of [[cardinal number|at most]] [[countable]] [[dimension of vector space|dimension]] over $\mathbb C$. Then (1) follows from [[Schur's lemma for rings]] and the [[Spectral Theorem]].
2. Now let $z\in Z(A)$ and note that the function $f:M\to M$ given by $m\mapsto zm$ is an $A$-[[module homomorphism]]. Moreover, $$f(am) = z(am) = a(zm) = af(m)$$ for all $a\in A$ and $m\in M$. Thus by (1) there exists $\chi_M(z)\in\mathbb C$ such that for all $m\in M$, $zm = \chi_M(z)\cdot m$. For any $z,z'\in Z(A)$, we have $$\begin{align*}\chi_M(z+z') &= (z+z')m \\&=zm+z'm \\&= \chi_M(z)m+\chi_M(z')m\\&= (\chi_M(z)+\chi_M(z'))m\end{align*}$$ and $$\begin{align*}\chi_M(zz')m\\ &= (zz')m \\&= z(z'm) \\&= \chi_M(z)(z'm)\\&=\chi_M((\chi_M(z')m)\\&= (\chi_M(z)\chi_M(z'))(m).\end{align*}$$ If we let $m\neq 0$, it follows that $\chi_M(z+z') = \chi_M(z)+\chi_M(z')$ and $\chi_M(zz') = \chi_M(z)\chi_M(z')$ making $z\mapsto \chi_M(z)$ an [[algebra homomorphism]], as desired.