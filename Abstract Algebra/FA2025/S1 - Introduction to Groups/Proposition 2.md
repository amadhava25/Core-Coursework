> Prop. (Cancellation Law): Let $G$ be a group and $a, b \in G$. The equations $ax = b$ and $ya = b$ have unique solutions for $x, y \in G$. In particular, the left and right cancellation laws hold in $G$; i.e., 
> 	1. if $au = av$, then $u = v$; 
> 	2. if $ub = vb$, then $u = v$. 

## Proof:
1. Suppose $au = av$. Then $u = a^{1}(au) = a^{-1}(av) = (a^{-1}a)v = ev = v$. 
2. Likewise, if $ub = vb$, then $u = (ub)b^{-1} = (vb)b^{-1} = v(bb^{-1}) = ve = v$. 
3. Existence is guaranteed by taking $x = a^{-1}b \in G$. Suppose $ax = b$ and $ax' = b$. Then $ax = ax'$. By Property (1), $x = x'$, showing uniqueness. 
4. Existence is guaranteed by taking $y= ba^{-1} \in G$. Suppose $ya = b= y'a \iff ya = y'a$. Then by Property (2), $y = y'$, showing uniqueness. 

## References:
1. [Group](Group.md)