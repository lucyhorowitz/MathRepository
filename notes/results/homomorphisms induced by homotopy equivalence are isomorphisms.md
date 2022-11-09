## [[A Concise Course in Algebraic Topology|Concise]] version:
### Theorem
Let $X$ and $Y$ be [[topological space|topological spaces]]. If $f:X\to Y$ is a [[homotopy equivalence of spaces|homotopy equivalence]], then the [[induced homomorphism on fundamental group|induced]] [[group homomorphism|homomorphism]] $$f_*: \pi_1(X,x) \to \pi_1(Y,y)$$ is an [[group homomorphism|isomorphism]] for all $x\in X$. 
### Proof
Let $g:Y\to X$ be a [[homotopy]] inverse of $f$. Then by the [[homotopy invariance diagram]], the following two composites are [[isomorphism|isomorphisms]]:

$$\begin{align*}\pi_1(X,x)&\overset{f_*}{\to} \pi_1(Y,f(x) \overset{g_*}{\to}\pi_1(X,(g\circ f)(x))\\ \pi_1(Y,y)&\overset{g_*}{\to} \pi_1(X,g(y))\overset{f_*}{\to} \pi_1(Y,(f\circ g)(y)).\end{align*}$$  Moreover, the [[group homomorphism|isomorphisms]] are determined by [[path|paths]] between basepoints given by the chosen [[homotopy|homotopies]] $g\circ f \simeq \text{id}$ and $f\circ g\simeq \text{id}$. It follows that the first map must be a [[monomorphism]] and the second map must be an [[epimorphism]]. Thus if, in the first composite, we choose $y=f(x)$, the second map in the first composite must be an [[isomorphism]]. Then the first map must be an [[isomorphism]]. Since we are working with [[group|groups]], the [[isomorphism|isomorphisms]] correspond exactly to [[group homomorphism|group isomorphisms]].


## [[Algebraic Topology|Hatcher]] version:
### Theorem
Let $X$ and $Y$ be [[topological space|topological spaces]] and let $f:X\to Y$ be a [[homotopy equivalence of spaces]]. Then the [[continuous functions induce homomorphisms on homology groups|induced homomorphisms]] between the [[homology group|homology groups]] $f_*:H_n(X)\to H_n(Y)$ are [[group homomorphism|isomorphisms]].
### Proof 
#write_proof [[properties of induced homomorphisms]] [[homotopic maps induce the same homomorphism on homology]]