## Theorem
Let $U \subset \mathbb R^n$ and $V \subset \mathbb R^m$ be [[open|open]]. Let $f:U\to \mathbb R$, and suppose that for some $a \in U$, the [[partial derivative|partial derivatives]] $\frac{\partial f}{\partial x_i}$ for $1\leq i\leq n$ are all [[bounded]] in a [[neighborhood]] of $a$. Then $f$ is [[continuous]] at $a$.
## Proof
Let $\varepsilon > 0$. Let $M \in \mathbb R$ such that for all $x \in U$, $\left|\frac{\partial f}{\partial x_i}(x)\right| \leq M$. 
Let $\delta < \varepsilon$ such that the [[open|open]] ball $B\left(a, \frac{\delta\sqrt{n}}{Mn}\right) \subset U$.
Choose $h = (h_1,\dots, h_n) \in \mathbb R^n$ such that $||h|| < \frac{\delta}{Mn}$.
For $i \in \{1,\dots,n\}$, define $\phi_i:[0,h_i] \to \mathbb R$ by $$\begin{align*}
	\phi_i(t) &= f(a_1, \dots, a_i + t, a_{i+1}+h_{i+1},\dots, a_n+h_n)\\ &- f(a_1, \dots, a_i, a_{i+1}+h_{i+1},\dots, a_n+h_n).
	\end{align*}$$

- The sum of the $\phi_i$ telescopes: $\sum\limits_{i=1}^n \phi_i(h_i) = f(a+h)-f(a)$.
- Each $\phi_i$ is [[differentiable]].
	- $a+h \in B\left(a, \frac{\delta\sqrt{n}}{Mn}\right) \subset U$.
	- Differentiating $\phi_i$ with respect to $t$ is equivalent to taking a [[partial derivative]] of $f$ at some point where it exists. 
		- $\begin{cases}\begin{align*}\phi_i'(t) &= \frac{\partial}{\partial x_i}(\phi_i(t))\\&=\frac{\partial}{\partial x_i} (f(a_1, \dots, a_i + t, a_{i+1}+h_{i+1},\dots, a_n+h_n)\\ &\text{ }\text{ }\text{ }\text{ }\text{ }\text{ }\text{ }\text{ }\text{ }- f(a_1, \dots, a_i, a_{i+1}+h_{i+1},\dots, a_n+h_n))= \\&= \frac{\partial f}{\partial x_i}(a_1,\dots, a_i+t, a_{i+1}+h_{i+1},\dots, a_n+h_n)\end{align*}\end{cases}$
		- Because the [[derivative of sums|derivative of a sum is the sum of the derivative]] and the [[derivative of constant|derivative of a constant is 0]].
- Each $\phi_i'$ is [[bounded]] by $M$.
	- Each $\phi_i'$ is equal to one of the [[partial derivative|partial derivatives]] of $f$ at some point where it is [[bounded]].
- $f$ is [[continuous]] at $a$.
	- By the [[mean value theorem]], for each $\phi_i$ there exists $t_i \in (0, h_i)$ such that $|\phi_i(h_i)-\phi_i(0)| = |\phi_i(t_i)| \leq M|h_i| < M\frac{\delta}{Mn} = \frac{\delta}{n}.$ 
	- Because $\phi_i(h_i)$ telescopes, $\begin{cases}\begin{align*}|f(a+h) - f(a)| &= \left|\sum\limits_{i=1}^n \phi_i(h_i) - \phi_i(0)\right|\\&\leq\sum\limits_{i=1}^n| \phi_i(h_i) - \phi_i(0)|\\& < n\frac{\delta}{n} = \delta < \varepsilon.\end{align*}\end{cases}$
	- For all $\varepsilon > 0$, there exists $\delta_0 = \frac{\delta}{Mn}$ such that $|((a+h)-f(a)| < \varepsilon$ whenever $||(a+h)-a|| < \delta_0$.

