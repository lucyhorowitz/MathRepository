## Theorem
Let $G$ be a [[compact]] [[topological group|topological]] [[group]] and let $\rho:G\to GL(V)$ be a [[continuous group representation|continuous]] complex [[group representation|representation]] of $G$. Then the[[character of a representation|character]] of the  [[contragradient representation]] $\rho^\vee:G\to GL(V^*)$ is given by $$\chi_{\rho^\vee}(g) = \overline{\chi_\rho(g)}$$ for al $g\in G$.
## Proof
[[continuous representations are unitary with respect to some basis|Choose an]] [[orthonormal]] [[basis]] for $V$ and by abuse of notation, write $g$ for $\rho(g)$. Write the [[matrix of a linear transformation|matrix]] for $g$ in this [[basis]] as $(g_{ij})$ so that its [[adjoint of a linear transformation|adjoint]] is $(\overline{g_{ji}})$. Then because $g$ is [[unitary group representation|unitary]] , we have that its [[trace]] is $$\text{tr}(g^{-1}) = \text{tr}(g^*) = \sum_{i=1}^n \overline{a_{ii}} = \overline{\text{tr}(a)}.$$ Thus because [[character of contragradient representation|we have]] $\chi_{\rho^{\vee}}(g) = \chi_\rho(g^{-1}),$ the [[character of a representation|character]] $$\chi_{\rho^\vee}(g) = \chi_{\rho}(g^{-1}) = \text{tr}(\rho(g)^{-1}) = \text{tr}(\rho(g)^*) = \overline{\text{tr}(\rho(g))} = \overline{\chi_\rho(g)}$$ as desried.