> Def. (Dihedral Group): Let $D_{2n}$ be the set of all symmetries of an $n$-gon. Then $D_{2n}$ is a group under the following operation: if $s, t$ effect the permutations $\sigma, \tau$, respectively, then we define $st$ to be the functional composition $\sigma \circ \tau$. 

## Properties:
1. The order of $D_{2n}$ is $2n$. 
		Proof: Consider an arbitrary $\sigma \in D_{2n}$; $\sigma$ can map the vertex $1$ to a total of $n$ locations. If $\sigma(1) = i$, then since $\sigma$ is a symmetry on the $n$-gon (and hence, represents a rigid motion), $\sigma(2) = i \pm 1$. Hence, if there are $n$ choices for where $1$ ends up, there are $2n$ choices for where $2$ ends up. And since the symmetries are rigid motions, specifying the new positions of two vertices under a permutation completely determines the permutation. Therefore, there are a total of $2n$ elements in $D_{2n} \implies |D_{2n}| = 2n$. 

## References: 
1. [Group](Group.md)
2. [Symmetry](Symmetry.md)