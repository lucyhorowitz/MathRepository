## Theorem
Let $L$ be a [[formal language of propositional logic]], let $\Gamma \subseteq\text{Form}(L)$ and let $\phi\in \text{Form}(L)$. Then  $\Gamma$ [[syntactic proof|proves]] $\phi$ implies that $\Gamma$ [[model|models]] $\phi$. 

## Proof
Let $S_1,\dots,S_k$ be a [[syntactic proof]] of $\phi$ from $\Gamma$. We will show by [[induction]] that for all [[model|models]] $t$ of $\Gamma$, $t(S_i) = 1$ for $1\leq i\leq k$. Suppose that for all $j < i$, $t(S_j) = 1$. 
- In the case that $S_i$ is an [[Axioms of Propositional Logic|axiom]], we are done.
- In the case that $S_i\in \Gamma$, we are done. 
- In the case that there exists $m,n < i$ such that $S_n = S_m \rightarrow S_i$, we note that for all [[model|models]] of $\Gamma$, $t(S_n) = t(S_m\rightarrow S_i) = 0$ if $t(S_m)= 1$ and $t(S_i) = 0$. But we know that $t(S_n) = 1$ by the inductive hypothesis, so we must have $t(S_i) = 1$. 