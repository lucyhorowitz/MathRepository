## Theorem
Let $p:E\to B$ be a [[covering space]]. Let $b\in B$ adn $e,e'\in F_b$ (defined as the [[fiber]] of the point $b$). Let $I$ denote the unit [[interval]]. Then
1. A [[path]] $f:I\to B$ with $f(0) =b$ [[lift|lifts]] uniquely to a path $g:I\to E$ such that $g(0) = e$ and $p\circ g=f$.
2. [[homotopy equivalence of paths|Equivalent]] [[path|paths]] $f\simeq f':I\to B$ that start at $b$ [[lift]] to [[homotopy equivalence of paths|equivalent]] [[path|paths]] $g\simeq g':I\to E$ that start at $e$, hence $g(1) = g'(1)$.
3. The [[continuous functions induce homomorphisms on homology groups|induced homomorphism]] between [[fundamental group|fundamental groups]] $p_*:\pi_1(E,e)\to \pi_1(B,b)$ is a [[monomorphism]].
4. The [[image]] $p_*(\pi_1(E,e'))$ is [[conjugate subgroups|conjugate]] to $p_*(\pi_1(E,e))$.
5. As $e'$ "runs through" $F_b$, [[image of group homomorphism is subgroup of codomain|the]] [[group|groups]] $p_*(\pi_1(E,e'))$ "run through" all [[conjugate subgroups|conjugates]] of $p_*(\pi_1(E,e))$ in $\pi_1(B,b).

## Theorem [[functor|functorially]]
The first two parts can be stated as follows: 

Let $p:E\to B$ be a [[covering space]]. Then the induced [[functor]] (the [[fundamental groupoid]]) $\Pi(p) : \Pi(E) \to \Pi(B)$ is a [[covering of groupoids]].

The last three parts can be stated as follows: 

 Let $p:\mathcal E\to \mathcal B$ be a [[covering of groupoids]], let $b$ be an object of $\mathcal B$, and let $e$ and $e'$ be objects of $\mathcal E$. Then 
 3. $p:\pi(\mathcal E,e)\to \pi(\mathcal B,b)$ is a [[monomorphism]]. [^1]  Moreover, [[monomorphisms are injective]].
 4. $p(\pi(\mathcal E,e'))$ is [[conjugate subgroups|conjugate]] to $p(\pi(\mathcal E,e))$.
 5. As $e'$ runs through $F_b$, the [[group|groups]] $p(\pi(\mathcal E,e'))$ run through all [[conjugate subgroups|conjugates]] of $p(\pi(\mathcal E,e))$ in $\pi(\mathcal B,b)$. 
 
 [^1]: Note that $\pi(\mathcal E,e)$ denotes the [[group]] of [[automorphism|automorphisms]] of $e$. as defined in the [[star of an object]]. 


## Proof
1. Divide $I$ into [[subinterval|subintervals]], each mapping to a [[covering space|fundamental neighborhood]]. #todo *how do we know we can do this?* [[lift|Lift]] $f$ to $g$ [[induction|inductively]] by using the [[homeomorphism]] property of [[covering space|fundamental neighborhoods]]. 
2. Let $h:I\times I\to B$ be a [[homotopy]] $f\simeq f'$ through [[path|paths]] $b\to b'$. [[partition of a set|Partition]] the square into subsquares each mapping to a [[covering space|fundamental neighborhood]] under $f$. Again proceeding by [[induction]] #todo *how, exactly?* $h$ [[lift|lifts]] uniquely to to a [[homotopy]] $H:I\times I \to E$ such that $H(0,0) = e$ and $p\circ H = h$. By uniqueness, $H$ is a [[homotopy]] $g\simeq g'$ through [[path|paths]] $e\to e'$, where $g(1) = e'=g'(1)$. 

The next parts are proved in terms of the [[functor|functorial]] statement of the theorem.

3.  If $g,g'\in\pi(\mathcal E,e)$ and $p(g) = p(g')$, then $g=g'$ by the [[injective|injectivity]] of $p$ on the [[star of an object|star]] $\text{St}(e)$.
4.  Because $\mathcal E$ is [[connected category|connected]], there exists a map $g:e\to e'$. [[inner automorphism of a group|Conjugation]] by $g$ gives a [[group homomorphism|homomorphism]] $\pi(\mathcal E,e)\to  \pi(\mathcal E,e')$ that maps under $p$ to [[inner automorphism of a group|conjugation]] of $\pi(\mathcal B,b)$ by its element $p(g)$. 
5.  The [[surjective|surjectivity]] of $p$ on the [[star of an object|star]] $\text{St}(e)$ gives that any $f\in\pi(\mathcal B, b)$ is of the form $p(g)$ for some $g\in \text{St}(e)$. If $e'$ is the target of $g$, then $p(\pi(\mathcal E,e'))$ is the [[conjugate subgroups|conjugate]] of $p(\pi(\mathcal E,e))$ by $f$.
