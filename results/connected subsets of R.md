## Theorem
The [[connected]] subsets of $\mathbb R$ are exactly the [[interval|intervals]].
## Proof
Let $A$ be a [[connected]] subset of $\mathbb R$ that is not an [[interval]].
- There exists $a<b \in A$ and $x \in \mathbb R$ such that $a < x < b$ but $x \notin A$.
- A may be expressed as the nonempty disjoint union of [[definitions/open]] sets:
	- $A = ((-\infty, x) \cap A) \cup ((x,\infty) \cap A)$
- A is not [[connected]], a contradiction.

Let $A$ be an [[interval]] that is not [[connected]].
- $A$ may be expressed as the nonempty disjoint union of [[definitions/open]] sets $U$ and $V$:
	- $A = U\cup V$
- If $A = \{x\}$ for some $x \in \mathbb R$, it is [[connected]]:
	- There is no way to write $\{x\}$ as the disjoint nonempty union of [[open]] sets. #todo finish this!
- Suppose that $A$ contains at least two points.
	- Choose $a \in U$, $b \in V$.
	- Without loss of generality, suppose $a <b$.
	- Let $c = \sup\{x>a \mid (a,x] \subset U\}$. Then $c \in A$:
		- $U = A \cap U'$ for some [[open]] $U' \subset\mathbb R$:
			- $U$ is [[subspace topology|open]] in $A\subset\mathbb R$.
		- For $p \in U'$, there exists $\varepsilon > 0$ such that $(a-\varepsilon, a+\varepsilon) \subset U'$:
			- $U'$ is [[open]] in $\mathbb R$.
		- If $a+\varepsilon < b$, then $(a,a+\varepsilon) \subset U = A\cap U'$:
			- $A$ is an [[interval]]
	- $c < b$:
		- $a<b$ and $b \notin U$ implies that $c$ as the [[supremum]] of some points in $U$ is less than the [[infimum]] of an analogous set in $V$, and is therefore less than $b \in V$. #todo finish this
- $c \notin U$ and $c \notin V$, and therefore $c \notin A$
	- Suppose $c \in U$.
	- $c$ is not the [[supremum]] of $\{x>a \mid (a,x] \subset U\}$:
		- There exists $\varepsilon > 0$ such that $(c, c+\varepsilon) \subset U$:
			- $U$ is [[definitions/open]].
		- Then $\left(a, c+\frac{\varepsilon}{2}\right] \subset U$, contradicting the definition of $c$ as the [[supremum]] of such [[interval|intervals]].
	- Suppose $c \in V$. 
		- There exists $\varepsilon > 0$ such that $(c-\varepsilon, c) \subset V$:
			- $V$ is [[open]].
		- Also, $\left(a, c- \frac{\varepsilon}{2}\right) \subset U$:
			- $c - \frac{\varepsilon}{2} < c = \sup\{x > a \mid (a,x] \subset U\}$.
		- $U$ and $V$ are not disjoint:
			- $\left(a, c- \frac{\varepsilon}{2}\right)\cap (c-\varepsilon, c) \neq \emptyset$.
- $A$ is not an [[interval]]
	- $A$ must include all $x \in \mathbb R$ such that $a < x < b$, but $a < c < b$ and $c \notin A$.
