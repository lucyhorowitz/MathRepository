## Theorem 
Let $f,g \in$ [[Lp space|L]]$_p$. Then $||f+g||_p \leq ||f||_p + ||g||_p$. This is essentially the [[norm|triangle inequality]].
## Proof
If $p=1$, we immediately have the inequality from the usual [[metric space|triangle inequality]]. Suppose instead that $1 < p < \infty$. Let $q = \frac{p}{p-1}$ so that $\frac{1}{p} + \frac{1}{q} = 1$. Then for $f \in L_p$, we have that $|f|^{p-1} \in L_q$ because $$\int(|f|^{p-1})^q = \int |f|^{q(p-1)} = \int|f|^p < \infty.$$  Note that $$||f+g||_p^p= \int|f+g|^p \leq \int|f|\cdot|f+g|^{p-1} + \int|g|\cdot|f+g|^{p-1}.$$ Because [[Lp is a vector space]], $f+g \in L_p$ and therefore $|f+g|^{p-1} \in L_q$. Then from [[Hölder's inequality]], $$\begin{align*}\int|f|\cdot|f+g|^{p-1} + \int |g| \cdot |f+g|^{p-1} &\leq ||f||_p +||(|f+g|^{p-1})||_q +||g||_p +||(|f+g|^{p-1})||_q\\
&= (||f||_p + ||g||_p) \cdot||(|f+g|^{p-1})||_q \\
&= ||f+g||_p^{p/q}.\end{align*}$$ Dividing both sides of the inequality by $||f+g||_p^{p/q}$ gives the desired result.