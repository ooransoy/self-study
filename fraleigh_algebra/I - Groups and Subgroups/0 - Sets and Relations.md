**Exercise 15**

$f(x) = \log(\frac{1}{x}-1)$ is a bijection from $(0, 1)$ to $\mathbb{R}$, showing that they have the same cardinality. We know $f$ is a bijection because it is the composition of three other bijections ($\log(x)$, $\frac{1}{x}$, $x-1$).



**Exercise 16**

a.

	$\{\}$

	1

b.

	$\{\}$

	$\{a\}$

	2

c.

	$\{\}$

	$\{a\}$

	$\{b\}$

	$\{a, b\}$

	4

d.

	$\{\}$

	$\{a\}$

	$\{b\}$

	$\{a, b\}$

	$\{c\}$

	$\{a, c\}$

	$\{b, c\}$

	$\{a, b, c\}$

	8



**Exercise 17**

$|P(A)|=2^{|A|}$

We use induction. For the base case $A = \varnothing$, $P(A) = {\varnothing}$, and $|P(A)| = 1 = 2^{|A|} = 2^0$.

We assume inductively that for a set $A$ that $|P(A)|=2^{|A|}$. We will prove that for the set $B = A \cup \{x\}$, $|P(B)|=2^{|B|}$. 



Every subset of A is also a subset of B. From this, we have $|P(A)|$ subsets. For every subset S of A, $S \cup \{x\}$ is also a subset of B, giving us another $|P(A)|$ subsets. We know these two sets of subsets are mutually exclusive, because the first group of subsets do not contain x (since x is not in A) and the second group of subsets do contain x. These two groups combined give us at least $2|P(A)| = 2 \cdot 2^{|A|} = 2^{|A|+1} = 2^{|B|}$ distinct subsets of B.

Now we will show that every subset of B has to be in one of these two groups.

A subset S of B either contains or does not contain x. If S does not contain x, it falls into the first group, because every element of B is either x or an element of A. If no element of S is x, then every element of S must be an element of A, which means that S is a subset of A and falls into the first group.

If S does contain x, it falls into the second group, because we can write S as $S' \cup \{x\}$ where $S' = \{e\in S\ |\ e \neq x\}$ is a subset of A (Every element of S' is an element of S is an element of B which means it is either x or an element of A. Since no elements of S' are x then all elements of S' are elements of A, meaning S' is a subset of A).

We have shown that every subset of B is one of these $2^{|B|}$ subsets, closing the induction.



**Exercise 18**

We will prove that $B^A$ has the same cardinality as $P(A)$ by giving an injective function $\phi : B^A \mapsto P(A)$ and an injective function $\sigma : P(A) \mapsto B^A$.

We define $\phi(f) = \{e\in A\ |\ f(e) = 1\}$. We will now prove that $\phi$ is injective by contradiction. Assume that $\phi$ is not injective. This means that there exist distinct $f$ and $g$ in $B^A$ s.t. $\phi(f) = \phi(g)$. If $f \neq g$, then there has to exist an $x \in A$ s.t. $f(x)\neq g(x)$. WLOG assume that $f(x) = 0$ and $g(x) = 1$. This means that $x \notin \phi(f)$ and that $x \in \phi(g)$. This contradicts our previous statement that $\phi(f) = \phi(g)$.

We define $\sigma(s)(x) = [x \in s]$. We will now prove that $\sigma$ is injective by contradiction. Assume that $\sigma$ is not injective. This means that there exist distinct $s$ and $t$ in $P(A)$ s.t. $\sigma(s) = \sigma(t)$. If $s \neq t$, then WLOG there has to exist $x \in s$ s.t. $x \notin t$. This means that $\sigma(s)(x) = 1$ and $\sigma(t)(x) = 0$, which contradicts our previous statement that $\sigma(s) = \sigma(t)$.

We have now proved that $|P(A)| = B^A$.



**Exercise 19**

To show that $|P(A)| > A$, we will show that an injective function $\phi : A \mapsto P(A)$ cannot be surjective. By contradiction, assume that $\phi$ is surjective. Consider the subset $S = \{e \in A\ |\ e \notin \phi(e)\}$. If $\phi$ is surjective, this means that there exists $x \in A$ s.t. $\phi(x) = S$. If $x \in S$, this would mean $x \notin S$ (by the definition of $S$). If $x \notin S$, this would mean $x \in S$ by the definition of $S$. This means that our initial assumption that $\phi$ is surjective is a contradiction.



The set of everything $S$ is not a sound concept, because $P(S)$ is a set bigger than $S$. How could $S$ be the set of everything if there exists a bigger set?



**Exercise 20**

