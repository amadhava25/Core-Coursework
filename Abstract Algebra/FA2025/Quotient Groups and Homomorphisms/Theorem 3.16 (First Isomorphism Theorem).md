> Thm. (First Isomorphism Theorem): If $\varphi: G \to H$ is a homomorphism of groups, then $\ker{\varphi} \unlhd G$ and $G / \ker{\varphi} \cong \varphi(G)$. 
> 

## Proof:
1. Let $g$ be any arbitrary element of $G$, and $h$ any arbitrary element of $\ker{\varphi}$. Then $$\varphi(ghg^{-1}) = \varphi(g)\varphi(h)\varphi(g^{-1}) = \varphi(g)\varphi(g)^{-1} = 1 \implies ghg^{-1} \in \ker{\varphi}.$$ Since this is true for any $g \in G, h \in \ker{\varphi}$, $g\ker{\varphi}g^{-1} \subseteq \ker{\varphi}$. Hence, by Theorem 3.6 (Equivalent Conditions for Normal Subgroups), $\ker{\varphi} \unlhd G$. 
2. This property is left as an exercise for future. 

## Reference: 
1. [Group](../Introduction%20to%20Groups/Group.md)
2. [Homomorphism](../Introduction%20to%20Groups/Homomorphism.md)
3. [Kernel of a Homomorphism](Kernel%20of%20a%20Homomorphism.md)
4. [Normal Subgroup](Normal%20Subgroup.md)
5. [Isomorphism](../Introduction%20to%20Groups/Isomorphism.md)
6. [Quotient Group (Factor Group)](Quotient%20Group%20(Factor%20Group).md)