## Theorem
Let $$f(x) = \sum_{n=0}^\infty a_nx^n$$ be a formal [[power series]] with $a_n$ elements of the [[p-adic field]] $\mathbb Q_p$. Define $$\rho = \frac{1}{\limsup\limits_{n\to\infty}\sqrt[n]{|a_n|_p}}$$ as the reciprocal of the [[limit supremum]] of the $n$th root of the $p$-adic [[absolute value]] of the $a_n$. Then:
- If $\rho = 0$, then $f(x)$ [[series convergence|converges]] only for $x=0$;
- If $\rho = \infty$, then $f(x)$ [[series convergence|converges]] for all $x\in\mathbb Q_p$;
- If $0<\rho<\infty$ and $\lim\limits_{n\to\infty}|a_n|_p\rho^n = 0$, then $f(x)$ [[series convergence|converges]] on $D = \{x\in\mathbb Q_p\mid |x|_p\leq\rho\}$;
- If $0<\rho<\infty$ and $\lim\limits_{n\to\infty}|a_n|_p\rho^n \neq 0$, then $f(x)$ [[series convergence|converges]] on $D = \{x\in\mathbb Q_p\mid |x|_p<\rho\}$.

## Proof (sketch)
Use the fact that [[series in p-adic numbers converges absolutely iff terms approach 0]] #write_proof 