The **group algebra** of a [[group]] $G$ is the [[group ring]] of $G$ over $\mathbb C$ is denoted $\mathbb C[G]$ and is the set of maps $f:G\to \mathbb C$ with finite [[support]]. This forms a [[module over a ring]] over $\mathbb C$, and because $\mathbb C$ is a [[field]], it is a [[vector space]] over $\mathbb C$. 

The module scalar product of $\alpha\in \mathbb C$ and $f\in \mathbb C[G]$ is the map $x\mapsto \alpha\cdot f(x)$. The module group sum of mappings $f$ and $g$ in $\mathbb C[G]$ is the map $x\mapsto f(x)+g(x)$. To make this whole thing into a [[ring]], we define the product of $f,g\in \mathbb C[G]$ by the map$$x\mapsto \sum_{uv=x} f(u)g(v) = \sum_{u\in G} f(u)g(u^{-1}x).$$

We often write elements of $\mathbb C[G]$ as formal linear combinations of elements in $G$ with coefficients in $\mathbb C$, which looks like $$\sum_{g\in G} f_gg.$$ [[notes/class notes/MATH 26700/Lecture 11|]]

Equivalently, let $\mathbb k$ be a [[field]] and let $G$ be a [[group]]. The **group algebra** $\mathbb k G$ is a $\mathbb k$-[[vector space]] with basis $\{1_g\}_{g\in G}$ and multiplication table given by $1_g\cdot 1_h = 1_{gh}$ for all $g,h\in G$. The elements of $\mathbb kG$ are linear combinations $$\sum_{g\in G} c_g1_g$$ for $c_g \in\mathbb k$ zero for all but finitely many $g\in G$.  [[Prof-Provided notes|]]
https://www.wikidata.org/wiki/Q17019511