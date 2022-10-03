## Theorem
Let $U \subset \mathbb R^n$ be [[open]]. The function $f:U\to\mathbb R^m$ is [[differentiable]] if all [[partial derivative|parital derivatives]] of $f$ exist and are [[continuous]] on $U$.

Such a function is of [[class]] at least $C^1$.
## Proof
Let $f: U\to\mathbb R^m$ have [[continuous]] [[partial derivative|partial derivatives]] at $a = (a_1,\dots,a_n)$. Write $f = (f_1,\dots,f_m)$ where $f_i: U\to \mathbb R$ are the [[component function|component functions]] of $f$. Let $h = (h_1,\dots,h_n) \in U-a = \{x \in \mathbb R^n \mid x = y-a \text{ for } y \in U\}$. 
- Write $f_j(a+h) - f_j(a)=\sum\limits_{i=1}^{n+1} f_j( a_1, \dots, a_i+ h_i, \dots, a_n+h_n) - f_j(a_1, \dots, a_i, a_{i+1}+h_{i+1}, \dots, a_n + h_n))$ so that $f(a+h)- f(a) = (f_1(a+h)- f_1(a), \dots, f_m(a+h)-f_m(a))$.
	- The series telescopes.
- For each $i$, there exists some $c_{i}(h) \in (a_i, a_i + h_i)$ or $(a_i-h_i, a_i)$ such that $f(a_1,\dots, a_i+h_1,\dots,a_n+ h_n) - f(a_1, \dots, a_{i+1}+h_{i+1},\dots, a_n+h_n) =h_i\frac{\partial f}{\partial x_i}(a_1,\dots, a_{i-1}, c_{i}(h), a_{i+1}+h_{i+1}, \dots, a_n+h_n).$
	- For each $i,j$ there exists some $c_{ij}(h) \in (a_i, a_i + h_i)$ or $(a_i-h_i, a_i)$ such that each $f_j(a_1,\dots, a_i+h_1,\dots,a_n+ h_n) - f_j(a_1, \dots, a_{i+1}+h_{i+1},\dots, a_n+h_n) =h_i\frac{\partial f_j}{\partial x_i}(a_1,\dots, a_{i-1}, c_{ij}(h), a_{i+1}+h_{i+1}, \dots, a_n+h_n):$
		- By assumption, each $f_j$ is [[differentiable]] in the $i$th variable and is [[differentiable implies continuous|therefore continuous]] in the $i$th variable.
		- Apply the [[mean value theorem]] to the $i$th variable of each $f_j$.
	- Write $f$ as the vector consisting of its [[component function|component functions]].
- Let $\pi_i: \mathbb R^n \to \mathbb R^n$ be given by $(x_1,\dots,x_n) \mapsto (0,\dots, x_i, \dots, 0)$. For all $x \in \mathbb R^n$, $x = \sum\limits_{i=1}^n \pi_i(x)$.
- The [[Jacobian matrix]] $A$ of $f$ at $a$ exists and $\lim\limits_{h\to 0} \frac{f(a+h)-f(a)-A(h)}{||h||} = 0$.
	- $f(a+h) - f(a) = \sum\limits_{i=1}^n h_i\frac{\partial f}{\partial x_i}(a_1, \dots, a_{i-1}, c_i(h), a_{i+1} + h_{i+1}, \dots, a_n + h_n)$
	- $A(h) = \sum\limits_{i=1}^n \frac{1}{||h||} A(\pi_i(h)) = \sum\limits_{i=1}^n\frac{\partial f}{\partial x_i}(a)h_i$
	- $\lim\limits_{h\to 0}\frac{f(a+h)-f(a)-A(h)}{||h||} = \lim\limits_{h\to 0}\sum\limits_{i=1}^n \frac{h_i}{||h||}\left( \frac{\partial f}{\partial x_i}(a_1,\dots, c_i(h), \dots, a_n+h_n) - \frac{\partial f}{\partial x_i}(a)\right) = 0$
		- [[sum of limits is limit of sum|The limit of the sum is the sum of the limits]].
		- [[limit of product is product of limits|The limit of the product is the product of the limits]] if both exist:
			- $\left|\frac{h_i}{||h||}\right| \leq 1$, so this limit exists.
			- Since the [[partial derivative|partial derivatives]] are [[continuous]] by assumption, the limit of the difference exists.

_NOTE: the converse of this theorem is not true. See [[hw2 example 1]]_ #todo is this the correct example?