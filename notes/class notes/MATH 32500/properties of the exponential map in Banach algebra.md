## Theorem 
Let $A$ be a [[Banach algebra]] and  consider the [[exponential map]] $$a\mapsto e^{a} = \sum_{n=0}^\infty \frac{a^n}{n!}.$$ 
Then 
1. This map is [[absolute convergence|absolutely convergent]] on all of $A$, i.e. its [[radius of convergence]] is infinite;
2. For any $a,b\in A$ that [[commute]], $e^{a+b} = e^ae^b$;
3. $e^{-a} = (e^a)^{-1}$;
4. For any $a\in A$, the map $t\mapsto e^{ta}$ is a [[group homomorphism]] $(\mathbb R,+) \to A^\times$, the [[group]] of [[inverse element|invertible]] elements of $A$ that is [[smooth]] and for which the $n$th [[differentiable|derivative]] is $$\frac{d^n(e^{ta})}{dt^n} = a^ne^{ta};$$
5. The map $\exp: A\to A$ is [[differentiable]] with differential at $0$ given by $$d_0 \exp = \text{Id}_A;$$
6. For sufficiently small $r$, the set $\exp(D_r(A))$ is a [[neighborhood]] of $1\in A$ and the [[matrix logarithm|logarithm]] is an [[inverse function|inverse]] [[diffeomorphism]] to $\exp$ on this neighborhood.
## Proof
#write_proof [[binomial theorem]][[power series convergence implies derivative convergence]]  HOMEWORK 