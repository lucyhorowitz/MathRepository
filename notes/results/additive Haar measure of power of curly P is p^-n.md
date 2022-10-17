## Theorem
The [[Haar measure on additive Qp]] of a power of [[curly P]] (better written as $\mathcal P^n$) is equal to $p^{-n}$. 
## Proof
We can find the [[measure space|measure]] using the [[Lebesgue integral of characteristic function|Lebesgue integral]] of the [[characteristic function]] on $\mathcal P^n$, which is really just the constant $1$ function if we integrate only over $\mathcal P^n$. 

Because the [[Haar measure]] is translation invariant, it must be the case that $$\int_{k+\mathcal P} \text dx = \int_{\mathcal P} \text dx$$ for all $k\in \{0,1,\dots,p-1\}$. But we [[p-adic integers is disjoint union of cosets of curly P|may]] write the [[p-adic integers]] as $$\mathbb Z_p = \coprod_{k\in\{0,\dots, p-1\}} (k+\mathcal P).$$ So by the countable additivity condition on [[measure space|measures]] and translation invariance, we have the result for when the power of $\mathcal P$ is one. But note that similarly, we can write $$\mathcal P^{-n} = \coprod_{0\leq k < p^n}(k+\mathbb Z_p),$$ so again the whole thing follows.