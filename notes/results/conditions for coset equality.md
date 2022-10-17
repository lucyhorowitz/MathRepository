## Theorem
Let $G$ be a [[group]] with [[subgroup]] $H$. Let $a,b\in G$. Then the following statements about [[left coset|cosets]] are equivalent:
1. $aH= bH$
2. $aH\subseteq bH$
3. $a\in bH$
4. $b^{-1}a\in H$

## Proof
(1) implies (2) implies (3) is clear. To see that (3) implies (4), note that if $a\in bH$, then by definition of [[inverse element|inverse]] and [[identity element|identity]], $b^{-1}a \in b^{-1}bH = eH = H$. 

Now note that if $h\in H$, then $hH = H$. From this we see that (4) implies (1): suppose that $b^{-1}a\in H$. Then $b^{-1}aH = H$ so that $bb^{-1}aH = b^{-1}H$ and finally $aH = bH$. 