## Theorem
Let $Q\subset\mathbb R^n$ be a [[rectangle]] and let $f: Q\to\mathbb R$ be a [[bounded]] function. Let $D\subset Q$ be the set of  points where $f$ is not [[continuous]]. Then $f$ is [[Riemann integrable]] if and only if $D$ has [[measure zero]].
## Proof
Let $f:Q\to\mathbb R$ be a [[bounded function|bounded]] [[Lebesgue measure|Lebesgue]] [[measurable function|measurable]] function Because $f$ is [[bounded function|bounded]], there exists $M \geq 0$ such that $|f(x)| \leq M$ for all $x \in Q$. Suppose that the set $D \subset Q$ of points at which $f$ is dis[[continuous]] is of [[measure zero]]. Given $\varepsilon > 0$, we wish to find a [[partition]] $P$ of $[0,1]$ for which the difference of the [[upper sum|upper]] and [[lower sum|lower sums]] is $U(f,P) - L(f,P) < \varepsilon$. By the [[mesh condition for integrability]], this will show that $f$ is [[Riemann integrable]].

Let $\epsilon = \frac{\varepsilon}{2(M+1)}$, and cover $D$ with countably many [[open]] [[rectangle|rectangles]] $I_i$. For each $y \in Q\setminus D$, let $J_y$ be an [[open]] [[rectangle]] such that $y \in J_y$ and $|f(x)-f(y)| < \epsilon$ whenever $x \in J_y \cap Q$. The open [[rectangle|rectangles]] $I_i$ and $J_y$ cover $Q$, which is [[compact]] by the [[Heine-Borel theorem]] as a [[closed]] and [[bounded]] subset of $\mathbb R^n$. Thus there exist finite subcollections $$\{I_i\}_{i=1}^n\text{ and } \{J_{y_j}\}_{j=1}^m$$ of [[rectangle|rectangles]] that cover $Q$. Moreover, the $I_i$ are such that the sum of their [[measure space|measures]] $\sum\limits_{i=1}^n\mu(I_i) < \epsilon$ and the $J_{y_j}$ are such that $|f(x)-f(y)| < 2\epsilon$ for $x,y \in J_{y_j} \cap Q$. 

Pass to the [[closure]] of these [[rectangle|rectangles]] and their intersections with $Q$ and use their endpoints to define a [[partition]] $P$ of $Q$. Consider two collections $A$ and $B$ of sub[[rectangle|rectangles]] of $P$ such that each $K \in A$ is a subset of some $I_i$ and each $H \in B$ is a subset of some $J_{y_i}$. Then taking the [[Riemann sum|Riemann sums]] over $A$ and $B$, we have 

$$\begin{align*}

\sum_{R\in A} (M_R(f)-m_R(f)) \mu(R) &\leq 2M \sum\_{R \in A} \mu(R)\\

\sum_{R\in B} (M_R(f)-m_R(f)) \mu(R) &\leq 2\epsilon\sum_{R\in B}\mu(R).

\end{align*}$$

We also have 

$$\begin{align*}
\sum_{R \in A} \mu(R) &\leq\sum_{i=1}^n \sum_{R \subset I_i} \mu(R) = \sum_{i=1}^n \mu(I_i) < \epsilon\\

\sum_{R\in B} \mu(R) &\leq \sum_{R\subset Q} \mu(R) = \mu(Q).

\end{align*}$$ 

Thus $U(f,P) - L(f,P) < 2M\epsilon + 2\epsilon = \varepsilon$, and $f$ is [[Riemann integrable]] on $Q$.

Now suppose that $f$ is [[Riemann integrable]] over $Q$. Let $\varepsilon > 0$, and let $D_m = \{x \in Q \mid \text{osc}(f,x) \geq 1/m\}$ be the set of points in $Q$ for which the [[oscillation]] of $f$ is less than $\frac{1}{m}$. Then $D$ as defined above is the union of all the $D_m$ and there exists a [[partition]] $P$ of $Q$ on which $U(f,P) - L(f,P) < \frac{\varepsilon}{m}$. Then let $D_m'$ be the set of points in $D_m$ that are also points in $P$. This is at most a finite set of points, and is therefore of [[measure zero]]. Let $D_m''$ be the set of points in $D_m$ that do  *not* belong to $P$. Let $\{I_i\}_{i=1}^k$ be the sub[[rectangle|rectangles]] determined by $P$ that contain points of $D_m''$. For each $i$, $I_i$ contains some $x \in D_m''$ not as an endpoint and there therefore exists $\delta > 0$ such that $J_\delta = (x-\delta, x+\delta)^n \subset I_i$. Then we have $$\frac{1}{m} \leq \text{osc}(f,x) \leq M_{J_\delta}(f) - m_{J_\delta}(x) \leq M_{I_i}(f)- m_{I_i}(f).$$ Multiplying by $\mu(I_i)$ and taking the sum over $I$, we find that $$\sum_{i=1}^k \frac{\mu(I_i)}{m} \leq U(f,P) - L(f,P) < \frac{\varepsilon}{m}.$$ Thus the $I_i$ have total [[measure space|measure]] less than $\varepsilon$ for any $\varepsilon > 0$, so $D_m''$ is a set of [[measure zero]]. [[countable union of measure zero sets has measure zero|Thus]] $D$ is also measure zero as the union of countably many sets of measure zero.