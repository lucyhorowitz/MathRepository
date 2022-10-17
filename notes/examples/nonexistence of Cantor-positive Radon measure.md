## Theorem
There exists no [[Radon measure]] $\mu$ on $\mathbb R$ for which every translation of the [[Cantor set]] $C$ has positive $\mu$-[[measure space|measure]].
## Proof
Suppose we have such a [[measure space|measure]] $\mu$. Let $A\times [-1,1] = \{(x,y) \mid x+y \in C, y \in [-1,1]\}$ be a [[product measure|product space]] with measure $\mu \times \lambda$ for $\lambda$ the [[Lebesgue measure]] on $\mathbb R$. The space $A$ can be considered as the union of the sets $A_y$ for all $y \in [-1,1]$ such that $A_y = C-y$. This amounts to the [[Cantor set]] being extruded parallel to the line $y=x$. Let $\chi$ be the [[characteristic function]] of $A \times [-1,1]$. Consider the [[Lebesgue integral|integral]] $$\int_{A\times[-1,1]} \chi(x,y) \text d(\mu\times\lambda).$$ Because [[Lebesgue measure is Radon|both]] $\mu$ and $\lambda$ are [[Radon measure|Radon]], we can apply [[Fubini's theorem]] and we expect

$$\int_A\left(\int_{[1,1]} \chi(x,y)\text d\lambda\right) \text d\mu = \int_{[-1,1]}\left(\int_A \chi(x,y)\text d\mu\right) \text d\lambda.$$

If we evaluate the integral on the right, we find that

$$\begin{align*}

\int_{[-1,1]}\left(\int_A \chi(x,y)\text d\mu\right) \text d\lambda &= \int_{[-1,1]} \left(\int \chi_{C-y} \text d\mu\right) \text d\lambda \\

&= \int_{[-1,1]} \mu(C-y) \text d\lambda > 0.

\end{align*}$$ 
But fixing $x$ and considering the cross section results in a [[Cantor set]], which [[Cantor set has measure zero|has]] [[Lebesgue measure]] zero. Thus evaluating the [[Lebesgue integral|integral]] on the left, we have

$$\begin{align*}

\int_A\left(\int_{[-1,1]} \chi(x,y)\text d\lambda\right) \text d\mu = 0,

\end{align*}$$ 

and the two iterated [[Lebesgue integral|integrals]] are not in fact equal. This contradicts [[Fubini's theorem]] and therefore there can be no such [[measure space|measure]].