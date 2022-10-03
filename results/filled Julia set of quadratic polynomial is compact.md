## Theorem
The [[filled Julia set]] of the [[polynomial]] $f_c(z) = z^2+c$ is [[compact]].
## Proof
By definition, there exists a constant $T$ depending on $c$ such that if $|z| > T$, then $z\notin K(f_c)$. Moreover, $z\notin K(f_c)$ if and only if there exists $n \in \mathbb N$ such that $|f_c^{\circ n}(z)| > T$.

Let $U = \{z \in\mathbb C \mid |z| > T\}$. This set is [[open]] and $z \in K(f_c)$ if and only if its iterate $f_c^{\circ n}(z)$ is in $U$. This implies that $$K(f_c) = \mathbb C \setminus \bigcup_{n\in\mathbb N} f_c^{-\circ n}(U)$$ where $f_c^{-\circ n}(U)$ denotes the [[preimage]] of $U$ under the $n$th iteration of $f_c$. This implies that $K(f_c)$ is [[closed]]. By definition, it is [[bounded]], so by the [[Heine-Borel theorem]], it is [[compact]]. 