> Prop. (Uniqueness of Identities and Inverses): If $G$ is a group under the operation $\star$, then 
> 	1. the identity of $G$ is unique; 
> 	2. for each $a \in G$, $a^{-1}$ is uniquely determined; 
> 	3. $(a^{-1})^{-1} = a$ for all $a \in G$; 
> 	4. $(a \star b)^{-1} = b^{-1} \star a^{-1}$; 
> 	5. for any $a_{1}, a_{2}, \ldots, a_{n} \in G$, the value of $a_{1} \star a_{2} \star \dotsm \star a_{n}$ is independent of how the expression is bracketed (this is called the *generalized associative law*). 

## Proof: 
1. Suppose $G$ contains two identity elements $e$ and $e'$. Then $$e = e\star e' = e'.$$ Therefore, the identity of $G$ is unique. 
2. Suppose for some $a \in G$, there exist two elements $b, c \in G$ such that $a \star b = b \star a = a \star c = c \star a = e$. Then $$\begin{aligned}b &= b \star e \\ &= b \star (a \star c) \\ &= (b \star a) \star c \\ &= e \star c  = c.\end{aligned}$$ Therefore, the inverse of $a$ is unique, and we can label this inverse as $a^{-1}$. 
3. Likewise, we know that $a^{-1}$ is the inverse of $a$. Therefore, $a$ is the inverse of $a^{-1}$, which means $a = (a^{-1})^{-1}$. 
4. Again, $(a \star b)^{-1}$ is the inverse of $a \star b$. On the other hand, $$\begin{aligned}(b^{-1} \star a^{-1}) \star (a \star b) &= b^{-1} \star (a^{-1} \star a) \star b \\ &= b^{-1} \star b = e. \\ (a \star b) \star (b^{-1} \star a^{-1}) &= a \star (b \star b^{-1}) \star a^{-1} \\ &= a \star a^{-1} = e. \end{aligned}$$ By definition, $(b^{-1} \star a^{-1})$ is the inverse of $a \star b$. Therefore, by uniqueness of inverses, $(a \star b)^{-1} = b^{-1} \star a^{-1}.$ 
5. This proof follows by induction on the number $n$ of elements in the operation. 

## References:
1. [Group](Group.md)