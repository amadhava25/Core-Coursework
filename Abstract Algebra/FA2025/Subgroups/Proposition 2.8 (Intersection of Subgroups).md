> Prop. (Intersection of Subgroups is a Subgroup): If $\mathcal{A}$ is any nonempty collection of subgroups of $G$, then the intersection of all members of $\mathcal{A}$ is also a subgroup of $G$. 

## Proof: 
Let $\mathcal{A} = \{A_{\alpha}\}_{\alpha \in A}$, where each $A_{\alpha} \leq G$, and $A$ is some index set. Also denote $\sf{A} = \bigcap_{\alpha \in A}A_{\alpha}$. 
1. Since $1 \in A_{\alpha}$, for every $\alpha$, $1 \in \sf{A}$; i.e., $\sf{A}$ is nonempty. 
2. Let $x, y \in \sf{A}$,which means $x, y \in A_{\alpha}$ for every $\alpha$. Since each $A_{\alpha}$ is a subgroup of $G$, $xy^{-1} \in A_{\alpha}$ for every $\alpha$, which means $xy^{-1} \in \sf{A}$. 

Therefore, by Proposition 2.1 (The Subgroup Criterion), $\sf{A}$ is a subgroup of $G$. 

## References:
1. [Group](../Introduction%to$Groups/Group.md)
2. [Subgroup](Subgroup.md)
3. [Proposition 2.1 (Subgroup Criterion)](Proposition%202.1%20(Subgroup%20Criterion).md)