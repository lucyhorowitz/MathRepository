---
aliases: deformation retract
---
### [[Algebraic Topology|Hatcher]] version
Let $X$ be a [[topological space]]. A **deformation retraction** of $X$ onto a [[subspace topology|subspace]] $A$ is a family of [[continuous]] maps $f_t: X\to X$ for $t\in [0,1]$ such that $f_0 = \mathbb 1$ (the [[identity function|identity]]), the [[image]] $f_1(X) = A$, and ${f_t}_{|A} = \mathbb 1$ for all $t$ and such that the associated map $X \times [0,1] \to X$ given by $(x,t)\mapsto f_t(x)$ is also [[continuous]].

### [[A Concise Course in Algebraic Topology|Concise]] version
A [[subspace topology|subspace]]$A$ is a **deformation retract** of $X$ if there exists a [[homotopy]] $h:X\times I\to X$ such that $h(x,0) = x$, $h(a,t) = a$, and $h(x,1)\in A$ for all $a\in A$ and $t\in T$. Such a [[homotopy]] is a **Deformation retraction** of $X$ onto $A$

https://www.wikidata.org/wiki/Q2141963
#todo WD doesn't have the other name as *deformation* retract
