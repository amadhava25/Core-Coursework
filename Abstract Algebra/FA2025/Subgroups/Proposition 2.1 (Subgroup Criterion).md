> Prop. (The Subgroup Criterion): A subset $H$ of a group $G$ is a subgroup if and only if 
> 	1. $H \neq \varnothing$, and 
> 	2. for all $x, y \in H$, $xy^{-1} \in H$. 
> Furthermore, if $H$ is finite, then it suffices to check that $H$ is nonempty and closed under multiplication. 


## Proof:
Statement 1:
($\implies$) Suppose $H \leq G$. By definition, $H$ is nonempty (so that (1) is satisfied), and is closed under inverses and multiplication (such that (2) is satisfied). 
($\Longleftarrow$) Suppose $H$ is a nonempty subset of $G$ satisfying (2). First, if $x \in H$, then $e = xx^{-1} \in H$. Therefore, $x^{-1} = ex^{-1} \in H$, showing closure under inverses. Finally, for any $x, y \in H$, since $y^{-1} \in H$ as well, $xy = x(y^{-1})^{-1} \in H$, showing closure under multiplication. Hence, $H \leq G$. 

Statement 2: 
Let $H$ be a nonempty, finite subset of $G$ that is closed under multiplication. Let $x$ be any element of $H$. Then there must be finitely many distinct elements among $x, x^{2}, x^{3}, \ldots$ such that $x^{a} = x^{b}$ for some $a, b \in \mathbb{Z}$, with $b > a$. Hence, $x^{b - a} = 1$. In particular, every element of $H$ has finite order. Moreover, $x^{b -a - 1} = x^{-1}$ is an element of $H$, so that $H$ is closed under inverses. 

## References:
1. [Group](../Introduction%20to%20Groups/Group.md)
2. [Subgroup](../Subgroups/Subgroup.md)