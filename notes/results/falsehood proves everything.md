## Theorem
Let $L$ be a [[formal language of propositional logic]]. Then for any $\phi \in \text{Form}(L)$, falsehood [[syntactic proof|proves]] $\phi$. That is,$$\bot \vdash \phi.$$
## Proof
- $\bot\rightarrow ((\phi\rightarrow\bot)\rightarrow \phi)$ by [[Axioms of Propositional Logic|axiom]] 1;
- $\bot\vdash((\phi\rightarrow \bot)\rightarrow \bot)$ by the [[Deduction Theorem]];
- $\bot \vdash \phi$ by [[modus ponens]] and [[Axioms of Propositional Logic|axiom]] 2