a.

	A and B are disjoint, so the cardinality of their union would be the sum of their cardinalities, i.e. $2+3=5$.

	i. $3+\aleph_0$

		$S = \{-3, -2, -1\}$ is a set of cardinality $3$, and $\mathbb{Z}^+$ is a set of cardinality $\aleph_0$. The function $f(x) = x-3$ is a bijection from $\mathbb{Z}^+$ to $S \cup \mathbb{Z}^+$, and since these two sets are disjoint this leads us to believe that $3+\aleph_0 = \aleph_0$.

	ii. $\aleph_0 + \aleph_0$

		$\mathbb{Z}^+$ and $\mathbb{Z}^-$ are disjoint sets of cardinality $\aleph_0$. $f(x) = (-1)^x\lceil\frac{x}{2}\rceil$ is a bijection from $\mathbb{Z}^+$ to $\mathbb{Z}^+ \cup \mathbb{Z}^-$, showing that the sets are of equal cardinality, which leads us to believe that $\aleph_0 + \aleph_0 = \aleph_0$.

		(or)

		$\mathbb{Z}^-$ and $\mathbb{N}$ are disjoint sets of cardinality $\aleph_0$. Their union is $\mathbb{Z}$, of the same cardinality, which leads us to believe that $\aleph_0 + \aleph_0 = \aleph_0$.



b.

	```

	#  3   4   5

	1 1,3 1,4 1,5

	2 2,3 2,4 2,5

	```

	```

	#  0  1  2  3  4

	0  0  1  8  9 24 ...

	1  3  2  7 10 23

	2  4  5  6 11 22

	3 15 14 13 12 21

	4 16 17 18 19 20

	```

	We can use a pattern like shown to get a bijection between $\mathbb{N} \times \mathbb{N}$ and $\mathbb{N}$, which leads us to believe that $\aleph_0 \cdot \aleph_0 = \aleph_0$.



**Exercise 21**

$10^2$. $10^5$. $\mathbb{R}$, $\mathbb{R}$, and $\mathbb{R}$.



**Exercise 22**

$\aleph_0$, $|\mathbb{R}|$, $|2^\mathbb{R}|$, $|2^{2^\mathbb{R}}|$, $|2^{2^{2^\mathbb{R}}}|$.



**Exercise 23-27**

1, 2, 5, 15, 52



**Exercise 28**

Reflexive: $\bar{x}$ = $\bar{x}$ is true by the reflexivity of equality

Transitive: $\bar{x}$ = $\bar{y}$ and $\bar{y}$ = $\bar{z}$ implies $\bar{x}$ = $\bar{z}$ by the transitivity of equality



**Exercise 29-34**

Yes: $\{\{-1, -2, -3, -4, ... \}, \{0\}, \{1, 2, 3, 4, ...\}\}$

No, symmetry is violated.

Yes: $\{\{0\}, \{1, -1\}, \{2, -2\}, \{3, -3\}, ...\}$

No, transitivity is violated.

Yes: $\{\text{numbers with 1 digit}, \text{with 2}, \text{with 3 }, ...\}$

Yes: $\{\text{numbers ending in 0}, \text{in 1}, \text{in 2}, ..., \text{in 9}\}$



**Exercise 35**

a.

	$\{1, 3, 5, 7, 9, ...\}$

	$\{2, 4, 6, 8, 10, ...\}$

b.

	$\{1, 4, 7, 10, 13, ...\}$

	$\{2, 5, 8, 11, 14, ...\}$

	$\{3, 6, 9, 12, 15, ...\}$

c.

	$\{1, 6, 11, 16, 21, ...\}$

	$\{2, 7, 12, 17, 22, ...\}$

	$\{3, 8, 13, 18, 23, ...\}$

	$\{4, 9, 14, 19, 24, ...\}$

	$\{5, 10, 15, 20, 25, ...\}$



**Exercise 36**

a.

	Symmetry: $x-y = nq$, $y-x = n(-q)$

	Reflexivity: $x-x = n \cdot 0$

	Transitivity: $x-y = nq$, $y-z = np$, $x-z = n(p+q)$

b.

	TODO later

c.

	a.

		$\{..., -4, -2, 0, 2, 4, ...\}$

		$\{..., -3, -1, 1, 3, 5, ...\}$

	b.

		$\{..., -6, -3, 0, 3, 6, ...\}$

		$\{..., -5, -2, 1, 4, 7, ...\}$

		$\{..., -4, -1, 2, 5, 8, ...\}$

	c.

		$\{..., -10, -5, 0, 5, 10, ...\}$

		$\{..., -9, -4, 1, 6, 11, ...\}$

		$\{..., -8, -3, 2, 7, 12, ...\}$

		$\{..., -7, -2, 3, 8, 13, ...\}$

		$\{..., -6, -1, 4, 9, 14, ...\}$



**Exercise 37**

If a function is not injective, that means that there are two inputs that lead to the same output, which could be seen as a _two to one_ relationship. By calling injective functions _two to two_, we imply in the name that any two distinct inputs lead to two distinct outputs.
