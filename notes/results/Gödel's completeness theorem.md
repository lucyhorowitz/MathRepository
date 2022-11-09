## Theorem
Let $L$ be a [[formal language of propositional logic]], let $\Gamma \subseteq\text{Form}(L)$ and let $\phi\in \text{Form}(L)$. Then $\Gamma$ [[model|models]] $\phi$ if and only if $\Gamma$ [[syntactic proof|proves]] $\phi$. 
## Proof
The first direction follows from the [[soundness theorem]].

Now suppose that $\Gamma$ [[model|models]] $\phi$. Then there is no model of $\Gamma\cup \{\neg \phi\}$. Then by [[Lindenbaum's lemma]]. $\Gamma \cup\{\neg\phi\}$ is [[inconsistent]]. But this really means that $\Gamma \cup\{\neg\phi\} \rightarrow\bot$. By the [[Deduction Theorem]], $\Gamma\vdash (\neg\phi)\rightarrow\bot$, which is because [[all logical operators can be replaced with implies and bottom]] the same as saying $\Gamma \vdash ((\phi\rightarrow\bot)\rightarrow \bot)$. Application of [[Axioms of Propositional Logic|axiom]] 2 and [[modus ponens]] shows that $\Gamma \vdash \phi$. 