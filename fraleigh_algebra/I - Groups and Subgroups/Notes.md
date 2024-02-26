# Section 0



A **set** is a collection of objects.



$e \in S$ means the object $e$ is a member of a set $S$.

There is exactly one set with no elements: the **empty set**, denoted by $\varnothing$.

$\{x \in S| P(x)\}$ is the set of elements in $S$ that satisfy the property $P$.

$\{x| P(x)\}$ is the set of elements that satisfy the property $P$.



A set $B$ is a **subset** of set $A$ (denoted by $B \subseteq A$ or $A \supseteq B$) if every element of $B$ is an element of $A$.



If $A$ is any set, $A$ is the **improper subset** of $A$. Any other subset is a **proper subset**.



Let $A$ and $B$ be sets. The **Cartesian product** of $A$ and $B$ is $\{(a, b) | a \in A \wedge b \in B\}$, denoted by $A \times B$.



---



$\mathbb{Z}$ is the set of all integers.

$\mathbb{Q}$ is the set of all rational numbers.

$\mathbb{R}$ is the set of all real numbers.



$\mathbb{Z}^+$ is the set of all positive integers.

$\mathbb{Q}^+$ is the set of all positive rational numbers.

$\mathbb{R}^+$ is the set of all positive real numbers.



$\mathbb{C}$ is the set of all complex numbers.



$\mathbb{Z}^*$ is the set of all nonzero integers.

$\mathbb{Q}^*$ is the set of all nonzero rational numbers.

$\mathbb{R}^*$ is the set of all nonzero real numbers.

$\mathbb{C}^*$ is the set of all nonzero complex numbers.



---



A **relation** between sets $A$ and $B$ is a subset $\star$ of $A \times B$. We say that $a$ is related to $b$ if $(a, b) \in \star$, denoted by $a\star b$.



The **equality relation** on $S$ is a relation $=$ between $S$ and $S$ such that $=$ is $\{(x, x) | x \in S\}$.



We will refer to relations between $S$ and $S$ as a **relation on** $S$.



A **function** $\phi$ mapping $A$ to $B$ is a relation between $A$ and $B$ where every element of $A$ appears as the first element of exactly one pair in $\phi$. We write $\phi : A \to B$ and denote $(x, y) \in \phi$ as $\phi(x)=y$.

The **domain** of $\phi$ is $A$

The **codomain** of $\phi$ is $B$

The **range** of $\phi$, denoted $\phi[A]$, is $\{\phi(a)|a \in A\}$.



---



The number of elements in $S$ is called the **cardinality** of $S$, denoted by $|S|$.



A function $\phi : X \to Y$ is

- **one to one** or **injective** if $\phi(a)=\phi(b) \implies a=b$ for all $a, b \in X$.

- **onto** or **surjective** if the range and the codomain of $\phi$ are the same.

- **bijective** if it is both surjective and injective.



Let $\phi : X \to Y$ be some bijection. The **inverse function** of $\phi$, denoted by $\phi^{-1}$, is a function mapping $Y$ to $X$ such that $\phi^{-1}(y)=x \iff \phi(x)=y$ for any $x\in X$ and $y\in Y$.



Two sets have the same cardinality if there is a bijection between them.



---



Two sets are **disjoint** if they have no common elements.



A **partition** of a set $S$ is a collection of nonempty subsets of $S$ such that each element of $S$ appears in exactly one subset. The subsets are the **cells** of the partition.



An **equivalence relation** $\star$ on a set $S$ is a relation such that

1. (Reflexivity) $a\star a$

2. (Symmetry) $a \star b \implies b \star a$

3. (Transitivity) $a\star b \wedge b\star c \implies a\star c$

for all $a, b, c \in S$.



For a set $S$ and an equivalence relation $\sim$, there is a partition of $S$ such that $\bar{a} = \{x \in S | x \sim a\}$.

For a set $S$ and a partition on $S$, there is an equivalence relation $\sim$ on $S$ such that $a \sim b$ iff $a$ and $b$ are in the same cell.



# Section 1



# Section 2



A **binary operation** $*$ on $S$ is a mapping from $S\times S$ to $S$. We denote $*((a, b))$ as $a*b$.



A subset $H$ of $S$ is **closed under** $*$ if $a*b\in H$ for all $a, b \in H$. The binary operation created by restricting $*$ to $H$ is called the **induced operation** of $*$ on $H$.



A binary operation is **commutative** if $a*b=b*a$ for all $a, b \in S$.



