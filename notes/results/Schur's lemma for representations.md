## Theorem
Let $V$ and $W$ be [[vector space|vector spaces]] over the [[field]] $\mathbb k$ and $\phi:G\to GL(V)$ and $\psi: G\to GL(W)$ be [[irreducible representation|irreducible]] [[group representation|representations]] of the [[group]] $G$. Let $T: V\to W$ be an [[morphism of group representations|intertwiner]] of $\phi$ and $\psi$. Then:
1. either $T$ is an [[linear transformation|isomorphism]] or it is identically zero;
2. if $\mathbb k = \mathbb C$ and $V=W$ is of finite [[dimension of group representation|dimension]] then the [[matrix of a linear transformation|matrix]] of $T$ is $\lambda I$ for some $\lambda \in \mathbb C$. That is, the [[morphism of group representations|intertwiners]] of $V$ with itself are the scalar operators $\lambda \text{id}_V$ for $\lambda\in \mathbb C$. 

In particular, for any two finite-[[dimension of group representation|dimensional]] complex [[irreducible representation|irreducible]] [[group representation|representations]] $V$ and $W$ of $G$, the [[dimension of vector space|dimension]] of the space of [[morphism of group representations|intertwiners]] $V\to W$ is as $$\dim_\mathbb C(\text{Hom}_G(V,W)) = \begin{cases} 0 & V\not\cong W\\ 1 & V\cong W\end{cases}$$

## Proof
This follows from the [[Schur's lemma for algebras]] applied to the [[group algebra]] $\mathbb CG$ via the [[representations are modules over group algebra|correspondence]] between [[group representation|representations]] of $G$ and [[module over a ring|modules]] over $\mathbb CG$. 