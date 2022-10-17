## Theorem
Let $(X,\Sigma)$ be a [[measurable|measurable space]] and let $\mu$ and $\nu$ be [[σ-finite]] [[signed measure|signed measures]] on $X$. Then $\nu(A) = \int_A f\text d\mu +\nu_s(A)$ for some $f\in$[[Lp space|L]]$_1(\mu)$ and some [[measure space|measure]] $\nu_s$ that is [[singular measure|singular]] with respect to $\mu$. 
## Proof
First let $\mu$ and $\nu$ be non-negative, finite [[measure space|measures]] on $(X,\Sigma)$ and let $$\Phi = \left\{f\in L_1(\mu)\mid \int_A f\text d\mu \leq\nu(A), \forall A\in\Sigma\right\}.$$ Clearly $0 \in \Phi$. Next we wish to show that the maximum of two functions $f_1,f_2$ in $\Phi$ is also in $\Phi$. Let $A_1 = \{x\in A \mid (f_1-f_2)(x) \geq 0\}$ and let $A_2 = A\setminus A_1$. Because $f_1$ and $f_2$ are [[measurable function|measurable]], so is their difference, and therefore so are $A_1$ and $A_2$ by definition. Then $$\int_A \max(f_1,f_2)\text d\mu = \int_{A_1}f_1\text d\mu + \int_{A_2}f_2\text d\mu \leq \nu(A_1)+\nu(A_2) = \nu(A).$$ Thus $\max(f_1,f_2) \in \Phi$. Now consider a sequence $\{f_n\}_{n\in\mathbb N}$ of functions in $\Phi$ such that $$\int_X f_n\text d\mu \to \sup_{h\in\Phi} \int_X h\text d\mu$$ as $n \to \infty$. Pass to the sequence $\{g_n\}_{n\in\mathbb N}$ where $g_n = \max\limits_{n}(f_n)$. Then $\{g_n\}_{n\in\mathbb N}$ is a sequence in $\Phi$ such that $f_n \leq g_n$ for all $n$, so $$\lim_{n\to\infty} \int g_n\text d\mu=\sup_{h\in\Phi}\int_X g\text d\mu.$$ By the [[monotone convergence theorem]], the function $f = \lim\limits_{n\to\infty} g_n$ has the property that $\int_X f\text d\mu = \sup\limits_{h \in \Phi} \int_X h\text d\mu$ and also that $f\in \Phi$ because its [[Lebesgue integral|integral]] $$\int_A f\text d\mu = \lim\limits_{n\to\infty} \int_A g_n \text d\mu  < \nu(A).$$ For all $A\in \Sigma$, let $$\nu_s(A) = \nu(A) - \int_A f\text d\mu.$$ To show that $\nu_s$ is [[singular measure|singular]] with respect to $\mu$, define $$\nu_n(A) - \nu(A) - \int_A \left(f + \frac{1}{n}\right)\text d\mu.$$ Then $\nu_n$ is a [[signed measure]], so by the [[Hahn decomposition theorem]], we can write $X = P_n\cup N_n$. We wish to show that for all $n$, $\mu(P_n)=0$. Suppose for the sake of contradiction that $\mu(P_n) > 0$ for some $n$. Then consider the function $f + \frac{1}{n}\chi_{P_n}$, which is in $\Phi$ because $$\begin{align*}\int_A \left(f + \frac{1}{n}\chi_{P_n}\right)\text d\mu &= \int_{A\cap P_n}\left(f+\frac{1}{n}\right) \text d\mu + \int_{A\setminus P_n} f \text d\mu \\ &\leq \nu(A\cap P_n) + \nu(A\setminus P_n) \\ &= \nu(A).\end{align*}$$ But then $$\int_X f\text d\mu < \int_X \left(f+\frac{1}{n}\chi_{P_n}\right)\text d\mu$$ contradicting the maximality of $f$. Thus the set $P = \bigcup\limits_{n\in\mathbb N} P_n$ has $\mu$-measure $0$, so $\mu$ "lives on" $N = \bigcap\limits_{n\in\mathbb N} N_n$. Now we wish to show that $\nu_s$ "lives on" $P$. It is sufficient to show that $\nu(N) = 0$. By definition, $$\nu_n(N_n) = \nu_s(N_n)-\frac{1}{n}\mu(N_n)$$ which implies that $$\nu_s(N_n) - \nu_n(N_n) = \frac{1}{n}\mu(N_n).$$ Because $\nu_n$ is non-positive on $N_n$, it follows that $\nu_s(N_n) \leq \frac{1}{n}\mu(N_n)$ for all $n \in \mathbb N$. Thus $$\nu_s(N)\leq \nu_s(N_n) \leq \frac{1}{n} \mu(N_n) \leq \frac{1}{n}\mu(X).$$ Because we have assumed that $\mu(X)< \infty$, we can send $n$ to $\infty$ to see that $\nu_s(N) = 0$ as desired. Thus $\nu_s\perp\mu$.

We can extend this result to non-negative [[σ-finite]] [[measure space|measure spaces]] by partitioning the underlying space $X$ into countably many sub-spaces with finite $\mu$-[[measure space|measure]]. Then by the [[Hahn decomposition theorem]], we generalize to signed measures. 