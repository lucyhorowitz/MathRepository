---
aliases: binomial coefficient
---
## Theorem
For any non-negative integer $n$, we have $$(x+y)^n = \sum_{k=0}^n {n\choose k}x^ky^{n-k}$$ where $${n\choose k} = \frac{n!}{k!(n-k)!}$$ are the **binomial coefficients**.
## Proof
#write_proof 


## Binomial coefficients are the number of ways to choose objects
Note that by the [[rule of sum]], $(x+y)$ corresponds to either choosing $x$ or $y$ one time. By the [[rule of product]], $(x+y)^k$ is making $k$ choices of either $x$ or $y$. The exponent on $x$ after this multiplication represents the number of times we did in fact choose $x$ out of these $k$ times. And the binomial coefficients count the number of times we get that thing! It's crazy!