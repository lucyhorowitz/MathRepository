## Theorem
Let $X$ be a [[topological space]] with [[subspace topology|subspace]] $A$ and let $Z$ be a [[subspace topology|subspace]] of $A$ such that the [[closure]] of $Z$ is contained in the [[interior]] of $A$. Then the inclusion map $(X\setminus Z, A\setminus Z)\to (X,A)$ [[continuous functions induce homomorphisms on homology groups|induces]] [[group homomorphism|homomorphisms]] $H_n(X\setminus Z,A\setminus Z)\to H_n(
X,A)$ on the [[relative homology groups|relative homology groups]] for all $n$.

Equivalently, for [[subspace topology|subspaces]] $A$ and $B$ of $X$ whose [[interior|interiors]] cover $X$, the inclusion $(B,A\cap B) \to (X,A)$ [[continuous functions induce homomorphisms on homology groups|induces]] [[group homomorphism|homomorphisms]] $H_n(B,A\cap B)\to H_n(X,A)$ on the [[relative homology groups|relative homology groups]] for all $n$.
## Proof
Equivalence of the two statements comes from setting $B=X\setminus Z$ and $Z = X\setminus B$. Then $A\cap B = A\setminus Z$ and the condition $\overline Z\subset \text{int}(A)$ is equivalent to $X = \text{int}(A) \cup \text{int}(B)$ because $X\setminus \text{int}(B) = \overline Z.$ We will prove the version of this theorem from the second statement.

#write_proof 