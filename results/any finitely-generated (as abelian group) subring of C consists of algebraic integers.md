## Theorem
Let $R$ be a [[unital subring|subring]] of $\mathbb C$. Suppose that $R$ is finitely [[generating set of a group|generated]] as an [[abelian]] [[group]]. Then all elements in $R$ are [[algebraic integer|algebraic integers]].
## Proof
Suppose that $R = \mathbb Zr_1 + \mathbb Zr_2 +\cdots + \mathbb Zr_k$ as an [[abelian]] [[group]]. Take $\alpha\in R$, and we can write $$\alpha r_1 = n_{11}r_1+n_{12}2r_2+\cdots + n_{1k}r_k + \cdots + n_{kk}r_k.$$ There are similar expressions for $\alpha r_i$ for all $i \leq k$, and they form a system of equations to which $r_1,r_2,\dots,r_k$ is a solution. It can be represented by the following matrix: $$\begin{bmatrix}n_{11}-\alpha 
 & n_{12} & \cdots & n_{1k}\\n_{21} & n_{22}-\alpha & \cdots & n_{2k}\\\vdots &\vdots &\ddots &\vdots\\n_{k1} & n_{k2} & \cdots & n_{kk}-\alpha\end{bmatrix}$$
This has a solution, so its [[determinant]] is $0$ ( #todo im confused here) and we have an equation on $\alpha$ with coefficients $(\pm 1)^k$. By [[Nakayama's lemma]], all other coefficients are integers, so $\alpha \in \overline{\mathbb Z}$.