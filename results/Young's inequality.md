## Theorem
Let $a,b \geq 0$ be nonnegative real numbers. If $p,q > 1$ are real numbers such that $\frac{1}{p} + \frac{1}{q}=1$, then $$ab \leq \frac{a^p}{p}+ \frac{b^q}{q},$$ with equality if and only if $a^p = b^q$.
## Proof
The inequality is trivial if $a$ or $b$ is zero, so assume $a,b > 0$. Then set $t = \frac{1}{p}$ and $1-t = \frac{1}{q}$. Then because the logarithm function is [[concave]], $$\ln(ta^p + (1-t)b^q) \geq t\ln(a^p)+(1-t)\ln(b^q) = \ln(a) + \ln(b) = \ln(ab).$$ Then by exponentiating, we find
$$\begin{align*}
	e^{\ln(ta^p + (1-t)b^q)} &\geq e^{\ln(ab)} \\
	ta^p + (1-t)b^q &\geq ab \\
	\frac{a^p}{p} + \frac{b^q}{q} &\geq ab
\end{align*}$$
as desired.
