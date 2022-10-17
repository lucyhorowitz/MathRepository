## Proposition
If $A$ and $B$ are both [[linear transformation|linear transformations]] satisfying the definition of [[differentiable|total derivative]], then $A=B$.
## Proof 
Let $U \subset\mathbb R^n$ be [[openness in a metric space.]]
Let $f: U\to \mathbb R^m$ be [[differentiable]].
Suppose that $$\lim_{h\to 0}\frac{f(a+h)-f(a) -A(h)}{||h||}=0=\lim_{h\to 0}\frac{f(a+h)-f(a) -B(h)}{||h||}$$ for [[linear transformation|linear transformations]] $A, B: \mathbb R^n \to \mathbb R^m$.
- $\lim\limits_{h\to 0} \frac{A(h)-B(h)}{||h||} = 0$:
	- [[sum of limits is limit of sum|The sum of two limits is the limit of the sums]].
- For $v \in \mathbb R^n$, $\frac{A(tv)-B(tv)}{t} = A(v)- B(v)$:
	- $A$ and $B$ are [[linear transformation|linear]].
- $A(v) = B(v)$ for all $v \in \mathbb R^n$:
	- $A(v) - B(v) = \lim\limits_{t\to 0} \frac{A(tv)-B(tv)}{t} = 0$.