> Def. (Centralizer of $A$): Let $G$ be an arbitrary group and $A$ be any nonempty subset of $G$. Define the set $$C_{G}(A) = \{g \in G: gag^{-1} = a  \text{ for all $a \in A$}\}.$$ Then $C_{G}(A)$ is called the centralizer of $A$ in $G$ and is a subgroup of $G$. 

## Proof:
1. Since $1 \cdot a = a=  a \cdot 1$ for all $a \in A$, it follows that $1 \in C_{G}(A)$, and hence $C_{G}(A)$ is nonempty. 
2. Suppose $g, h \in C_{G}(A)$. Then $$\begin{aligned}(gh^{-1})a(gh^{-1})^{-1} &= gh^{-1}ahg^{-1} \\\ &= g(a)g^{-1} = a, \end{aligned}$$ since $gag^{-1} = hah^{-1} = a$ for all $a \in A$. Therefore, $gh^{-1} \in C_{G}(A)$. 
By Proposition 2.1 (the Subgroup Criterion), it follows that $C_{G}(A)$ is a subgroup of $G$. 

## Examples:
1. 