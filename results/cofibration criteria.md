## Theorem
Let $A$ be a [[closed]] [[subspace topology|subspace]] of the [[compactly generated]] [[topological space]] $X$ and let $I$ be the unit [[interval]]. Then the following statements are equivalent:
1. $(X,A)$ is an [[NDR pair]];
2. $(X\times I,(X\times\{0\})\cup( A\times I))$ is a [[NDR pair|DR pair]];
3. $(X\times \{0\})\cup (A\times I)$ is a [[deformation retraction|deformation retract]] of $X\times I$;
4. The inclusion $i:A\to X$ is a [[cofibration]].

## Proof
By [[product of NDR pairs is an NDR pair]], (1) implies (2). (2) trivially implies (3), and because [[mapping cylinder deformation retracts onto Y]] and because [[maps decompose as cofibration and homotopy equivalence]], (3) and (4) are equivalent. 

Now suppose that we have a [[deformation retraction|deformation retract]] $r:X\times I\to (X\times \{0\})\cup (A\times I)$. Let $\pi_1:X\times I\to X$ and $\pi_2:X\times I\to I$ be the usual projections. Define $u:X\to I$ using the [[supremum]]: $$u(x) = \sup\{t-\pi_2(r(x,t))\mid t\in I\}$$ and define $h:X\times I\to X$ by $$h(x,t)= \pi_1(r(x,t)).$$ Then $(h,u)$ are maps that make $(X,A)$ an [[NDR pair]]. We can see that the [[fiber]] $u^{-1}(0) = A$ because $u(x)=0$ implies that $r(x,t)\in A\times I$ for $t>0$ and then for $t=0$ because $A\times I$ is [[closed]] in $X\times I$. Thus we have shown (3) implies (1) so we are done.