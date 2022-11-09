Let $\mathbb k$ be some [[field]]. Let $G$ be a [[group]] and let $\rho:G\to GL(V)$ be a [[group representation|representation]] of $G$ in the $\mathbb k$-[[vector space]] $V$. Let $V^* = \text{Hom}_\mathbb k(V,\mathbb k)$ be the [[dual space]] of $V$. By the [[Riesz representation theorem]], there is a canonical pairing $\langle \cdot,\cdot \rangle:V^*\times V \to\mathbb k$ that lets us write [[linear transformation|linear]] functionals $\phi:v\mapsto \phi(v)$ as $\langle \phi,v\rangle$. 

The $G$-[[conjugacy classes|action]] $v\mapsto \rho(g)v$ on $V$ induces [[induced action of group on maps|the action on the space of functions on]] $V$, of which $V^*$ is an [[invariant subspace]]. Explicitly, $g\in G$ acts on $\phi \in V^*$ by $$[v\mapsto \phi((\rho(g))^{-1}(v))] = \langle \phi, (\rho(g))^{-1}v\rangle = \langle ((\rho(g))^{-1})^\intercal, v\rangle = \langle (\rho(g^{-1})^\intercal, v\rangle$$ where $(\rho(g^{-1}))^\intercal$ is the [[adjoint of a linear transformation|adjoint]] of the [[linear transformation|operator]] $\rho(g):V\to V$. This action on $V^*$ gives a [[group homomorphism]] $\rho^\vee:G\to GL(V^*)$ where $\rho^\vee(g) = (\rho(g^{-1}))^\intercal$ that is called the **contragradient representation** of the original representation $\rho$. 