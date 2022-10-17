## Theorem
Let $X$ and $B$ be [[compactly generated]] [[topological space|topological spaces]] and $A$ a [[closed]] [[subspace topology|subspace]] of $X$. If $i:A\to X$ is a [[cofibration]], then the induced map $p= B^i:B^X\to B^A$ is a [[fibration]]. 
## Proof

Note that $B^X$ means the space of functions $X\to B$, etc. 
#todo check that this is a [[homeomorphism]]: Let $Mi$ be the [[mapping cylinder]] of $i$. Then $$B^{Mi}= B^{X\times \{0\}\cup A\times I} \cong B^X\times_p (B^A)^I = Np$$ the [[mapping path space]] by [[homeomorphism]]. If $r:X\times I\to Mi$ is a [[deformation retraction|deformation retract]], then $$B^r:Np\cong B^{Mi}\to B^{X\times I} \cong (B^X)^I$$ is a [[mapping path space|path lifting function]]. #todo something something [[pushout]] 