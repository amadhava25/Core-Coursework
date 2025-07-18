> Cor. (Order of an Element and the Group): If $G$ is a finite group and $x \in G$, then the order of $x$ divides the order of $G$. In particular, $x^{|G|} = 1$ for all $x \in G$. 

## Proof:
Let $x \in G$, and consider the subgroup $\braket{x} \leq G$ generated by $x$. By Theorem 3.8 (Lagrange's Theorem), $|\braket{x}| \mid |G|$. Since $|\braket{x}| = |x|$, $|x| \mid |G|$. In particular, if $|G| = k|x|$, then $$x^{|G|} = (x^{|x|})^{k} = 1^{k} = 1.$$

## References:
1. [Group](../Introduction%20to%20Groups/Group.md)
2. [Order of an Element](../Introduction%20to%Groups/Order%20of%20an%20Element.md)
3. [Subgroup](../Subgroups/Subgroup.md)
4. [Subgroup Generated by A](../Subgroups/Subgroup%20Generated%20by%20A.md)
5. [Theorem 3.8 (Lagrange's Theorem)](Theorem%203.8%20(Lagrange's%20Theorem).md)