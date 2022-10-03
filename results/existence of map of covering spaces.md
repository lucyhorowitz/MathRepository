## Theorem
Let $E$, $E'$, and $B$ be [[connected]], [[locally path-connected]] [[topological space|topological spaces]] and let $p:E\to B$ and $p':E'\to B$ be [[covering space|coverings]] over $B$. Choose $b\in B$, $e\in E$, and $e'\in E'$ such that $p(e) = b = p'(e')$. Then there exists a [[map of coverings of a space|map of coverings]] $g:E\to E'$ such that $g(e)=e'$ if and only if after passing to the [[continuous functions induce homomorphisms on homology groups|induced homomorphism]] on the [[fundamental group]], $$p_*(\pi_1(E,e)) \subset p_*'(\pi_1(E',e'))$$ where the inclusion is inclusion of [[subgroup|subgroups]]. Moreover, there is only one such $g$. 

In particular, two [[map of coverings of a space|maps of covers]] $g,g':E'\to E$ coincide if $g(e)= g(e')$ for any single $e\in E$. 

Moreover, $g$ is a [[homeomorphism]] if and only if the inclusion of [[subgroup|subgroups]] above is an equality. Thus $E$ and $E'$ are [[homeomorphism|homeomorphic]] if and only if $p_*(\pi_1(E,e))$ and $p_*'(\pi_1(E',e'))$ are [[conjugate subgroups|conjugate]] whenever $p(e) = p'(e')$. 
## Theorem (in terms of [[fiber|fibers]])
Let $E$, $E'$, and $B$ be [[connected]], [[locally path-connected]] [[topological space|topological spaces]] and let $p:E\to B$ and $p':E'\to B$ be [[covering space|coverings]] over $B$. Choose a basepoint $b\in B$ and let the [[group]] G be the [[fundamental group]] of $B$ at $b$. That is, let  $G=\pi_1(B,b)$. Then if $g:E\to E'$ is a [[map of coverings of a space|map of coverings]], then $g$ restricts to a map $F_b\to F_b'$ between the [[fiber|fibers]] over $b$ as [[group action|G-sets]]. Moreover, restriction to [[fiber|fibers]] gives a [[bijective|bijection]] between the morphisms $\text{Cov}(E,E')$ in the [[category of covering spaces]] of $B$ and the set of [[equivariant map|G-maps]] $F_b\to F_b'$.
## Proof
[[Fundamental Theorem of Covering Space Theory]] [[map of coverings of a space is a covering]]

[[group-level determination of coverings of a groupoid]]