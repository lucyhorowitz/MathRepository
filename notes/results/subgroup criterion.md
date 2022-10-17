## Theorem
A subset $H$ of the [[group]] $G$ is a [[subgroup]] if and only if 
1. $H \neq \emptyset$ and
2. for all $x,y \in H$, $xy^{-1}\in H$.

Moreover, if $H$ is finite, then it is sufficient to check that $H$ is nonempty and closed under the group [[binary operation|operation]].
## Proof
The forward direction is clear. 

Now suppose that (1) and (2) hold. Then let $x\in H$ and set $y=x$ so that by (2), $xy^{-1} = xx^{-1} = e \in H$. Since $e \in H$, for every $x\in H$ we have again by (2) that $ex^{-1} = x^{-1} \in H$. Thus for $x,y\in H$, we have $x,y^{-1} \in H$ and finally $x(y^{-1})^{-1} = xy\in H$ so that $H$ is closed under the group [[binary operation|operation]]. Thus it is a [[subgroup]] of $G$. 

Now suppose that $H$ is finite and closed under the group [[binary operation|operation]]. Let $x\in H$. Then there are only finitely many distinct $x^n$ for integer $\mathbb N$. Thus $x^a = x^b$ for some $b > a$. Let $m= b-a$. Then $x^n = e$, which implies that every element in $H$ is of finite [[order of a group element|order]]. Thus $x^{n-1} = x^{-1} \in H$ and $H$ therefore contains the [[inverse element|inverse]] of each of its elements and is a [[subgroup]] of $G$. 