## Theorem
Let $X$ be a [[compact]] [[topological space]] and let $\int_X$ be a [[Haar integral]] over $X$. Then for all [[continuous]] functions $f:X\to \mathbb C$, we have the following inequality: $$\left|\int_X f \right| \leq \text{vol}(X) \cdot\max_{x\in X} |f(x)|$$ where $\text{vol}(X)$ is the [[volume of compact topological space|volume]] of $X$. 

## Proof
Let $C$ be the maximum from the statement of the theorem. Then $C-|f(x)| \geq 0$ for all $x$, so $\int_X(C-|f(x)|)dx \geq 0$ by positivity of the integral. Because $\int_X Cdx = \text{vol}(X)\cdot C$, we have $$\text{vol}(X) \cdot C - \int_X |f(x)|dx = \int_X (C-|f(x)|)dx \geq 0.$$ By [[norm inequality of Haar integral]], it follows that $$\left|\int_X f(x)dx\right| \leq \int_X|f(x)|dx\leq \text{vol}(X)\cdot C.$$