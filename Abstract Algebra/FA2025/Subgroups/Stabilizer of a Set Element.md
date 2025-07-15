> Def. (Stabilizer of a Set Element): Let $G$ act on a set $S$. Also let $s$ be some fixed element of $S$. Then the *stabilizer* of $s$ in $G$ is the set: $$G_{s} \coloneqq \{g \in G: g \cdot s = s\}.$$ $G_{S}$ is a subgroup of $G$. 

## Proof:
1. Since $1 \cdot s = s$, $1 \in G_{s}$, which means it is nonempty. 
2. Let $x, y \in G_{s}$, which means that $x \cdot s = s  = y \cdot s$. From the latter, $$y \cdot s = s \iff (y^{-1}y) \cdot s = y^{-1} \cdot s \iff 1 \cdot s = y^{-1} \cdot s \iff y^{-1}\cdot s = s.$$ Hence, $y^{-1} \in G_{s}$. Therefore, $$(xy^{-1}) \cdot s = x \cdot (y^{-1} \cdot s) = x \cdot s = s.$$ This shows that $xy^{-1} \in G_{s}$. 
Therefore, by Proposition 2.1 (The Subgroup Criterion), $G_{s}$ is a subgroup of $G$. 

## References: 
1. [Group](../Introduction%20to%Groups/Group.md)
2. [Subgroup](Subgroup.md)
3. [Group Action](../Introduction%20to%20Groups/Group%20Action.md)
4. [Proposition 2.1 (Subgroup Criterion)](Proposition%202.1%20(Subgroup%20Criterion).md)