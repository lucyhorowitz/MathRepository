## Theorem
Let $U \subset \mathbb R^n$ be [[open]]. A function $f:U\to\mathbb R^m$ is [[differentiable]] at $a \in U$ if and only if each of its [[component function|component functions]] is [[differentiable]] at $a$.
## Proof
Suppose that $F$ is [[differentiable]] with derivative at $x$ given by $A(x)$. Write $f = (f_1,\dots,f_m)$ and $A = (A_1,\dots, A_m)$.
- $\begin{align*} &\lim\limits_{h\to 0} \frac{f(a+h)-f(a)-A(h)}{||h||}\\ =& \lim\limits_{h\to 0} \frac{(f_1(a+h), \dots, f_m(a+h))-(f_m(a),\dots,f_m(a)) -(A_1(h),\dots, A_m(h)}{||h||}\\ =& \text{  }0\end{align*}$ 
if and only if $\lim\limits_{h\to 0} \frac{f_i(a+h) - f_i(a) -A_i(h)}{||h||} = 0$ for all $i$.
- This corresponds exactly to the definition of [[differentiable]] for the $f_i$.