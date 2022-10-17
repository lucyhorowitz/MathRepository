## Theorem
Let $A'\subset A$ and $B'\subset B$. If $A'$ and $B$ are [[equidecomposable]] and $A$ and $B'$ are [[equidecomposable]], then $A$ and $B$ are [[equidecomposable]].
## Proof
Let $A' = A_1' \cup\cdots\cup A_n'$ and $B = B_1\cup \cdots B_n$ and let $\phi_i: A_i' \to B_i$ be [[isometry|isometries]]. Similarly, let $A = A_1\cup\cdots\cup A_m$ and $B' = B_1' \cup\cdots \cup B_m'$ with $\psi_i:B_i'\to A_i$ [[isometry|isometries]]. Construct a [[bipartite graph]] by connecting $x$ to $\phi_i(x)$ for $x \in A_i'$ and by connecting $y$ to $\psi_i(y)$ for $y \in B_i'$. [[edge coloring|Color]] the edges according to which [[isometry]] it arises from, giving $n+m$ colors.

Consider the [[graph component|components]] of the graph. Because it is [[bipartite graph|bipartite]], [[bipartite graphs contain no odd cycles|each connected component is either an even cycle or a path]]. Thus we can remove alternating edges in each [[graph component|component]] and then sort the edges by color to obtain an [[equidecomposable|equidecomposition]] of $A$ and $B$. 

#todo: how?