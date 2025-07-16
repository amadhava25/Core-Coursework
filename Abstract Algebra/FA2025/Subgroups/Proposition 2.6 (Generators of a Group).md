> Prop. (Generators of a Group): Let $H = \braket{x}$. Then 
> 	1. if $|x| = \infty$, then $H = \braket{x^{a}}$ iff $a = \pm 1$; 
> 	2. if $|x| = n < \infty$, then $H = \braket{x^{a}}$ iff $(a, n) = 1$. In particular, the number of generators of $H$ is $\varphi(n)$, where $\varphi$ is Euler's totient $\varphi$-function. 

## Proof: 
1. Let $|x|= \infty$. 
	($\implies$) Suppose $H =\braket{x^{a}}$. Since $H = \braket{x}$, $x \in H$, which means there must be some integer power $k$ of $x^{a}$ such that $x^{ak}= x \iff ak - 1= 0 \iff ak = 1$. Since $a, k$ are both integers, there are only two cases: (1) either $a, k = 1$ or $a, k = -1$. Therefore, $a = \pm 1$. 
	($\Longleftarrow$) If $a = 1$, then we're done. Otherwise, suppose $a =-1$. Let $x^{t} \in \braket{x} = H$ for some $t \in \mathbb{Z}$. Then since $x^{t} = (x^{-1})^{-t}$, where $-t \in \mathbb{Z}$, $x^{t} \in \braket{x^{-1}}$. Therefore, $\braket{x} \subseteq \braket{x^{-1}}$. On the other hand, if $x^{-a} \in \braket{x^{-1}}$ for some $a \in \mathbb{Z}$, then since $-a \in \mathbb{Z}$, $x^{-a} \in \braket{x}$, which shows that $\braket{x^{-1}} \subseteq \braket{x}$. Therefore, $H = \braket{x^{a}}$
2. By Proposition 2.2, $|x^{a}|$ generates a subgroup of $H$ of order $|x^{a}|$; by Proposition 2.5, the order of this subgroup is $n/(n, a)$. Therefore, $\braket{x^{a}} = \braket{x} = H$ iff $n/(n, a)= n \iff (n, a)= 1$. And since $\varphi(n)$, by definition, is the number of $a \in \{1, \ldots, n\}$ such that $(a, n) = 1$, $H$ has $\varphi(n)$ generators. 

## Examples:
1. This proposition enables us to exactly deduce the generators of a group. For example, in $\mathbb{Z}/12\mathbb{Z}$, the generators are those residue classes $\bar{a}$ such that $(a, 12) = 1$; i.e., the generators are $\bar{1}, \bar{5}, \bar{7}, \bar{11}$. We check that $\varphi(n) = 4$. 

## References: 
1. [Group](../Introduction%to%Groups/Group.md)
2. [Cyclic Group](Cyclic%20Group.md)
3. [Proposition 2.2 (Order of Cyclic Groups)](Proposition%202.2%20(Order%20of%20Cyclic%20Groups).md)
4. [Subgroup](Subgroup.md)
5. [Proposition 2.5 (Orders of x and Its Powers)](Proposition%202.5%20(Orders%20of%20x%20and%20Its%20Powers).md)