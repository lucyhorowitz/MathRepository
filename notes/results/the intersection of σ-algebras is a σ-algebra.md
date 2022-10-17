## Theorem
The intersection of [[σ-algebra|σ-algebras]] is also a [[σ-algebra]].
## Proof
Let $\Sigma_1$ and $\Sigma_2$ be [[σ-algebra|σ-algebras]] on the set $X$.
1. Clearly, $X \in \Sigma_1\cap\Sigma_2$.
2. If $S \in \Sigma_1\cap \Sigma_2$, then it is in both $\Sigma_1$ and $\Sigma_2$, so $X\setminus S$ is in $\Sigma_1$ and $\Sigma_2$. Thus $X\setminus S \in \Sigma_1\cap\Sigma_2$.
3. If $\{A_i\}_{i\in\mathbb N} \subset \Sigma_1\cap\Sigma_2$ is a sequence of sets in $\Sigma_1\cap\Sigma_2$, then it is a sequence of sets in each [[σ-algebra]] individually. Thus their union $\bigcap\limits_{i\in\mathbb N} A_i$ is also in both [[σ-algebra|σ-algebras]], and so it is in $\Sigma_1\cap\Sigma_2$.

QED.