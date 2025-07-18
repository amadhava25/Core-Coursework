> Def. (Subgroup of $G$ Generated by $A$): Let $G$ be a group and $A$ any subset of $G$. Define $$\braket{A} = \bigcap_{\substack{A \subseteq H \\ H \leq G}}H.$$ Then this is a subgroup of $G$ containing $A$, and is called the *subgroup of $G$ generated by $A$*. 

## Proof:
Since each $H$ is a subgroup of $G$, by Proposition 2.8 (Intersection of Subgroups), $\braket{A}$ is a subgroup of $G$. And since each $H$ contains $A$, $\braket{A}$ contains $A$. 

## Properties:
1. $\braket{A}$ is the smallest subgroup of $G$ containing $A$. 
	Proof: Suppose $B$ is another subgroup of $G$ containing $A$. Then $B$ is one of the subgroups $H$ over which the intersection is taken. Therefore, $\braket{A} \subseteq B$, showing that $\braket{A}$ is the unique smallest subgroup of $G$ containing the subset $A$. 

## References:
1. [Group](../Introduction%20to%20Groups/Group.md)
2. [Subgroup](Subgroup.md)
3. [Proposition 2.8 (Intersection of Subgroups)](Proposition%202.8%20(Intersection%20of%20Subgroups).md)