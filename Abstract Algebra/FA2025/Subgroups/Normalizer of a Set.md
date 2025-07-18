> Def. (Normalizer of a Set): Define the set $$gAg^{-1} \coloneqq \{gag^{-1}:a \in A\}$$ and the set $$N_{G}(A) \coloneqq \{g \in G: gAg^{-1} = A\}.$$ Then $N_{G}(A)$ is a subgroup of $G$, called the *normalizer of $A$ in $G$*. 

## Proof:
1. Clearly $1 \in N_{G}(A)$ such that it is nonempty. 
2. Let $x, y \in N_{G}(A)$. By definition, $xax^{-1}, yay^{-1} \in A$ for all $a \in A$. Then $$\begin{aligned} (xy^{-1})a(xy^{-1})^{-1} &= (xy^{-1})a(yx^{-1}) \\ &= x(y^{-1}ay)x^{-1} \\ &= xa_{2}x^{-1} \qquad a_{2} \in A \\ &= a_{3} \qquad a_{3} \in A.\end{aligned}$$ Therefore, $xy^{-1} \in N_{G}(A)$. 
By Proposition 2.1 (The Subgroup Criterion), it follows that $N_{G}(A) \leq G$. 

## References:
1. [Group](../Introduction%20to%20Groups/Group.md)
2. [Subgroup](Subgroup.md)
3. [Proposition 2.1 (Subgroup Criterion)](Proposition%202.1%20(Subgroup%20Criterion).md)