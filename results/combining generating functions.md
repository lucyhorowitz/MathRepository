## Theorem
Suppose that $A(x)$, $B(x)$, and $C(x)$ are the [[ordinary generating function|ordinary generating functions]] for the sequecnes $\{a_k\}_{k\in\mathbb N}$, $\{b_k\}_{k\in\mathbb N}$, and $\{c_k\}_{k\in\mathbb N}$, respectively. Then 
- $C(x) = A(x) + B(x)$ if and only if $c_k = a_k + b_k$ for all $k$;
- $C(x) = A(x)B(x)$ if and only if $c_k = a_0b_k + a_1b_{k-1} +\cdots + a_kb_0$ for all $k$.

In the second case, $\{c_k\}_{k\in\mathbb N}$ is called the **convolution** of the sequences $\{a_k\}_{k\in\mathbb N}$ and $\{b_k\}_{k\in\mathbb N}$.

## Proof
Pretty straightforward algebraic manipulations.