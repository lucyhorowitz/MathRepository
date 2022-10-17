## Theorem
Let $(X,\Sigma,\mu)$ be a [[measure space]] and let $\{f_n\}_{n\in\mathbb N}$ be a sequence of [[measurable function|measurable]] functions $f_n: X\to \mathbb R$. Then the sets 
- $\{x\in X\mid \{f_n(x)\}_{n\in\mathbb N}\}$
- $\{x\in X\mid \text{there exists a subsequence } n_k \text{ s.t. } \lim\limits_{k\to \infty}f_{n_k}(x) = \infty\}$
- $\{x\in X\mid \text{there exists a subsequence } n_k \text{ s.t. } \lim\limits_{k\to \infty}f_{n_k}(x) = -\infty\}$

are [[measurable]].
## Proof
Denote $$A = \{x\in X \mid \{f_n(x)\}_{n\in\mathbb N} \text{ is bounded}\}$$ and $$\begin{align*} B &= \{x\in X\mid \text{ there is a subsequence } n_k \text{ such that } \lim f_{n_k}(x) = \infty\}\\ &= \{x\in X \mid \{f_n(x)\}_{n\in\mathbb N} \text{ is bounded from below and unbounded from above}\}. \end{align*}$$ Then we may introduce the sets 

$$\begin{align*} B' &= \{x\in X \mid \{f_n(x)\}_{n\in\mathbb N} \text{ is bounded from below}\} \\ B'' &= \{x \in X \mid \{f_n(x)\}_{n\in\mathbb N} \text{ is bounded from above}\}\end{align*}$$

so that $A = B' \cap B''$ and $B = (X\setminus B') \cap B''$. We may rewrite $B'$ and $B''$ as follows: 

$$\begin{equation*}\begin{split}

B' &=\bigcup_{m\in\mathbb Z} \{x\in X \mid f_n(x) \geq m \quad \forall n \in \mathbb N\}\\

&= \bigcup_{m\in\mathbb Z} \bigcap_{n\in\mathbb N} \{x\in X \mid f_n(x) \geq m\}

\end{split} \qquad

\begin{split}

B'' &= \bigcup_{m\in\mathbb Z}\{x\in X \mid f_n(x) \leq m \quad \forall n\in\mathbb N\} \\

&= \bigcup_{m\in\mathbb Z} \bigcap_{n\in\mathbb N} \{x\in X\mid f_n(x) \leq m\}.\end{split}\end{equation*}$$

For all $n$, the sets $\{x\in X \mid f_n(x) \leq m\}$ and $\{x\in X\mid f_n(x) \geq m\}$ are just the [[preimage]] of the sets $[m,\infty)$ and $(-\infty, m] \subset \mathbb R$, respectively. Each is in the [[Borel σ-algebra]] as it is [[closed]]. Thus because each $f_n$ is [[measurable]], the [[measurable function|preimage of a measurable set under a measurable functions is measurable]], and the sets $\{x\in X \mid f_n(x) \leq m\}$ and $\{x\in X \mid f_n(x) \geq m\}$ are also [[measurable]]. Moreover, measurability is preserved under countable unions and intersections, so $B'$ and $B''$ are both themselves measurable. Once more, with the consideration of complementation preserving measurability, we have that $A$ and $B$ are both measurable, as desired.