## Theorem
Let $V$ be a [[definitions/vector space]] and let $T:V\to V$ be a [[linear transformation]] with  [[matrix of a linear transformation|corresponding matrix]] $A$. The [[matrix of a linear transformation|matrix corresponding]] to the [[adjugate]] of $T$ (written $\text{adj}(T) = (c_{ij})$) is given as follows: 

For each $i \in \{1,\dots,n\}$, let $I_i \subset\{1,\dots,n\}$ denote the subset of [[cardinality]] $n-1$ with $i$ removed. Each $$c_{ij} = (-1)^{i+j}\text{det}(A_{I_jI_i})$$ where $A_{I_jI_i}$ is the $(n-1)\times (n-1)$ sub[[matrix]] of $A$ with the $j$th row and $i$th column removed.
## Proof
#write_proof 