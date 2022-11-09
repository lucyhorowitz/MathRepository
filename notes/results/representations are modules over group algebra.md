## Theorem
Let $G$ be a [[group]]. Defining a [[group representation|representation]] $\rho:G\to GL(V)$ is equivalent to endowing the [[vector space]] $V$ with the structure of a [[module over a ring|module]] over the [[group algebra]] $\mathbb kG$.
## Proof 
The [[group action|action]] of an element $a = \sum_{g\in G}c_g1_g$ on the element $v \in \mathbb V$ is defined by $$av = \sum_{g\in G}c_g \rho(g)v.$$ We end up with the correspondence between [[group representation|representations]] of $G$ and $\mathbb kG$-[[module over a ring|modules]]:
- $W\subseteq V$ is a [[subrepresentation]] of $V$ if and only if $W$ is a $\mathbb kG$-[[submodule]] of $V$;
- A [[group representation|representation]] of $G$ in $V$ is [[irreducible representation|irreducible]] if and only if $V$ is a [[simple module|simple]] $\mathbb kG$-[[module over a ring|module]];
- A [[group representation|representation]] of $G$ in $V$ is [[complete reducibility|completely reducible]] if and only if $V$ is a [[semisimple module|semisimple]] $\mathbb kG$-[[module over a ring|module]];
- $f:V\to W$ is an [[morphism of group representations|intertwiner]] if and only if $f$ is a $\mathbb kG$-[[module homomorphism]]. In particular the [[vector space]] of $G$-[[morphism of group representations|intertwiners]] is equal to the [[vector space]] of $\mathbb kG$-[[module homomorphism|module homomorphisms]]: $$\text{Hom}_G(V,W) = \text{Hom}_{\mathbb kG}(V,W).$$