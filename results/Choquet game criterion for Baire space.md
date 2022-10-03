## Theorem
Player 1 of the [[Choquet game]] $C(X,\emptyset,\mathcal G)$ has no [[winning strategy]] if and only if $X$ is a [[Baire space]].
## Proof
[[Borel determinacy theorem|Since]] the empty set is [[Borel σ-algebra|Borel]], the game is [[determined]]. Either Player 1 or Player 2 will always have a [[winning strategy]].

Suppose that $X$ is not a [[Baire space]]. Then there exists a nonempty [[open]] set of [[meager|first category]]. Denote this set by $G_1$, and write $G_1 = \bigcup\limits_{n\in\mathbb N} A_n$ where the $A_n$ are all [[nowhere dense]]. To begin playing according to the [[winning strategy]], Player 1 will choose this set for their first move. Player 2 must choose some nonempty [[open]] $G_2 \subset G_1$ Since $A_1$ is [[nowhere dense]], there exists an open set $H_1 \subset G_2$ such that $H_1\cap A_1 = \emptyset$. Player 1 will choose $G_3 = H_1$, and continue in this fashion. That is, in response to Player 2's move $G_{2n}$, Player 1 can always choose $G_{2n+1} = H_n$ so that $H_n \cap A_n = \emptyset$, and after infinitely many moves, The intersection of Player 1's choices are all disjoint from $A_n$ for all $n$. Thus $\bigcap\limits_{n\in\mathbb N} G_n = \emptyset$.