A binary operation is **associative** if $(a*b)*c=a*(b*c)$ for all $a, b, c \in S$.



# Section 3



Let $\langle S, *\rangle$ and $\langle S', *'\rangle$ be binary algebraic structures. An **isomorphism** of $S$ with $S'$ is a bijection $\phi : S \to S'$ such that $$\phi(x*y)=\phi(x)*'\phi(y)$$(homomorphism property) for all $x, y\in S$. If such isomorphism exists, we call $S$ and $S'$ **isomorphic**, denoted $S\simeq S'$. If $\phi$ is not injective, then it is a **homomorphism**.



Let $\langle S,*\rangle$ be a binary structure. An element $e$ of $S$ is called the **identity element** if $x*e=e*x=x$ for all $x\in S$.



The identity element is unique.



Let $\langle S, *\rangle$ and $\langle S', *'\rangle$ be binary algebraic structures, with an isomorphism $\phi$ between them. If $e$ is the identity element of $S$, then $\phi(e)$ is the identity element of $S'$.



# Section 4



A **group** $\langle G, *\rangle$ is a set $G$ closed under $*$ such that

1. The group is associative`

2. The group has an identity element $e$

3. For every element $x\in G$, $x$ has an **inverse element** $x'$ such that $x*x'=x'*x=e$.



A group is **abelian** if its operation is commutative.



The **left cancellation law** for a group: $a*b=a*c\implies b=c$

The **right cancellation law** for a group: $b*a=c*a\implies b=c$

for all $a, b, c\in G$



For a group, for all $a, b \in G$ there exist $x, y\in G$ such that $a*x=b$ and $y*a=b$.



For a group, the inverse of $a$ is unique for all $a\in G$.

For a group, its identity element is unique.



For a group and $a, b\in G$, $(a*b)'=b'*a'$



# Section 5



For a group $G$, the **order** $|G|$ of $G$ is the number of elements it contains.



If a subset $H$ of a group $G$ is closed under $*$ and $H$ forms a group with the induced operation $*$ in $H$ is also a group, $H$ is called a **subgroup** of $G$.



The **improper subgroup** of $G$ is $G$. All other subgroups are **proper subgroups**. $\{e\}$ is the **trivial subgroup**. All other subgroups are **nontrivial subgroups**.



A subset $H$ of a group $G$ is a subgroup iff

1. $H$ is closed under $*$

2. $e$ is in $H$

3. $a\in H \implies a' \in H$



For a group $G$ and an $a \in G$, the smallest subgroup of $G$ containing $a$ is $\{a^n | n \in \mathbb{Z}\}$. This is called the **cyclic subgroup of $G$ generated by $a$**, denoted by $\langle a\rangle$.



A **generator** of $G$ is a $g\in G$ such that $\langle g\rangle = G$. $g$ **generates** $G$.



# Section 6



Every cyclic group is abelian.



For all $m \in \mathbb{Z}^+$ and $n\in \mathbb{Z}$, there exist unique $q, r \in \mathbb{Z}$ such that

$$n=mq+r \quad\wedge\quad 0\leq r<m$$



A subgroup of a cyclic group is cyclic.



The subgroups of $\mathbb{Z}$ under $+$ are exactly the groups $n\mathbb{Z}$ under $+$.



Let $r,s\in\mathbb{Z}$. The positive generator $d$ of the cyclic group $\{nr+ms|n,m\in \mathbb{Z}\}$ is the **greatest common divisor (gcd)** of $r$ and $s$.



Let $G$ be a cyclic group, generated by $g$. If $G$ is infinite it is isomorphic to $\langle\mathbb{Z},+\rangle$. If it has finite order $n$, it is isomorphic to $\langle\mathbb{Z}_n,+_n\rangle$.



Let $G$ be a finite cyclic group generated by $a$. Let $b\in G, b=a^s$. The cyclic subgroup of $G$ generated by $b$ has order $\frac{n}{\gcd(n, s)}$.

Also, $\langle a^s\rangle = \langle a^t\rangle$ iff $\gcd(s, n) = \gcd(t, n)$



If $a$ is a generator for a finite cyclic group $G$ of order $n$, then the other generators of $G$ are $a^r$ where $r$ is relatively prime to $n$.



# Section 7



intersection $\bigcap$



The intersection of some subgroups of a group is still a subgroup



Generating sets

are obvious smh



The elements of a group generated by a set are precisely the finite products of integral powers of the elements of the set
