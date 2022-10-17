## Theorem
Let $U \subset \mathbb R^n$ be [[open]]. If $f:U \to\mathbb R^m$ is [[differentiable]] at $a \in U$, then $f$ is [[continuous]] at $a$.
## Proof
- There exists a linear transformation $A: \mathbb R^n \to \mathbb R^m$ such that $\lim\limits_{h\to 0} \frac{f(a+h)-f(a) - A(h)}{||h||}=0$:
	- $f$ is [[differentiable]].
- $f(a+h) = f(a) + A(h) + ||h||\left(\frac{f(a+h)-f(a)-A(h)}{||h||}\right)$
- $f$ is [[continuous]]:
	- $\lim\limits_{h\to 0} f(a+h) = f(a)$:
		- $f(a+h) = f(a) + A(h) + ||h||\left(\frac{f(a+h)-f(a)-A(h)}{||h||}\right)$
		- $\lim\limits_{h\to 0}\left( f(a) + A(h) + ||h||\left(\frac{f(a+h)-f(a)-A(h)}{||h||}\right)\right) = f(a)$
			- [[sum of limits is limit of sum|The limit of a sum is the sum of the limits]].
			- [[limit of product is product of limits|The limit of a product is the product of the limits, if they exist]].