## Theorem
If $\rho:G\to GL(V)$ is a [[unitary group representation|unitary]] representation where $V$ is a complex [[vector space]] with a [[Hermitian inner product]] $\langle\cdot,\cdot\rangle$ then it is [[complete reducibility|completely reducible]].
## Proof 
The proof is by [[induction]] on the [[dimension of vector space|dimension]] of $V$. 

First suppose that $V$ is not [[irreducible representation|irreducible]]. Then it has at least one [[subrepresentation]], so choose $W$ the one of minimal [[dimension of vector space|dimension]] It follows that $W$ is i=[[irreducible representation|irreducible]]. We wish to show that the [[orthogonal complement]] of $W$, $W^\intercal$, is [[invariant subspace|invariant]] under the [[group action|action]] of $G$. 

For any $w\in W$ and $x\in X^\intercal$, the fact that $\rho$ is [[unitary group representation|unitary]] means that $\langle \rho(g)x, w\rangle = \langle x, \rho(g^{-1})w\rangle = 0$ because $W$ is $G$-[[invariant subspace|invariant]]. Thus $W^\intercal$ is a [[subrepresentation]] of $V$ and moreover $V$ is the [[direct sum of vector spaces|direct sum]] $W \oplus W^\perp$. 

Moreover, $\dim (W^\intercal) < \dim V$ so by the inductive hypothesis, $W^\intercal$ is itself completely reducible so the theorem is proved.