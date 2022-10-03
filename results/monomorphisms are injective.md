## Theorem
Let $f:A\to B$ be a function considered as a [[category|morphism]] in the [[category of sets]]. Then $f$ is [[injective]] if and only if it is a [[monomorphism]].
## Proof
Suppose that $f$ is [[injective]]. Then $f$ [[injective functions have left inverses|has]] a left [[inverse function|inverse]] $g:B\to A$. Let $\alpha,\beta:Z\to A$ be arbitrary functions from a set $Z$ to $A$ and suppose that $$f\circ \alpha = f\circ \beta.$$ Then $$g\circ f\circ a = g\circ f\circ \beta,$$ and by [[associative|associativity]] of function composition, we have that $\alpha = \beta$. Thus $f$ is a [[monomorphism]].

Now suppose that $f$ is a [[monomorphism]]. Choose some singleton $\{p\}$ from any set. Functions $\alpha,\beta:\{p\} \to A$ are determined entirely by $\alpha(p)=a$ and $\beta(p)=b$ In this case, the [[monomorphism]] condition states that $f(a)=f(b)$ implies $\alpha=\beta$. Since the two functions are equal if and only if they send $p$ to the same point, we have that $f(a)=f(b)$ implies that $a=b$, so $f$ is [[injective]].