> Prop. (Fibers of a Homomorphism): Let $\varphi: G \to H$ be a group homomorphism with kernel $K$. Let $X = G/K$ be the fiber over $a$; i.e., $X = \varphi^{-1}(a)$.  Then:
> 	1. for any $u \in X$, $X = \{uk: k \in K\};$ 
> 	2. for any $u \in X$, $X = \{ku: k \in K\}$. 

## Proof:
1. Fix some arbitrary element $u \in X$. Let $u\bar{k} \in \{uk: k \in K\}$, where $\bar{k} \in K$. Then $\varphi(u\bar{k}) = \varphi(u)\cdot \varphi(\bar{k}) = \varphi(u) = a$. Therefore, $u\bar{k} \in X$, which shows that $\{uk: k \in K\} \subseteq X$. On the other hand, since $1 \in K$ and $u = u(1)$, $u \in \{uk: k \in K\}$. Therefore, $X = \{uk: k \in K\}$. 
2. The proof of this follows identically to the proof of (1). 

## References:
1. [Group](../Introduction%20to%20Groups/Group.md)
2. [Homomorphism](../Introduction%20to%20Groups/Homomorphism.md)
3. [Kernel of a Homomorphism](Kernel%20of%20a%20Homomorphism.md)
4. [Fibers of Homomorphisms](Fibers%20of%20Homomorphisms.md)