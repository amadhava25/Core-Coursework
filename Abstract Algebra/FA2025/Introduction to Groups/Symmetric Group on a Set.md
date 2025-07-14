> Def. (Symmetric Group on the Set $\Omega$): Let $\Omega$ be any nonempty set and $S_{\Omega}$ the set of all bijections from $\Omega$ to itself (i.e., the set of *all* permutations of $\Omega$). The set $S_{\Omega}$ is a group under function composition $\circ$, called the *symmetric group on the set $\Omega$*. 

## Proof:
1. Let $\sigma, \tau \in S_{\Omega}$. From analysis, the composition of bijections is a bijection. Therefore, $\sigma \circ \tau, \tau \circ \sigma \in S_{\Omega}$, showing closure under the operation; 
2. The identity element $\iota: x \mapsto x$ is clearly a bijection;
3. Since each $\sigma \in S_{\Omega}$ is a bijection, the inverse element $\sigma^{-1}$ is well-defined such that $\sigma \circ \sigma^{-1} = \iota = \sigma^{-1} \circ \sigma$. 

Therefore, $S_{\Omega}$ is a group under function composition. 

## Examples:
1. If $\Omega = \{1, 2, \ldots, n\}$, the symmetric group $S_{\Omega}$ is denoted $S_{n}$, and is called the *symmetric group of degree $n$* 
## Properties:
1. $|S_{n}| = n!$. 
		Proof: There are $n$ choices for where we can map $1$  to, $n - 1$ choices where we can map 2 to, ..., and 1 choice for where we can map $n$ to. Therefore, there are a total of $\prod_{i = 1}^{n}i = n!$ permutations on $\{1, \ldots, n\}$, which means $|S_{n}| = n!$. 

## References:
1. [Group](Group.md)