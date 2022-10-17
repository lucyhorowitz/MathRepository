Let $X$ be a set. The **symmetric group** $S_X$ is the set of all [[bijective|bijections]] from $X$ to itself.

When $X$ is finite with [[cardinal number]] $n$, it is denoted $S_n$ and consists of the set of permutations on $n$ letters. 

### Proof that $S_X$ is a [[group]] under function composition
- Let $f,g\in S_X$. Then $f\circ g$ is also a function from $X$ to itself, and moreover [[composition of bijections is bijective|their composition is also a bijection]]. So $S_X$ is closed under function composition.
- [[function composition is associative|Function composition is]] [[associative]].
- The function $\text{id}_X:X\to X$ given by $x\mapsto x$ for all $x\in X$ serves as the [[identity element]] for $S_X$. 
- Every element of $X$ [[bijective functions are invertible|has]] an associated [[inverse element]].

https://www.wikidata.org/wiki/Q849512