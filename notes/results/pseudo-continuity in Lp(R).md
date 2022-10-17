## Theorem
Let $f \in$ [[Lp space|L]]$_p(\mathbb R)$ for some $1\leq p < \infty$ and let $f_t(x) = f(x+t)$. Then $f_t$ [[sequence convergence|converges]] to $f$ as $t$ goes to zero.
## Proof
Let $A$ be the set of functions $f \\in L\_p(\\mathbb R)$ for which $f_t \to f$ as $t\to 0$. This is a [[vector subspace]] of $L_p(\mathbb R)$. Let $f, g\in A$. Then $$(f+g)_t = (f+g)(x+t) = f(x+t) + g(x+t),$$ and therefore $$||(f+g)_t - (f+g) ||_p = ||f_t - f + g_t -g||_p \leq ||f_t -f ||_p + ||g_t-g||_p \\to 0.$$ By the scaling property of the [[norm]], we also have that scalar multiples of functions in $A$ are also in $A$. 

  

Now we will show that $A$ is [[closed]]. Let $\{f_n\}_{n\in\mathbb N}$ be a sequence of functions in $A$ converging to $f \in L_p(\mathbb R)$, and fix $t \in \mathbb R$. Then we have $$||f_t - f||_p \leq ||f_t - f_{n,t}||_p + ||f_{n,t} - f_n||_p + ||f_n - f||_p.$$ Because $t$ is fixed and $f_n \to f$, we have that $f_{n,t} \to f_t$. Because all of the $f_n \in A$, we have that $f_{n,t} \to f_n$, and by assumption, $f_n \to f$. Thus $f_t \to f$ in $L_p(\mathbb R)$. Thus $A$ contains all of its [[limit point|limit points]], and it is therefore [[closed]].

  

Now we show that the [[characteristic function]] of an interval $I \subset\mathbb R$ is in $A$. This function is only dis[[continuous]] at the endpoints of $I$, so by the definition of continuity of real-valued functions on $\mathbb R$ and the [[continuity condition for integrability|fact]] that a function with a [[measure zero]] set of discontinuities is [[Riemann integrable|integrable]], we have that $$\int_\mathbb R |\chi_{I,t} - \chi_I| \to 0$$ as $t \to 0$. 

  

Now we show that the [[characteristic function|characteristic functions]] of [[measurable]] sets are contained in $A$. Let $E\subset \mathbb R$ be [[measurable]] with $\mu(E) < \infty$, and let $\chi_E$ be its [[characteristic function]]. By [[Littlewood's principles|Littlewood's first principle]], for all $\varepsilon > 0$, there exists a finite collection $\{I_n\}_{n\in\mathbb N}$ of [[interval|intervals]] such that the [[symmetric difference]] has the property $$\mu\left(E \triangle \bigcup_{n=1}^k I_n\right) < \varepsilon.$$ This immediately implies that $$\left|\left|\chi_E - \sum_{n=1}^k \chi_{I_n} \right|\right|_p < \varepsilon.$$ Since the characteristic functions of intervals are in $A$, we have a similar argument to the one used to show that $A$ is closed that $$||\chi_{Et} - \chi_E||_p \\eq \left|\left| \chi_{Et} - \sum_{n=1}^k \chi_{I_nt}\right|\right|_p + \left|\left| \sum_{n=1}^k \chi_{I_nt} - \sum_{n=1}^k \chi_{I_n}\right| \right|_p + \left|\left| \sum_{n=1}^k \chi_{I_n} - \chi_E\right| \right|_p \to 0$$ as $t \to 0$. Thus the characteristic functions of measurable sets satisfy the desired property.

Because characteristic functions of measurable sets are in the [[vector space]] $A$, the [[simple function|simple functions]] are all contained in $A$ as finite linear combinations of characteristic functions. Moreover, the [[simple functions are dense in Lp|simple functions are dense]] in $L_p(\mathbb R)$, so their [[closure]] is the entirety of $L_p(\mathbb R)$, but the fact that $A$ is [[closed]] implies that $L_p(\mathbb R) \subseteq A$. Thus $L_p(\mathbb R) = A$, and $f_t \to f$ as $t \to 0$ for every $f \in L\_p(\mathbb R)$.