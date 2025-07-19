> Cor. (Corollary to First Isomorphism Theorem): Let $\varphi: G \to H$ be a homomorphism of groups. 
> 	1. $\varphi$ is injective if and only if $\ker{\varphi} = 1$; 
> 	2. $|G: \ker{\varphi}| = |\varphi(G)|$. 

## Proof:
1. ($\implies$) Suppose $\varphi$ is injective. Assume to the contrary that $\ker{\varphi} \neq 1$. I.e., suppose there exists some non-identity element $x \in \ker{\varphi}$. Then $\varphi(1) = \varphi(x)$, but $x \neq 1$, which contradicts our assumption of injectivity. Therefore, by contradiction, $\ker{\varphi} = \{1\}$.
   ($\Longleftarrow$) Now suppose $\ker{\varphi} = 1$, and suppose $\varphi(g) = \varphi(h)$ for some $g, h \in G$. Then $$\varphi(g) = \varphi(h) \iff \varphi(g)\varphi(h)^{-1} = 1 \iff \varphi(gh^{-1}) =1 \iff gh^{-1} = 1 \iff g = h.$$ Hence, $\varphi$ is injective. 
2. Exercise

## References: 
1. [Group](../Introduction%20to%20Groups/Group.md)
2. [Homomorphism](../Introduction%20to%20Groups/Homomorphism.md)
3. [Kernel of a Homomorphism](Kernel%20of%20a%20Homomorphism.md)
4. [Index of a Subgroup](Index%20of%20a%20Subgroup.md)
