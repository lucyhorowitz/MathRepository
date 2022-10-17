## Theorem
In $\mathbb R$ equipped with the [[Lebesgue measure]], the constant associated with the [[Besicovitch covering theorem]] is $2$.
## Proof
Choose an [[interval]] $B_n$ given by the algorithm from the proof of the [[Besicovitch covering theorem]]. Denote the coordinate of the center of any [[interval]] $B_m$ by $b_m$. Suppose that $B_n$ intersects two other intervals $B_i$ and $B_j$ such that $b_i,b_j > b_n$. Without loss of generality, let $\sup B_i \leq \sup B_j$. 

Suppose that there exists $x \in B_i\cup B_j$ such that $x < y$ for all $y \in B_n$. Then either $B_n \subset B_i$ or $B_n \subset B_j$. Without loss of generality, suppose that $B_n \subset B_i$. Then we have $b_n \in B_m$, so by the algorithm we must have $n < i$ so that $b_i \notin B_n$. But this would imply that $$r_n < \frac{r_i}{2} < \frac{9r_i}{10},$$ a contradiction by the algorithm. Therefore there can be no such $x$. 

Because $B_n \cap B_j \neq \emptyset$, the union $B_n \cup B_j$ is itself an [[interval]]. Then by the definition of [[interval]], it must be that $B_i \subset B_n \cup B_j$. Thus we can safely remove $B_i$ from the cover given by the algorithm so that for all [[interval|intervals]] $B_k$, there is at most one [[interval]] intersecting it on either side, and that these two [[interval|intervals]] do not intersect each other.

This kind of structure naturally gives rise to a [[graph]] consisting of nodes given by [[interval|intervals]] that are connected when they intersect. This graph is a union of [[path|paths]], and can [[color theorem to rename|therefore]] be colored by two colors, each corresponding to a family of pairwise disjoint intervals.