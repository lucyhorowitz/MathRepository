We define the **Haar integral** over a [[topological space]] $X$ s follows: 

Any [[Borel σ-algebra|Borel]] [[measure space|measure]] $\mu$ on $X$ gives a [[linear transformation|linear]] [[functional]] $$\int:C_c(X) \to \mathbb C, f\mapsto \int_X(f) := \int_X f(x)\text d\mu(x)$$ where $C_c(X)$ is the collection of [[continuous]] complex-valued functions on $X$ with [[compact support]] and the [[Lebesgue integral|integral]] is defined according to that measure.

The Haar integral is this $\mathbb C$-linear function $\int:C_c(X) \to \mathbb C$  such that
1. for all $f\in C_c(X)$, if $f(x) \geq 0$ for all $x\in X$ then $\int_X f \geq 0$. Moreover, $\int_X f= 0$ implies that $f=0$.  (when $f(x)$ is real)
2. For any [[compact]] $K\subset X$, there exists some $c_K\geq 0$ such that for all [[continuous]] functions with [[support]] in $K$, $\left|\int_X f\right| \leq c_K\cdot \max\limits_{x\in K} |f(x)|$.