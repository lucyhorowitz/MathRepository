## Theorem
There exists a [[comeager|residual]] subset of $\mathbb R^n$ with zero [[Lebesgue measure]]. 
## Proof
First we construct such a set in $[0,1] \subset\mathbb R$. For all $n \in\mathbb N$, we define a sequence $\{A_{n,m}\}$ of subsets of $[0,1]$ using "fat [[Cantor set|Cantor sets]]" as follows:

- $A_{n,0} = [0,1]$.
- $A_{n,1} = \left[0, \frac{1}{2^{n}}\right] \cup \left[\frac{2^n-1}{2^{n}}, 1\right]$.
- For all $m\leq k$, we have that $A_{n,m}$ is the disjoint union of $2^m$ [[closed]] [[interval|intervals]]. Construct $A_{n,k+1}$ from $A_{n,k}$ by removing from the center of each of the constituent [[interval|intervals]] the [[open]] [[interval]] of length $\frac{1}{2^{2m-2+n}}$. By induction, we find a general expression for the measure of each of the $A_{n,m}$: $$\mu\left(A_{n,m}\right) =1- \sum_{i=n-1}^{n+m} \frac{1}{2^i}.$$

It follows that $A_{n,m+1}$ has twice as many constituent [[interval|intervals]] as $A_{n,m}$, that for all $m$, $A_{n,m+1} \subset A_{n,m}$, and $\mu\left(A_{n,m+1}\right) = \mu\left(A_{n,m}\right) - \frac{1}{2^{m+n-1}}$. Now let $$C_n = \bigcap\limits_{m\in\mathbb N} A_{n,m}.$$ Because each $A_{n,m}$ is a finite union of [[closed]] [[interval|intervals]], it is itself [[compact]], and each $C_n$ is [[compact]]. Moreover, by the [[Cantor intersection theorem]], each $C_n$ is nonempty.

Now we show that each $C_n$ is [[nowhere dense]]. Let $G\subset [0,1]$ be an [[open]] [[interval]] such that $G\cap C_n \neq \emptyset$. Since each $A_{n,m}$ is a disjoint union of [[closed]] [[interval|intervals]] whose length approaches zero, there must be some $A_{n,m}$ which has some constituent [[interval]] $I \subset G$. Then there exists an [[open]] [[interval]]$J\subset I$ such that $J \cap A_{n,m+1} = \emptyset$, and consequently $J \cap C_n = \emptyset$. 

Because the $A_{n,m}$ form a descending sequence and by [[continuity of measure]], we have that $$\mu(C_n) = \lim_{m\to\infty} \mu(A_{n,m}) = \lim_{m\to\infty} 1- \sum_{i=n-1}^{n+m} \frac{1}{2^i} = 1- \sum_{i=n-1}^\infty \frac{1}{2^i}.$$

Now let $B = \bigcup\limits_{n\in\mathbb N} C_n$. and define $B_n = \bigcup\limits_{i=1}^n C_i$ so that $$\mu(B_n) = \mu\left(\bigcup_{i=1}^n C_i\right) \geq \mu(C_n) = 1- \sum_{i=n-1}^\infty \frac{1}{2^i}.$$ Because each $C_n$ is [[nowhere dense]], $B$ is of [[meager|first category]]. 

We now have that

$$\begin{align*}

\mu(B) &= \mu\left(\bigcup_{n\in\mathbb N} C_n\right) = \mu\left(\bigcup_{n\in\mathbb N} B_n\right) \\

&= \lim_{n\to\infty} \mu(B\_n)\\

&\geq \lim_{n\to\infty}1- \sum_{i=n-1}^\infty \frac{1}{2^i} =1.

\end{align*}$$

Thus $B$ is a [[meager|first category]] subset of $[0,1]$ with [[Lebesgue measure|measure]] 1, so its complement $[0,1]\setminus B$ is a [[comeager|residual]] subset of $[0,1]$ with [[measure zero]]. Let $$D = \bigcup_{z\in\mathbb Z} (B+z)$$ where $B+z$ denotes translation of $B$ by $z$ in the usual sense. Then $D$ is the countable union of [[meager|first category]] sets and is therefore [[meager|first category]]. Its complement in $\mathbb R$ is $$\mathbb R \setminus D = \bigcup\limits_{z\in\mathbb Z} (([0,1]\setminus B) + z)$$ is a [[comeager|residual]] set that is the countable union of measure zero sets, and is [[countable union of measure zero sets has measure zero|therefore]] also of measure zero.