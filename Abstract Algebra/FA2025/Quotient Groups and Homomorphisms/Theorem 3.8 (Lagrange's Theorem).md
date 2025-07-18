> Thm. (Lagrange's Theorem): If $G$ is a finite group and $H$ is a subgroup of $G$, then the order of $H$ divides the order of $G$ (i.e., $|H| \mid |G|$) and the number of left cosets of $H$ in $G$ equals $\frac{|G|}{|H|}$.

## Proof:
To prove this statement, we begin by proving a lemma:
> Lem. (Order of Coset equals Order of Subgroup): Let $H \leq G$. Then for any $g \in G$, $|gH| = |H|$. 

Proof:
Define the map $\varphi_{g}: H \to gH$ by $\varphi_{g}(h) = gh$. It is clear to see that $\varphi_{g}$ is a surjection. Now suppose $\varphi_{g}(h) = \varphi_{g}(h') \iff gh = gh' \iff h = h'$, showing injectivity. Therefore, $\varphi_{g}$ is a bijection, which means that $|H| = |gH|$ for all $g \in G$. 

Now, let $G$ be a finite group, $H \leq G$. Let $m$ denote the number of distinct left cosets of $H$ in $G$. By Proposition 3.4 (Partition of Groups by Left Cosets), $$G = \bigcup_{g \in G}|gH|.$$ If $\{g_{i}H\}_{i = 1}^{m}$ are the distinct left cosets of $H$, then $$G = \bigcup_{i = 1}^{m}g_{i}H \implies |G| = \sum_{i = 1}^{m}|g_{i}H| = m|H| \implies |H| \mid |G|.$$ Likewise, the number of distinct left cosets of $H$ in $G$ is $m = |G|/|H|$. 

## References:
1. [Group](../Introduction%20to%20Groups/Group.md)
2. [Subgroup](../Subgroups/Subgroup.md)
3. [Cosets of Groups](Cosets%20of%20Groups.md)
4. [Proposition 3.4 (Partition of Groups by Left Cosets)](Proposition%203.4%20(Partition%20of%20Groups%20by%20Left%20Cosets).md)
