## Theorem
The [[density topology]] on $\mathbb R^2$ is not equal to the [[box topology]] given by the Cartesian product of the [[density topology|density topologies]] on two copies of $\mathbb R$. 
## Proof
Let $S = \mathbb R^2 \setminus \{(x,y) \mid x+y \in \mathbb Q\}$. Then there are no [[Lebesgue measure|Lebesgue measurable]] sets $A,B\subset \mathbb R$ for which $A\times B \subset S$.       

Fix a set $A$ of positive [[Lebesgue measure]]. Let $$A' = \bigcup_{q\in\mathbb Q} q-A$$ be the union of all of the sets that result from shifting $A$ by some rational number $q$. Clearly the [[measure space|measure]] of this set is equal to the [[measure space|measure]] of $\mathbb R$.

Now let $B\subset \mathbb R$ be some set of positive [[Lebesgue measure]]. Because the measure of $A'$ is equal to the measure of $\mathbb R$ and $\mu(B) > 0$, we have $\mu(A'\cap B) > 0$. Then it must be nonempty, and this implies that the product $A\times B$ does contain some "rational sums," meaning that it cannot be a subset of $S$.

Now suppose for the sake of contradiction that the [[density topology]] on $\mathbb R^2$ is the stated [[box topology]]. Then because $S$ is clearly [[open]] in the [[density topology]], on $\mathbb R^2$ we can write $$S = \bigcup_{i\in \mathbb N} (A_i \times B_i)$$where $A_i, B_i$ are [[open]] in the [[density topology]] on $\mathbb R$. But $S$ has positive [[measure space|measure]], and so at least one of the products $A_i \times B_i$ must be of positive [[measure space|measure]], meaning that the component sets are of positive measure. This contradicts the previous result about $S$, so the [[density topology]] in $\\mathbb R^2$ is not the [[box topology]].