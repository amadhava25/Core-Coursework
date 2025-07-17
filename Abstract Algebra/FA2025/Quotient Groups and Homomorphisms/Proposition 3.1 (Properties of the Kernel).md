> Prop. (Properties of the Kernel): Let $G$ and $H$ be groups, and $\varphi: G \to H$ be a group homomorphism. Then the following results hold:
> 	1. $\varphi(1_{G}) = 1_{H}$; 
> 	2. $\varphi(g^{-1}) = \varphi(g)^{-1}$; 
> 	3. $\varphi(g^{n}) = \varphi(g)^{n}$ for all $n \in \mathbb{Z}$;
> 	4. $\ker{\varphi}$ is a subgroup of $G$; 
> 	5. $\operatorname{im}{\varphi}$ is a subgroup of $H$. 

## Proof:
1. First, we have $$\varphi(1_{G}) \cdot 1_{H} = \varphi(1_{G}) = \varphi(1_{G} \cdot 1_{G}) = \varphi(1_{G}) \cdot \varphi(1_{G}).$$ From the cancellation law, $\varphi(1_{G}) = 1_{H}$. 
2. Next, we have $$\varphi(g^{-1}) \cdot \varphi(g) = \varphi(g^{-1}g) = \varphi(1) = 1.$$ Therefore, by uniqueness of the identity, $\varphi(g^{-1}) = \varphi(g)^{-1}$. 
3. The case is clear if $n = 0$. If $n > 0$, then proceed as follows:
	1. $\varphi(g^{1}) = \varphi(g^{1})$ so that $n = 1$ is a base case. 
	2. Suppose the result holds for some $n \in \mathbb{N}$. 
	3. Then $$\varphi(g^{n + 1}) = \varphi(g^{n}) \cdot \varphi(g) = g^{n} \cdot g = g^{n + 1}.$$ Therefore, the result holds by induction. 
	If $n < 0$, the proof follows analagously. 
4. Since $\varphi(1) = 1$, $1 \in \ker{\varphi}$ such that it is nonempty. Now let $x, y \in \ker{\varphi}$. Then $$\varphi(xy^{-1}) = \varphi(x) \cdot \varphi(y)^{-1} = 1 \cdot 1 = 1.$$ Therefore, $xy^{-1} \in \ker{\varphi}$. By Proposition 2.1 (the Subgroup Criterion), $\ker{\varphi}$ is a subgroup of $G$. 
5. Since $\varphi(1) = 1$, $1 \in \operatorname{im}{\varphi}$, such that it is nonempty. Now let $x, y \in \operatorname{im}{\varphi}$; i.e., suppose there exist $g_{1}, g_{2} \in G$ such that $\varphi(g_{1}) = x$ and $\varphi(g_{2}) = y$. Then $xy^{-1} = \varphi(g_{1}g_{2}^{-1}) \in \operatorname{im}{\varphi}$ since $g_{1}, g_{2}^{-1} \in G$. Therefore, by Proposition 2.1 (the Subgroup Criterion), $\operatorname{img}{\varphi} \leq H$. 

## References: 
1. [Group](../Introduction%20to%20/Groups/Group.md)
2. [Homomorphism](../Introduction%to%20Groups/Homomorphism.md)
3. [Subgroup](../Sugroups/Subgroup.md)
4. [Kernel of a Homomorphism](Kernel%20of%20a%20Homomorphism.md)