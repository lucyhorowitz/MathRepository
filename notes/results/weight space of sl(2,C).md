## Theorem
Consider the [[special linear algebra]] $\mathfrak{sl}(2,\mathbb C) = \text{span}\{f,h,e\}$ and a [[Lie algebra representation|representation]] $(V,\rho)$. The [[weight space]] $$V_\lambda = \{v\in V\mid h\cdot v =\lambda v\}$$ has the properties
1. For any $v\in V_\lambda$, $e\cdot v = 0$ or $e\cdot v$ is an [[eigenvector]] of $h$ with [[eigenvalue]] $\lambda + 2$;
2. For any $v \in V_\lambda$, $f\cdot v = 0$ or $f\cdot v$ is an [[eigenvector]] of $h$ with [[eigenvalue]] $\lambda- 2$. 

## Proof
1. Note that $[h,e]=he-eh = 2e$ in $\mathfrak{sl}(2,\mathbb C)$.  Then for any $v\in V_\lambda$, we have $$h\cdot (e\cdot v) = (eh + 2e)\cdot v = \lambda(e\cdot v) +2(e\cdot v) = (2+\lambda)e\cdot v.$$
2. Note that $[h,f]=hf-fh = -2f$ in $\mathfrak{sl}(2,\mathbb C)$.  Then for any $v\in V_\lambda$, we have $$h\cdot (f\cdot v) = (fh - 2f)\cdot v = \lambda(f\cdot v) f2(f\cdot v) = (2+\lambda)f\cdot v.$$