## Theorem
The [[density topology]] does in fact form a [[topological space|topology]].
## Proof
Clearly, $X$ and $\emptyset$ are both measurable and have [[measure density|density]] 1 everywhere. 

Now we show that this topology is closed under finite intersections. Let $A_1,A_2$ satisfy properties (1) and (2) from the definition. Then $A_1\cap A_2$ is [[measurable]] because the measurable sets form a [[σ-algebra]], and for all $x\in A_1\cap A_2$, $$\mu(B(x,r)) \leq \mu((A_1\cap A_2)\cap B(x,r)) + \mu((X\setminus A_1)\cap B(x,r))+\mu((X\setminus A_2)\cap B(x,r)).$$ This implies that $$\begin{align*}\frac{\mu((A_1\cap A_2)\cap B(x,r))}{\mu(B(x,r))} &\geq \frac{\mu(B(x,r)-\mu((X\setminus A_1)\cap B(x,r))-\mu((X\setminus A_2)\cap B(x,r))}{\mu(B(x,r))}\\ &= 1 - d(X\setminus A_1,x) - d(X\setminus A_2, x). \end{align*}$$ Taking the limit as $r\to 0$ implies that $d(A_1\cap A_2,x)= 1$ for all $x\in A_1\cap A_2$. Moreover, $X\setminus (A_1\cap A_2) = X\setminus A_1 \cup X\setminus A_2$. Then for all $x \in A_1\cap A_2$, $$d(X\setminus(A_1\cap A_2),x) \leq d(X\setminus A_1, x) + d(X\setminus A_2,x) =0$$ which together imply that $A_1\cap A_2$ is d-open. An [[induction|inductive]] argument concludes that the topology is closed under finite intersections.

Let $\{A_i\}_{i\in I}$ be an arbitrary collection of d-open sets. By definition of unions, if $x \in \bigcup\limits_{i\in I} A_i$, there exists some $j \in I$ for which $x \in A_j$. Then $$1=d(A_j,x)\leq d\left(\bigcup_{i\in I} A_i,x\right)$$ so that $d\left(\bigcup\limits_{i\in I} A_i,x\right)=1$. Because $A_j$ is d-open, for all $x \in A_j$ we have that $$d\left(X\setminus \bigcup_{i\in I} A_i,x\right) \leq d(X\setminus A_j,x )=0.$$ 

Thus the d-open sets do indeed form a [[topological space|topology]].