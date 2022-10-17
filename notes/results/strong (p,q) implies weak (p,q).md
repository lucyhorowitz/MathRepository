## Theorem
Let $(X,\Sigma,\mu)$ and $(Y,T,\nu)$  be [[measure space|measure spaces]] and let $T: L_1(X,\mu) \to L_1(Y,\nu)$ be an operator that maps [[measurable function|measurable functions]] on $X$ to measurable functions on $Y$. If $T$ is of type [[strong (p,q)]], then it is of type [[weak (p,q)]].
## Proof
Let $E_t = \{x \in X\mid |Tf(x)| > t\}$. Then $$t^q\nu(\{x \in Y\mid |(Tf)(x)| > t\})= \int_{E_t}t^q \text d \leq\int_{E_t}|Tf|^q\text d\nu \leq ||T_f||_q^q \leq (c||f||_p)^q.$$ Dividing by $t^q$ gives the desired inequality.