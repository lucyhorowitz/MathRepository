## Theorem
Let $L$ be a [[formal language of propositional logic]] and let $\Gamma\subseteq \text{Form}(L)$. If every finite subset of $\Gamma$ has a [[model]], then $\Gamma$ has a [[model]].
## Proof
The proof is by [[contrapositive]]. 

Suppose that $\Gamma$ does not admit a [[model]]. Then by [[Gödel's completeness theorem]], $\Gamma$ [[syntactic proof|proves]] falsehood (write $\Gamma\vdash \bot$). Any [[syntactic proof]] of falsehood from $\Gamma$ is by definition of finite length, so it uses only a finite set of statements from $\Gamma$. This finite subset therefore [[syntactic proof|proves]] falsehood, so it does not have a [[model]]. 