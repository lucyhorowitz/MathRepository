## Theorem
Note: Write $B\cup_g X$ for the [[pushout]] of a [[cofibration]] $i:A\to X$ and a function $g:A\to B$.

If $i:A\to X$ is a [[cofibration]] and $g:A\to B$ is any map, then the induced map by the [[pushout]] $B\to B\cup_g X$ is a [[cofibration]].
## Proof
Notice that $(B\cup_gX)\times I\cong (B\times I)\cup_{g\times\text{id}}(X\times I)$ and consider a typical test diagram for the [[cofibration|homotopy extenson property]]. The proof is a formal chase of the diagram 
![[Screen Shot 2022-02-17 at 4.05.13 PM.png]]
Use that $A\to X$ is a [[cofibration]] to obtain a [[homotopy]] $\bar h:X\times I\to Y$ and use the right-hand [[pushout]] to see that $\bar h$ and $h$ induce the required [[homotopy]] $\tilde h$. 

This is a [[dual]] result to the result that [[pullbacks of fibrations are fibrations]].