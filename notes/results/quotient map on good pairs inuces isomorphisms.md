## Theorem
Let $(X,A)$ be a [[exact sequence on reduced homology of space and retractable subspace]]. Then the [[canonical projection|quotient map]] $q: (X,A) \to (X/A, A/A)$ induces [[group homomorphism|isomorphisms]] $q_*: H_n(X,A)\to H_n(X/A,A/A) \cong \tilde H_n(X/A)$.
## Proof
Let $V$ be a [[neighborhood]] of $A$ in $X$ that [[deformation retraction|deformation retracts]] onto $A$. Then the [[commutative diagram|diagram]] ![[Screen Shot 2021-11-11 at 10.16.37 AM.png]] commutes. 

The horizontal map in the upper left is an [[group homomorphism|isomorphism]] because in the [[long exact sequence of a triple|long exact sequence]] of the triple $(X,V,A)$, the [[homology group|homology groups]] $H_n(V,A)$ are zero for all $n$ because a [[deformation retraction]] of $V$ onto $A$ gives a [[homotopy equivalence of spaces]] of the pairs $(V,A) \simeq (A,A)$ and $H_n(A,A)=0$ and [[homomorphisms induced by homotopy equivalence are isomorphisms]]. 

The [[deformation retraction]] of $V$ onto $A$ induces a [[deformation retraction]] of $V/A$ onto $A/A$, so by the same argument as above, the lower left horizontal map is an [[group homomorphism|isomorphism]] too. 

The rightmost horizontal maps are [[group homomorphism|isomorphisms]] by the [[Excision Theorem]]. 

The rightmost vertical map is an [[group homomorphism|isomorphism]] because the [[canonical projection|quotient map]] $q$ restricts to a [[homeomorphism]] on the complement of $A$. Because the diagram [[commutative diagram|commutes]], the leftmost vertical map must also be an [[group homomorphism|isomorphism]].