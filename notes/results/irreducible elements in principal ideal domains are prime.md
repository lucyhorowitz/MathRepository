## Theorem
Let $R$ be a [[principal ideal domain]]. Then if $x\in R$ is [[irreducible element of an integral domain|irreducible]], then it is [[prime element of an integral domain|prime]].
## Proof
Assume that $x$ is [[irreducible element of an integral domain|irreducible]] and let $x\mid ab$. Consider the [[ring ideal|ideal]] [[generate a ring ideal|generated]] by $a$ and $x$ (written $(a,x)$). 
###### Case 1: 
If $(a,x)=R$, then there exist $u,v\in R$ such that $ux+av = 1$, because [[ideals containing a unit are the whole ring]]. This in turn implies that $av\equiv 1\pmod x$.  That is, $av+(x) = 1 + (x)$ is in the [[quotient ring]] $R/(x)$. But because $x$ [[division in a ring|divides]] $ab$, it follows that $ab\equiv 0\pmod x$. So $b\equiv vab \equiv v(0) \equiv 0\pmod x$, which implies that $x\mid b$. 
###### Case 2: 
If $(a,x)\neq R$, then let $d\in R$ be such that $(a,x) = d$. This is possible because $R$ is a [[principal ideal domain]]! Then $x\in (d)$ implies the existence of $e\in R$ such that $ed = x$. But $(d)\subsetneq R$ implies that $d$ is not a [[unit of a ring|unit]], so because $x$ is [[irreducible element of an integral domain|irreducible]], $e$ must be a [[unit of a ring|unit]]. [[equality of principal ideals in integral domains|Thus]] $(d)=(x) = (x,a)$ which implies that $a\in (x)$, so $x\mid a$. [