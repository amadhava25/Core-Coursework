> Prop: (Orders of $x$ and Powers of $x$): Let $G$ be a group, $x \in G$, and $a \in \mathbb{Z} \setminus \{0\}$. Then,
> 	1. if $|x| = \infty$, then $|x^{a}| = \infty$;
> 	2. if $|x| = n < \infty$, then $|x^{a}| = \frac{n}{(n, a)}$; 
> 	3. in particular, if $|x| = n < \infty$ and $a$ is a positive integer dividing $n$, then $|x^{a}| = \frac{n}{a}$. 

## Proof:
1. Suppose $|x| = \infty$, but assume to the contrary that $|x^{a}| < \infty$; i.e., suppose $|x^{a}| = n$. Then by definition, $(x^{a})^{n} = 1 \iff x^{an} = 1$, which contradicts our assumption that there exists no positive integer $z$ such that $x^{z} = 1$. Therefore, by contradiction, $|x^{a}| = \infty$. 
2. Let $d = (n, a)$ and let $n = db, a = dc$, where $b, c \in \mathbb{Z}$, and $b > 0$. Since $d$ is the greatest common divisor of $n$ and $a$, $b$ and $c$ must be relatively prime: $(b, c) = 1$. Now note that $$x^{ab} = x^{dcb} = (x^{n})^{c} = 1.$$ Therefore, by Proposition 2.3 (Order of Elements and GCDs), $|x^{a}| \mid b$. Let $m = |x^{a}|$. Then $$x^{ak} = 1,$$ such that by Proposition 2.3, $n \mid ak \implies db \mid dck$. Since $(b, c) = 1$, it follows that $b \mid k$. Since $b$ and $k$ are positive integers that divide each other, $b = k$. Hence, the proof is complete. 
3. If $a \mid n$, then $(n, a) = a$. Hence, by (2), the proof concludes. 

## References: 
1. [Group](../Introduction%20to%20Groups/Group.md)
2. [Order of an Element](../Introduction%to%Groups/Order%20of%20an%20Element.md)
3. [Proposition 2.3 (Order of Elements and GCD)](Proposition%202.3%20(Order%20of%20Elements%20and%20GCD).md)