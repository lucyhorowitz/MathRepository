## Theorem
A function $f:A\to B$ has a left [[inverse function|inverse]] if and only if it is [[injective]].
## Proof
Suppose that $f$ has a left [[inverse function|inverse]]. then there exists a function $g:B\to A$ such that $g\circ f(a) = a$ for all $a\in A$. Let $a,b \in A$ such that $a\neq b$. Then $$g(f(a)) = a \neq b = g(f(b)),$$ so $f$ is [[injective]].

Now suppose that $f$ is [[injective]]. We wish to construct a left [[inverse function|inverse]] $g:B\to A$ for $f$. Fix some $s\in A$ and let $$g(b) = \begin{cases}a & \exists a\in A:b=f(a)\\ s & b\notin\text{im}(f).\end{cases}$$ This is indeed a function, and moreover it is a left [[inverse function|inverse]] for $f$. 