> Def: (Group): An ordered pair $(G, \star)$ where $G$ is a set and $\star: G \times G \to G$ is a binary operation on $G$ satisfying the following axioms: 
> 	1. For all $a, b, c \in G$, $(a \star b) \ast c = a \star (b \star c)$; 
> 	2. there exists an element $e \in G$ such that for all $a \in G$, $a \star e = a = e \star a$; 
> 	3. for each $a \in G$, there exists an element $a^{-1} \in G$ such that $a \star a^{-1} = e = a^{-1} \star a$. 

## Examples:
1. $\mathbb{Z}, \mathbb{Q}, \mathbb{R}, \mathbb{C}$ are all groups under addition. 
2. $\mathbb{R} \setminus \{0\}, \mathbb{Q} \setminus \{0\}, \mathbb{C}\setminus \{0\}$ are groups under multiplication. 
3. For $n \in \mathbb{N}$, $\mathbb{Z}/n\mathbb{Z}$ is an abelian (i.e., commutative) group under addition. 
4. If $(A, \star)$ and $(B, \diamond)$ are groups, then their *direct product* $A \times B$ defined as: $$A \times B = \{(a, b): a \in A, b \in B\}$$ with operation $(a_{1}, b_{1}) \cdot (a_{2}, b_{2}) = (a_{1} \star a_{2}, b_{1} \diamond b_{2})$ is a group. 