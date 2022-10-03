## Theorem
The [[p-adic integers]] are [[compact]] as a [[subspace topology|subspace]] of the [[p-adic field]] under the $p$-adic [[absolute value induces a topology|absolute value topology]].
## Proof 1
From the uniqueness of [[p-adic expansion is unique|p-adic expansions]], we can say that $\mathbb Z_p\cong \{0,1,\dots,p-1\}^\mathbb N$ where this exponentiation indicates a [[countable]] [[direct product of rings|direct product]]. The set $\{0,1,\dots,p-1\}$ is finite, so it [[finite sets are compact|is]] [[compact]]. [[Tychonoff's theorem]] states that the arbitrary [[direct product]] of [[compact]] spaces is also [[compact]], so we are done. 

## Proof 2
Since in a [[metric space]], a set is [[compact]] if and only if it is [[closed]] and [[totally bounded]], we just need to show total boundedness because we [[p-adic integers are closed|already have]] [[closed|closure]]. Given $\varepsilon = p^{-n}$, choose the [[left coset|cosets]] of the $n$th power of [[curly P]] as the finite set of balls [[p-adic integers is disjoint union of cosets of curly P|that cover]] $\mathbb Z_p$. 