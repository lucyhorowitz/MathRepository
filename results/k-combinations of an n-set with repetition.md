---
aliases: florist problem
---
## Theorem
The number of $k$-combinations of an $n$-set with repetition is ${n+k-1\choose k}$. [[binomial theorem|]]
## Proof 
We want to choose $k$ objects out of $n$ types with repetition allowed. In "florist" terms, we want to answer the question "In how many ways can you choose a bouquet of $k$ flowers if there are $n$ kinds of flowers available at the shop in sufficiently large supply?"

Suppose that, in the florist shop, the flowers are sorted in containers by type and lined up along a corridor. To buy $k$ flowers you start standing in front of the first flower and at every moment, either adds a flower to his bouquet or steps to the next container. He takes $n-1$ physical steps, and must make $k$ picks. So there are $n+k-1$ total "moves," and we want to figure out how many ways we can arrange the "picks" among the "moves." Thus it is $${n+k-1\choose k} = {n+k-1\choose n-1}$$ by symmetry of the [[binomial theorem|binomial coefficients]]. 