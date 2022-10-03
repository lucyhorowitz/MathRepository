## Theorem
The [[p-adic expansion is unique|p-adic expansion]] of a [[p-adic field|p-adic number]] $x$ repeats if and only if $x\in\mathbb Q$.
## Proof (sketch)
Without loss of generality, we can assume that the expansion repeats "immediately," because if this were not the case, we could just subtract off the (necessarily rational!) non-repeating part of the number. We may also assume without loss of generality that this immediately repeating number has p-adic [[absolute value]] $1$ because if it did not, we could multiply by some rational number so that the product has unit [[absolute value]]. Let $$\begin{align*}x &= \sum_{i=1}^\infty (a_0+a_1p+a_2p^2+\cdots + a_{n-1}p^{n-1})p^i\\&= (a_0+a_1p+a_2p^2+\cdots + a_{n-1}p^{n-1})(1+p^n+p^{2n} + \cdots) \\ &= (a_0+a_1p+a_2p^2+\cdots+a_{n-1}p^{n-1})\left(\frac{1}{1-p^n}\right).\end{align*}$$
But this is the product of a rational number and some finite sum of integers, so it is rational.

The other direction is more complicated and we did not do it in class. #write_proof 
