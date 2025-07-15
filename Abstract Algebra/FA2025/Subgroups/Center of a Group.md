> Def. (Center of a Group): Define the set $$Z(G) \coloneqq \{g \in G: gx = xg \text{ for all $x \in G$}\}.$$ Then $Z(G)$ is a subgroup of $G$, called the *center of $G$*; i.e., $Z(G)$ is the subgroup of $G$ consisting of all elements of $G$ that commute with every element of $G$. 

## Proof:
1. Clearly $Z(G)$ is nonempty since $1 \in Z(G)$. 
2. Let $x, y \in Z(G)$. For any $g \in G$, $y \in Z(G)$ means: $$yg = gy \iff y^{-1}yg = y^{-1}gy \iff g = y^{-1}gy \iff gy^{-1} = y^{-1}g.$$ I.e., $y^{-1} \in Z(G)$. Therefore, $$(xy^{-1})g = x(y^{-1}g) = (xg)y^{-1} = g(xy^{-1}),$$ such that $xy^{-1} \in Z(G)$. 
Therefore, by Proposition 2.1 (The Subgroup Criterion), $Z(G)$ is a subgroup of $G$. 

We could have proven this theorem much more succinctly by noting that $Z(G) = C_{G}(G)$, and hence must be a subgroup by an earlier proof. 

## References:
1. [Group](../Introduction%20%to$Groups/Group.md)
2. [Proposition 2.1 (Subgroup Criterion)](Proposition%202.1%20(Subgroup%20Criterion).md)
3. [Centralizer of a Set](Centralizer%20of%20a%20Set.md)
4. [Subgroup](Subgroup.md)

