---
aliases: Vitali set
---
## Theorem
There exists a subset $V\subset\mathbb R$ that is not [[Lebesgue measure|Lebesgue-measurable]].
## Proof
Define an [[equivalence relation]] $\sim$ on $\mathbb R$ by $x\sim y$ if and only if $x-y \in \mathbb Q$. By the [[Axiom of Choice]], we can select one representative for each [[equivalence class]]. For any $x\in \mathbb R$, we have that $x + n \sim x$ for all $n \in \mathbb Z$. Thus we can define $V$ be the set of these representatives that are in the interval $[0,1]$. Let $\mu$ be the [[Lebesgue measure]]. Then $\mu$ [[Lebesgue measure is translation invariant|is translation invariant]], and moreover $\mu(\mathbb R)\neq 0$ and $\mu([a,b]) < \infty$ for all $a<b$ by definition. We will show that the set $V$ is not contained in the [[Lebesgue measure|Lebesgue σ-algebra]]. 

For any nonzero $q \in \mathbb Q$, the sets $V$ and $V+q$ are disjoint. Suppose for the sake of contradiction that they are not. Then $x -q \in v$ and $x \in V$, and $V$ contains two representatives of the [[equivalence class]] for $x$, contradicting he definition of $V$.

Enumerate $\mathbb Q \cap [-1,1]$ by $\{q_n\}_{n\in\mathbb N}$ and let $$W = \bigcup_{m=n}^\infty (V+q_n).$$ Then $[0,1] \subset W \subset [-1,2]$. Suppose that $V$ is [[Lebesgue measure|Lebesgue measurable]] and consequently so are the $V+q_n$. By countable additivity of measure and [[translation invariant|translation invariance]], $$\mu(W) = \mu\left(\bigcup_{n\in\mathbb N} (V+q_n)\right) = \sum_{n\in\mathbb N}\mu(V+q_n) = \sum_{n\in\mathbb N} \mu(V).$$ But $\mu([0,1]) =1$ so $\mu(W) \geq 1$, and therefore $\mu(V) > 0$. But by [[monotonicity of measure]] the infinite sum is bounded by $\mu([-1,2]) = 3 < \infty$, a contradiciton. Therefore $V$ cannot be in the Lebesgue [[σ-algebra]].