> Thm. (Isomorphisms between Cyclic Groups): Any two cyclic groups of the same order are isomorphic. More specifically, 
> 	1. if $n \in \mathbb{Z}^{+}$ and $\braket{x}, \braket{y}$ are both cyclic groups of order $n$, then the map $$\begin{aligned}\varphi: &\braket{x} \to \braket{y} \\ &x^{k} \mapsto y^{k}\end{aligned}$$ is well-defined and an isomorphism; 
> 	2. if $\braket{x}$ is an infinite cyclic group, the map $$\begin{aligned}\varphi: &\mathbb{Z}\to \braket{x} \\ &k \mapsto x^{k}\end{aligned}$$ is well-defined and an isomorphism. 

## Proof: 
1. First, we must show that $\varphi$ is well-defined. Suppose $x^{r} = x^{s}$, which means $x^{r - s} = 1$. By Proposition 2.3 (Order of Elements and GCD), $n \mid (r - s)$. I.e., $r = tn + s$, for some $t$. Then $$\begin{aligned}\varphi(x^{r}) &= \varphi(x^{tn + s}) \\ &= y^{tn + s} = y^{tn} \cdot y^{s} = y^{s} \\ &= \varphi(x^{s}). \end{aligned}$$ Now, we show that $\varphi$ is an isomorphism. First, $$\varphi(x^{a} \cdot x^{b}) = \varphi(x^{a + b}) = y^{a + b} = y^{a} \cdot y^{b} = \varphi(x^{a}) \cdot \varphi(x^{b}),$$ which means $\varphi$ is a homomorphism. For any power $y^{k} \in \braket{y}$, it is clear that $x^{k} \mapsto y^{k}$, proving surjectivity. Finally, if $\varphi(x^{r}) = \varphi(x^{s})$, then $y^{r - s} = 1$, which means $n \mid (r - s)$. Therefore, if $r = tn + s$, then $x^{r} = x^{tn + s} = (x^{n})^{t} \cdot x^{s} = x^{s}$, proving injectivity. Hence, $\varphi: \braket{x} \to \braket{y}$ is an isomorphism of groups. 
2. Again, we show that $\varphi$ is well-defined. Suppose $k = l \in \mathbb{Z}$. Then $$\varphi(k) = x^{k} = x^{l} =\varphi(l).$$ Now we show that $\varphi$ is an isomorphism. First, $$\varphi(k + l) = x^{k + l} = x^{k} \cdot x^{l} = \varphi(k) \cdot \varphi(l),$$ which means $\varphi$ is a homomorphism. Finally, if $\varphi(k)  = \varphi(l)$, then $x^{k} = x^{l} \implies x^{k - l} =1$. Since $|x| = \infty$, $k - l$ must be equal to zero (since otherwise, the order of $x$ would be at most $k - l$, which is finite), which means that $k = l$. 
## References:
1. [Group](../Introduction%20%to%20Groups/Group.md)
2. [Cyclic Group](Cyclic%20Group.md)
3. [Homomorphism](../Introduction%20to%20Groups/Homomorphism.md)
4. [Isomorphism](../Introduction%20to%20Groups/Isomorphism.md)
5. [Proposition 2.3 (Order of Elements and GCD)](Proposition%202.3%20(Order%20of%20Elements%20and%20GCD).md)