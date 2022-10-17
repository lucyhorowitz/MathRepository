## Theorem
Let $(X,\Sigma,\mu)$ be a [[probability space]] and let $\{A_n\}_{n\in\mathbb N}$ be a collection of [[measurable]] subsets of $X$. If $$\sum_{n\in\mathbb N} \mu(A_n) = \infty$$ and the events represented by the $A_n$ are [[independent events|independent]] (i.e. for each finite $I \subset \mathbb N$, $$\mu\left(\bigcap_{i\in I} A_i\right) = \prod_{i\in I} \mu(A_i)),$$ then the [[measure space|measure]] of the [[limit supremum]] of the $A_n$ is $1$. That is, [[almost everywhere|almost every]] $x\in X$ is in infinitely many of the $A_n$.

This is a partial converse of the [[Borel-Cantelli lemma]].

## Proof
First, we have by [[continuity of measure]] that the product relation given in the statement of the problem holds for countable intersections of the $A_i$ as well as finite intersections. We also have that for the complements of the $A_i$, the product relation given in the statement holds. Thus

$$\begin{align*}

\mu(X\setminus Y) &= \mu\left(\bigcup_{k=1}^\infty \bigcap_{n=k}^\infty (X\setminus A_n)\right) \leq \sum_{k=1}^\infty \mu\left(\bigcap_{n=k}^\infty X\setminus A_n\right) \\

&= \sum_{k=1}^\infty \prod_{n=k}^\infty \mu(X\setminus A_n) = \sum_{k=1}^\infty \prod_{n=k}^\infty (1-\mu(A_n))\\

&\leq \sum_{k=1}^\infty \prod_{n=k}^\infty e^{-\mu(A_n)} = \sum_{k=1}^\infty e^{\left(-\sum\limits_{n=k}^\infty \mu(A_n)\right)} = 0 \end{align*}$$ 

because the series $\sum\limits_{k=1}^\infty \mu(A_n)$ diverges, and therefore every tail must diverge.