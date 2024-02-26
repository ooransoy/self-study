# Section 8
(8.3) A **permutation of a set** is a bijective function from a set to itself. It can be considered a rearrangement of items.

Multiplication of permutations is composition.
$$(\sigma\tau)(x)=\sigma(\tau(x))$$
Permutations are read right-to-left in order of application.

(8.5) The set $S_A$ of all permutations of a set $A$ is a group under permutation multiplication.

(8.6) For some positive $n$ let $A = \{x\in\mathbb{Z}|1\leq x\leq n\}$. The group of all permutations of $A$ under permutation multiplication is called the **symmetric group on $n$ letters**, denoted by $S_n$.

![[Pasted image 20231012154250.png]]
![[Pasted image 20231012154239.png]]
# Section 9
For any permutation $\sigma$ on a set $A$, define an equivalence relation such that $a \sim b \iff \exists x\in \mathbb{Z}, b=\sigma^x(a)$.

()

# Section 10

# Section 11
**Theorem 11.2**
The direct product of groups is a group.

**Theorem 11.5**
$\mathbb{Z}_m \times \mathbb{Z}_n \cong \mathbb{Z}_{nm} \iff \gcd(n, m)=1$ 

**Corollary 11.6**
$\prod^{n}_{i=1}\mathbb{Z}_{m_i} \cong \mathbb{Z}_{m_1m_2\ldots m_n}$  iff all $m_i$ are pairwise coprime.

**Definition 11.8**
The **least common multiple** of positive integers $r_1\ldots r_n$ is the generator of the cyclic group of all common multiples of all $r_i$

**Theorem 11.9**
Consider an element in a direct product of groups where all components of the element are of finite order. The order of the element is equal to the least common multiple of the orders of the components.

**Theorem 11.12 (Fundamental Theorem of Finitely Generated Abelian Groups)**
Every finitely generated abelian group is uniquely isomorphic to a direct product (up to rearrangement) of a number of $\mathbb{Z}$ and a number of $\mathbb{Z}_{p_i^{r_i}}$ where $p_i$ are primes and $r_i$ are positive integers, neither of which necessarily distinct.
$$\prod_{i=1}^n\mathbb{Z}_{p_i^{r_i}} \ \times \ \prod_{i=1}^{m} \mathbb{Z}$$
($m$ here is the **Betti number** of $G$.)

**Definition 11.14**
A group is **decomposable** if it is isomorphic to a direct product of two nontrivial proper subgroups. Otherwise, it is **indecomposable**.

**Theorem 11.15**
The indecomposable finite abelian groups are precisely the cyclic groups with order a prime power.

**Theorem 11.16**
If $k$ divides the order of a finite abelian group, the group has a subgroup of order $k$.

**Theorem 11.17**
Every abelian group of order a squarefree positive integer is cyclic.

# Section 12

Read:
Artin \[5]
Gallian \[8]

An **isometry** is a mapping of $\mathbb{R}^n$ onto itself such for any pair of points, their distance is preserved.

**Theorem 12.5**
Every finite group of isometries of $\mathbb{R}^2$ is isomorphic to either some $\mathbb{Z}_n$ or some $D_n$.