## Theorem 
Let $G$ be a [[compact]] [[topological group]] and let $X$ be a [[topological space]]. For any [[continuous]] function $f:X\to \mathbb C$, the [[averaging]] function is [[G-invariant function|G-invariant]].

## Proof
Fix $x\in X$ and define $\phi:G\to \mathbb C$ by $\phi(g) = f(gx)$. By [[G-invariant function|invariance]] of the [[Haar integral]], we have that $$\int_G\phi(g)\text dg = \int_G \phi(gh) \text dg = \int_Gf(ghx) = \text{vol}(G) \cdot \text{Av}(f)(hx)$$ while $$\int_Gf(gx)\text dg = \text{vol}(G) \cdot \text{Av}(f)(x)$$ as desired.