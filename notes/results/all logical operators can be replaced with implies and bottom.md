## Theorem
Let $\text{Form}(L)$ be a [[formal language of propositional logic]] with the logical operators $(\land,\lor, \rightarrow, \leftrightarrow, \neg)$.  Then any statement involving these can be rewritten using no operators other than $\rightarrow$ and $\bot$. 
## Proof
Let $\phi, \psi \in \text{Form}(L)$.
- $\neg \phi = \phi \rightarrow \bot$
- $\phi \lor \psi = (\neg \phi)\rightarrow \psi = (\phi\rightarrow\bot)\rightarrow \psi$
- $\phi \land\psi = \neg((\neg\phi)\lor (\neg\psi)) = \cdots$ by [[De Morgan's laws]]
- $\phi\leftrightarrow\psi = (\phi\rightarrow\psi)\land(\psi\rightarrow\phi) = \cdots$