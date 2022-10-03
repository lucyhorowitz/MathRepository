Let $(V,F)$ be a [[vector space]] and let $\text{End}(V)$ be the set of [[linear transformation|linear transformations]] $V\to V$. This is a [[ring]] with resepect to the usual product operation. Define a new **bracket** operation by $[x,y] = xy-yx$. Then $\text{End}(V)$ is a [[Lie algebra]] over $F$. We call it the **general linear algebra** and denote it $\mathfrak{gl}(V)$.


If $V$ is of finite [[dimension of vector space|dimension]], then $\text{dim}(\text{End}(V)) = \text{dim}(V)^2$.

### Proof that $\text{End(V)}$ is a [[Lie algebra]]
1. The bracket is [[multilinear|bilinear]]: $$\begin{align*}[ax+y,z] &= (ax+y)z - z(ax+y)\\ &= axz + yz - azx -zy \\ &= axz - azx  + yz - zy \\ &= a[x,z] + [y,z]\end{align*}$$ for all $x,y,z\in \text{End}(V)$ and $a\in F$. A similar argument follows for the other coordinate.
2. Obviously $[x,x] = xx-xx = 0$.
3. #write_proof 

https://www.wikidata.org/wiki/Q17521172