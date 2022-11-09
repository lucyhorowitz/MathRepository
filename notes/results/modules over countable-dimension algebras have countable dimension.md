## Theorem
Let $A$ be an [[algebra over a field|algebra]] over the [[field]] $\mathbb k$ with at most [[countable]] [[dimension of vector space|dimension]] as a $\mathbb k$-[[vector space]]. Let $M$ be a [[simple module|simple]] $A$-[[module over a ring|module]]. Then $M$ and [[module homomorphisms form a ring|the]] [[ring]] $\text{End}_A(M)$ of [[module homomorphism|module homomorphisms]] also have at most [[countable]] [[dimension of vector space|dimension]] over $\mathbb k$. 

## Proof
Note that $\text{End}_\mathbb{k}(M)$ [[module homomorphism|is]] a [[ring]], but it is also an [[algebra over a field|algebra]] over $\mathbb k$. Moreover, $\text{End}_A(M)$ is a [[subalgebra]] of $\text{End}_\mathbb{k}(M)$. 

Choose nonzero $m\in M$. Then we have two [[linear transformation|linear]] maps: $$\ell:A\to M, \quad \ell:a\mapsto am$$ and $$r:\text{End}_A(M), \quad f\mapsto f(m).$$ Since $Am$, the [[generate an R-module|generated]] by $m$, is a [[submodule]] of the [[simple module]] $M$, it follows that $Am = M$. Thus $\ell$ is [[surjective]], and the [[dimension of vector space|dimension]] $\dim_\mathbb k M$ is [[cardinal number|less than or equal to]] $\dim_\mathbb k A$.

Now let $f\in \text{End}_A(M)$ be such that $r(f) = f(m) = 0$. Then $f(am) = af(m) =0$ for all $a\in A$. This implies that $f(M) = f(Am) = 0$, and in particular that $f=0$. Thus $r:f\mapsto f(m)$ is [[injective]], so we have this total [[cardinal number|cardinal]] inequality $$\dim_\mathbb k(\text{End}_A(M) \leq \dim_\mathbb k M \leq \dim_\mathbb k A.$$