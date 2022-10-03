## Theorem
Let $A$ be a [[locally compact group|locally compact]], [[compact]], [[abelian]], [[Hausdorff]] [[topological group|topological]] [[group]].  Then if $\psi\in\widehat A$ is a nontrivial [[multiplicative character]] in the [[Pontryagin dual]], then the [[Lebesgue integral|integral]] under the [[Haar measure]] over $A$ is zero. That is, $$\int_A \psi(x)\text{d}x =0.$$
## Proof
Find $y\in A$ such that $\psi(y) \neq 1$. Then because $\psi$ is a [[group homomorphism|homomorphism]], because the [[Haar measure]] is translation invariant, and finally by [[linearity of the integral]], $$\int_A\psi(x)\text dx = \int_A\psi(x+y)\text dx = \int_A\psi(x)\psi(y)\text dx =\psi(y)\int_A \psi(x)\text dx.$$ That is, the integral is equal to a nonunit multiple of itself. Thus it must be zero. 