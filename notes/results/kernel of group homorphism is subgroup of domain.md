## Theorem
Let $G,H$ be [[group|groups]] and $f:G\to H$ a [[group homomorphism]]. Then the [[definitions/kernel of group homomorphism|kernel]] $K = \text{Ker}(f) \subset G$ is a [[subgroup]] of $G$.
## Proof
- Let $g_1,g_2\in K$. Then $f(g_1)f(g_2) = e_H^2 = e_H$, so $K$ is closed under the group operation.
- By properties of the [[group homomorphism]], $e_G$ must be mapped to $e_H$, so the [[identity element]] of $G$ is contained in the [[definitions/kernel of group homomorphism|kernel]].
- Let $g \in G$. Then $f(g) = e_H$. Moreover, $f(g^{-1}) = f(g)^{-1} = e_H^{-1} = e_H$, so that the [[inverse element|inverse]] of every element of $K$ is also in $K$.

Thus $K$ is a [[subgroup]] of $G$.