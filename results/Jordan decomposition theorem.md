## Theorem
Let $(X,\Sigma)$ be a [[measurable|measurable space]] with $\mu$ a [[signed measure]]. Then the [[positive variation]] $\pi$ and the [[negative variation]] $\nu$ of $\mu$ are both non-negative [[measure space|measures]] on $\Sigma$. 
## Proof
Clearly $\pi(\emptyset)=\nu(\emptyset) = 0$, so to show that the two variations are measures it remains to check countable additivity. Because $\nu$ is defined as the difference of $\pi$ and $\mu$, it suffices to show countable additivity for $\pi$. Fix $\varepsilon > 0$ and let $\{A_i\}_{i\in\mathbb N}$ be a sequence of pairwise disjoint [[measurable]] sets and choose $S_i \subset A_i$ such that $\mu(S_i) \geq \pi(A_i) - \frac{\varepsilon}{2}$, which is possible by the definition of $\pi$ as a [[supremum]]. Then $$\pi\left(\bigcup_{i\in\mathbb N} A_i\right)\geq \mu\left(\bigcup_{i\in\mathbb N} S)i\right) = \sum_{i\in\mathbb N} \mu(S_i) \geq \sum_{i\in\mathbb N} \pi(A_i) + \varepsilon.$$ Because $\varepsilon$ was arbitrary, we have that $$\pi\left(\bigcup_{i\in\mathbb N} A_n\right)\geq \sum_{i\in\mathbb N} \pi(A_n),$$ one direction of the desired equality. Now choose $S\subset\bigcup\limits_{i \in\mathbb N}A_n$ so that $\mu(S) \geq \pi\left(\bigcup\limits_{i \in\mathbb N} A_n\right)-\varepsilon$ Because $\mu(S\cap A_i) \leq \pi(A_i)$ for each $i$, we have $$\pi\left(\bigcup_{i\in\mathbb N} A_i\right)-\varepsilon \leq \mu(S) = \sum_{i\in\mathbb N} \mu(S\cap A_i) \leq \sum_{i\in\mathbb N} \pi(A_i).$$ Again because $\varepsilon$ may be as small as we wish, we have $$\pi\left(\bigcup_{i\in\mathbb N} A_n\right)\leq \sum_{i\in\mathbb N} \pi(A_n),$$ the other direction required to prove equality. Thus $\pi$ is a [[measure space|measure]] on $\Sigma$ and therefore so is $\nu$. 