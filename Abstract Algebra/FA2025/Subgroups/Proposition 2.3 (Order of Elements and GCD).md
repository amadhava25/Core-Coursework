> Prop. (Order of an Element): Let $G$ be an arbitrary group, $x \in G$, and $m, n \in \mathbb{Z}$. If $x^{n} = 1$ and $x^{m} = 1$, then $x^{d} = 1$, where $d = (m, n)$. In particular, if $x^{m} = 1$ for some $m \in \mathbb{Z}$, then $|x|$ divides $m$. 

## Proof:
Assume all of the hypotheses of the problem, and let $d = (m, n)$. By the Bezout identity, there exist integers $u, v$ such that $d = mu + nv$. Therefore, $$x^{d} = x^{mu + nv} = (x^{m})^{u} \cdot (x^{n})^{v} = 1 \cdot 1 = 1$.$$ Now suppose $x^{m} = 1$, and denote $|x| = n$. By the division algorithm, $m = nq + r$, where $0 \leq r < n$. Rearranging, $r = m - nq$, which means that $$x^{r} = x^{m - nq} = x^{m} \cdot (x^{n})^{-q} = 1 \cdot 1 = 1.$$ If $r$ is nonzero, then since $r < n$, $|x| = r$, which contradicts our assumption that $|x| = n$. Therefore, $r = 0$, which means $m =nq \implies n \mid m$. 

## References: 
1. [Group](../Introduction%20$to%20Groups/Group.md)
2. [Order of an Element](../Introduction%20to%20Groups/Order%20of%20an%20Element.md)
