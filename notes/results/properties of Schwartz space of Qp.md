## Theorem
Let $\mathbb Q_p$ be the [[p-adic field]] and let $C_c^\infty(\mathbb Q_p)$ be its [[Schwartz space]]. Then
1. If $f\in C_c^\infty(\mathbb Q_p)$, then $f$ is [[continuous]]. 
2. If $f\in C_c^\infty(\mathbb Q_p)$, then there exists $m\in\mathbb Z$ such that the [[support]] of $f$ is contained in $\mathcal P^m$, the $m$th power of [[curly P]].
3. If $f\in C_c^\infty(\mathbb Q_p)$, then there exists $n\in \mathbb Z$ such that $f$ is constant on [[left coset|cosets]] of $\mathcal P^n$.
4. If $f\in C_c^\infty(\mathbb Q_p)$, then the [[image]] of $f$ is finite.
5. $C_c^\infty(\mathbb Q_p)$ is [[dense]] in [[Lp space|L1]]$(\mathbb Q_p) = \left\{f:\mathbb Q_p\to\mathbb C\mid \int_{\mathbb Q_p}|f(x)|\text dx < \infty\right\}$.

## Proof
1. Let $x\in\mathbb Q_p$. Then because $f$ is locally constant, there exists $n\in\mathbb Z$ such that if $y\in B_{p^{-n}}(x)$, then $f(x) = f(y)$. Given any $\varepsilon > 0$, just choose $\delta = p^n$ and we have [[continuous|continuity]]. 
2. We know that $\mathbb Q_p$ [[Qp is union of powers of curly P|is]] the union of all of the powers of [[curly P]] (that is, $\mathbb Q_p = \bigcup\limits_{n\in\mathbb Z}\mathcal P^n$), so if the [[support]] of $f$ is [[compact]], as it must be by definition, then there exists $m\in\mathbb Z$ such that the [[support]] is contained in $\mathcal P^m$. 
3. #write_proof 
4. #write_proof 
5. (sketch) Choose $f\in L^1(\mathbb Q_p)$ and fix $\varepsilon >0$. First, find a [[compact]] set $A\subseteq \mathbb Q_p$ such that the [[Lebesgue integral|integral]] of the [[absolute value]] of $f$ is $$\int_{\mathbb Q_p\setminus A}|f(x)|\text dx < \frac{\varepsilon}{3}.$$ Now find $g\in C_c^\infty(\mathbb Q_p)$ such that $$\int_{\mathbb Q_p\setminus A}|f(x)-g(x)|\text dx < \frac{\varepsilon}{3}$$ and $h\in C_c^\infty(\mathbb Q_p)$ such that $$\int_{\mathbb Q_p\setminus A}|h(x)-g(x)|\text dx < \frac{\varepsilon}{3}.$$