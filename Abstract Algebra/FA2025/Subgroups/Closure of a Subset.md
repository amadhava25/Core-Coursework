> Def. (Set of Words of Elements of $A$): Let $G$ be a group and $A$ any subset of $G$. Define $$\bar{A} = \{a_{1}^{\epsilon_{1}}a_{2}^{\epsilon_{2}}\dotsm a_{n}^{\epsilon_{n}}: n \in \mathbb{Z}, n \geq 0, a_{i} \in A, \epsilon_{i} = \pm i \text{ for each $i$}\}.$$ Note that $\bar{A} = \{1\}$ if $A = \varnothing$. Then $\bar{A}$ is the set of all finite products (called *words*) of elements of $A$ and inverses of elements of $A$. 

## Properties:
1. $\bar{A}$ is a subgroup of $G$.  
	Proof: 
		1. If $A$ is empty, then $\bar{A} = \{1\}$. If $A$ is nonempty, then since $\bar{A}$ contains the set of all finite products of elements of $A$, $\bar{A}$ is nonempty. In any case, $\bar{A}$ is nonempty. 
		2. Let $x, y \in \bar{A}$, which means that $x = a_{1}^{\epsilon_{1}}a_{2}^{\epsilon_{2}} \dotsm a_{n}^{\epsilon_{n}}$ and $y = \bar{a}_{1}^{\bar{\epsilon}_{1}}\bar{a}_{2}^{\bar{\epsilon}_{2}}\dotsm \bar{a}_{m}^{\bar{\epsilon}_{m}}$ for some $n, m \in \mathbb{N}$. Then $$xy^{-1} = \prod_{i = 1}^{n}\prod_{j = 1}^{m}a_{i}^{\epsilon_{i}}\bar{a}_{j}^{\bar{\epsilon}_{j}},$$ which is still a finite product of elements of $A$. Therefore, $xy^{-1} \in \bar{A}$. 
	Therefore, by Proposition 2.1 (The Subgroup Criterion), $\bar{A}$ is a subgroup of $G$. 

## References: 
1. [Group](../Introduction%20to%20Groups/Group.md)
2. [Subgroup](Subgroup.md)
3. [Proposition 2.1 (Subgroup Criterion)](Proposition%202.1%20(Subgroup%20Criterion).md)
 