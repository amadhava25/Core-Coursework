> Prop. (Order of Product of Subgroups): If $H$ and $K$ are finite subgroups of a group, then $$|HK| = \frac{|H||K|}{|H \cap K|}.$$ 

## Proof: 
First, note that this equation is well-defined. Since $H$ and $K$ are subgroups of $G$, $1 \in H \cap K$, which means that $|H \cap K|\geq 1$. Next, we note that $$HK = \bigcup_{h \in H}hK.$$ Since each coset of $K$ has $|K|$ elements, it suffices to find the number of *distinct* left cosets of $K$. We note that $$h_{1}K = h_{2}K \iff h_{2}^{-1}h_{1} \in K \iff h_{2}^{-1}h_{1} \in H \cap K \iff h_{1}(H \cap K) = h_{2}(H \cap K).$$ I.e., the number of distinct left cosets of $K$ is equal to the number of distinct left cosets of $H \cap K$, which is a subgroup of $H$. By Theorem 3.8 (Lagrange's Theorem), it then follows that $|H: H \cap K| = \frac{|H|}{|H \cap K|}$. Therefore, we find at last that $$|HK| = \frac{|H||K|}{|H \cap K|}.$$ 
## References:
1. [Group](../Introduction%20to%20Groups/Group.md)
2. [Subgroup](../Subgroups/Subgroup.md)
3. [Theorem 3.8 (Lagrange's Theorem)](Theorem%203.8%20(Lagrange's%20Theorem).md)
4. [Cosets of Groups](Cosets%20of%20Groups.md)
 