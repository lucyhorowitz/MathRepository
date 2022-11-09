## Theorem 
Let $A$ be an [[algebra over a field|algebra]] over an [[algebraically closed]] [[field]] $\mathbb k$ and let $V$ and $M_i$ for $1\leq i\leq p$ be [[simple group|simple]] $A$-[[module over a ring|modules]]. The [[multiplicity of simple module in semisimple module|multiplicity]] of $V$ in $M = \bigoplus_i M_i$  does not depend on a choice of decomposition into $M_i$. \

## Proof

Under the conditions above, we have a [[canonical isomorphism of module homomorphisms of sums of modules|canonical isomorphism]] of [[vector space|vector spaces]] $$\text{Hom}_A\left(V, \bigoplus_{i=1}^pM_i\right) \cong \bigoplus_{i=1}^p \text{Hom}_A(V,M_i).$$ By [[Schur's lemma for algebras]], we have that the [[dimension of vector space|dimension]] $$\dim_\mathbb k(\text{Hom}_A(V,M_i)) = \begin{cases}1 & V\cong M_i \\ 0 &V\not\cong M_i \end{cases}$$ so that $$\dim_\mathbb k(\text{Hom}_A(V,M)) = \sum_{i=1}^p \dim_\mathbb k(\text{Hom}_A(V,M_i)) = \Big|\{M_i \mid M_i\cong V\}\Big|.$$