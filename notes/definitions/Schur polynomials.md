Let $\Lambda=\{\mu = (\mu_1,\dots, \mu_n)\in\mathbb Z^n \mid \mu_1\geq \cdots\geq \mu_n \geq 0\} \subseteq \mathbb Z^n_{\geq 0}$. For each $\mu \in \Lambda$, define $\nabla_\mu \in \mathbb Z[x_1,\dots, x_n]^\text{sign}$ to be the [[invariant polynomials under group action|antisymmetric]] [[polynomial ring|polynomial]] under the [[sign representation]] of the [[symmetric group]] given by $$\nabla_\mu = \sum_{s\in S_n} \text{sign}(s) x^{s(\mu)} = \det\left|\begin{matrix}x_1^{\mu_1}  & x_1^{\mu_2} & \cdots & x_1^{\mu_n} \\ x_2^{\mu_1} & x_2^{\mu_2} & \cdots & x_2^{\mu_n} \\ \vdots &\vdots & \ddots &\vdots \\ x_n^{\mu_1} & x_n^{\mu_2}&\cdots & x_n^{\mu_n}\end{matrix} \right|.$$ The second equality follows from the [[Leibniz formula]] for [[determinant|determinants]]. 

Set $\rho \in \Lambda$ to $\rho = (n-1,n-2,\dots, 1, 0)$. Up to sign, $\nabla_\rho$ is the [[Vandermonde determinant]]. 

Because $\mathbb Z[x_1,\dots, x_n]^\text{sign}$ [[antisymmetric polynomials have a Vandermonde factor|is]] a [[rank of a module|rank]]-one [[free module|free]] [[module over a ring|module]] over $\mathbb Z[x_1,\dots, x_n]^{S_n}$ with [[generate an R-module|generator]] $\Delta_n$, it follows that $\nabla_\rho$ is also a [[generate an R-module|generator]] of this [[module over a ring|module]]. Thus for every $\mu\in \Lambda$ there exists a unique [[polynomial ring|polynomial]] $s_\mu\in\mathbb Z[x_1,\dots, x_n]^{S_n}$ called the **Schur polynomial** of $\mu$ such that $\nabla_{\mu + \rho} = s_\mu \cdot\nabla_\rho$. 

Explicitly, $s_\mu = \nabla_{\mu + \rho}/\nabla_\rho$. 