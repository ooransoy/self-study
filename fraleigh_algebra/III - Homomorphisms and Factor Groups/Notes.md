# Section 13
**Definition 13.1**
A map of a group into another group is called a **homomorphism** when
$$\phi(ab)=\phi(a)\phi(b)$$

**Definition 13.11**
For a mapping $\phi : X \to Y$,
$\phi[A]$ is the **image** of $A$, $\{\phi(a)\ |\ a \in A\}$
$\phi[X]$ is the **range** of $A$
$\phi^{-1}[A]$ is the **inverse image** of $A$, $\{x\ |\ x\in X, \phi(x)\in A\}$

**Definition 13.12**
Homomorphisms preserve identity, inverses, and subgroups (The image of a subgroup and the inverse image of a subgroup are both subgroups).

**Definition 13.13**
The subgroup $\phi^{-1}[\{e'\}]$ (all elements sent to the identity by $\phi$) is the **kernel** of $\phi$, $\mathrm{Ker}(\phi)$.

**Theorem 13.15**
$\phi^{-1}[\{\phi(a)\}]$ is the left and the right coset of $\mathrm{Ker}(\phi)$ containing $a$.

**Corollary 13.18**
A homomorphism is injective iff its kernel is $\{e'\}$

**Definition 13.19**
A subgroup is called normal if its left cosets and right cosets are the same.

**Corollary 13.20**
The kernel of a homomorphism is normal.

# Section 14
**Theorem 14.1**
Let $H$ be the kernel of a homomorphism from $G$. The cosets of $H$ form a group $G/H$, named the **factor group**, s.t. $(aH)(bH)=(ab)H$. $\mu(aH)=\phi(a)$ is an isomorphism from $G/H$ to $\phi(G)$.

$(xh_1)(yh_2)=x(h_1y)(h_2)$
Since $H$ is normal, there must exist some $h_3$ s.t. $h_1y=yh_3$
$(xh_1)(yh_2)=x(yh_3)(h_2)=(xy)(h_3h_2)$
Since $H$ is a group, $h_3h_2=h_4\in H$.
$(xh_1)(yh_2)=(xy)h_4$

**Theorem 14.4**
Let $H$ be a subgroup of $G$. Left coset multiplication by representatives $(aH)(bH)=(ab)H$ is well-defined iff $H$ is normal.

**Corollary 14.5**
Let $H$ be a normal subgroup of $G$. Coset multiplication by representatives forms a group over the cosets of $H$.

**Definition 14.6**
The group in 14.5 is the **factor group** (or **quotient group**) of $G$ by $H$.

**Theorem 14.9**
$\gamma(x)=xH$ is a homomorphism from $G$ to $G/H$ with kernel $H$.

**Theorem 14.11**
Let $\phi$ be a homomorphism from $G$ to $G'$ with kernel $H$. $\mu(gH)=\phi(g)$ is an isomorphism from $G/H$ to $\phi[G]$. $\gamma(g)=gH$ is a homomorphism from $G$ to $G/H$. $\phi$ can be factored as $\mu\gamma$.

**Theorem 14.13**
Let $H$ be a subgroup of $G$.
1. $ghg^{-1}\in H$ for all $g\in G$ and $h\in H$
2. $gHg^{-1}=H$ for all $g\in G$
3. $gH=Hg$ for all $g\in G$
are all equivalent definitions of $H$ being a normal subgroup of $G$.

**Theorem 14.15**
An isomorphism from $G$ to itself is an **automorphism** of $G$. $i_g(x)=gxg^{-1}$ is the **inner automorphism** of $G$ by $g$. $i_g$ is called **conjugation by $g$**. A subgroup $K$ of $G$ is called a **conjugate subgroup of $H$** if $K=i_g[H]$ for some $g\in G$.
**Remark:** Definition 2 of 14.13 is equivalent to saying $H$ is invariant under all inner automorphisms of $G$.

# Section 15
**Theorem 15.8**
Let $G=H\times K$ where $H$ and $K$ are groups. $G/\bar{H}\cong K$ and $G/\bar{K}\cong H$.

**Theorem 15.9**
A factor group of a cyclic group is cyclic.

**Definition 15.14**
A nontrivial group is **simple** if it has no proper nontrivial normal subgroups.

**Theorem 15.16**
Homomorphisms preserve normal subgroups both ways. ($\phi[N]$ is normal in $\phi[G]$, but not necessarily in $G'$.)

**Definition 15.17**
A **maximal** normal subgroup of a group is a proper subgroup s.t. no proper normal subgroup properly contains it.

**Theorem 15.16**
Homomorphisms preserve normal subgroups both ways.

**Theorem 15.18**
$M$ is maximal iff $G/M$ is simple.

**Theorem 15.20**
The commutators (elements of the form $aba^{-1}b^{-1}$ for some $a,b\in G$) generate a **commutator subgroup** of $G$. This subgroup is normal. Further, $G/N$ is abelian iff $C\leq N$.
**Proof:**
First, note that elements of $C$ are finite products of commutators.
We will first show that the conjugation of a commutator is a product of commutators.
Let $a,b,g\in G$
$gaba^{-1}b^{-1}g^{-1}$
$gaba^{-1}g^{-1}gb^{-1}g^{-1}$
$gab(ga)^{-1}gb^{-1}g^{-1}$
$cbc^{-1}gb^{-1}g^{-1}$ (labeling $c=ga$)
$cbc^{-1}gb^{-1}g^{-1}$
$cbc^{-1}b^{-1}bgb^{-1}g^{-1}$
$(cbc^{-1}b^{-1})(bgb^{-1}g^{-1})$
showing that the conjugation of $aba^{-1}b^{-1}$ by $g$ is a product of two commutators, meaning that it is again an element of $C$.
Take $c_1c_2\ldots c_n$ where $c_i$ are commutators.
Conjugating by $g$:
$gc_1c_2\ldots c_ng^{-1}$
Inserting $g^{-1}g=e$ in between the $c_i$:
$gc_1g^{-1}gc_2g^{-1}g\ldots g^{-1}gc_ng^{-1}$
$=(gc_1g^{-1})(gc_2g^{-1})(g\ldots g^{-1})(gc_ng^{-1})$ showing that the conjugation of a finite product of commutators is a finite product of conjugations of commutators. We already know that the conjugation of a commutator is a product of commutators, meaning that the aforementioned product is a finite product of commutators, showing that it is in $C$ and completing the proof.

**Questions:**
1. Any examples of commutator subgroup $\neq$ commutator set?
2. Exercise 37, what if abelian instead of cyclic?

# Section 16
**Definition 16.1**
Let $G$ be a group, and $X$ a set. A **group action** on $X$ by $G$ is defined as $*:G\times X\to X$ s.t. $ex=x$ and $(g_1g_2)x=g_1(g_2x)$ for all $x\in X$ and $g_1,g_2\in G$. $X$ is called a $G$-set.

**Theorem 16.3**
Let $G$ be some group and $X$ some $G$-set. $\sigma_g:X\to X$ given by $\sigma_g(x)=gx$ is a permutation of $X$. $\phi:G\to S_X$ given by $\phi(g)=\sigma_g$ is a homomorphism. Note that $\phi(g)(x)=gx$
Remark: Analogue of Cayley's theorem?

For some group $G$ and some $G$-set $X$, the subset of $G$ leaving every element of $X$ fixed forms a normal subgroup of $G$. $X$ can be regarded as a $G/N$-set where the action of a coset $gN$ on any $x\in X$ is well defined by representatives.
If $N=\{e\}$, then $e$ is the only element leaving all elements of $X$ fixed. In this case, it is said that $G$ **acts faithfully** on $X$.
A group $G$ is **transitive** on $X$ if for every $x_1,x_2\in X$ there exists some $g$ s.t. $gx_1=x_2$.

For a group $G$ and a $G$-set $X$, for any $g\in G$ let $X_g=\{x\in X\ |\ gx=x\}$ be the subset of $X$ consisting of all elements of $X$ left fixed by $g$. Similarly, let $G_x=\{g\in G\ |\ gx=x\}$ be the subset of $G$ that leaves $x$ fixed.
**Theorem 16.12** and **Definition 16.13**
For a group $G$ and a $G$-set $X$, $G_x$ is a subgroup for all $x\in X$, called the **isotropy subgroup** of $x$.

**Theorem 16.14**
For a group $G$ and a $G$-set $X$, define a relation $x_1\sim x_2 \iff \exists g\in G,\ gx_1=x_2$. In other words, $x\sim y$ iff there is an element of $G$ mapping $x$ to $y$. $\sim$ is an equivalence relation.

**Definition 16.15**
The partitions of the previously defined equivalence relation are the **orbits in $X$ under $G$**. For $x\in X$, the partition containing $x$ is called the **orbit of $x$**, denoted by $Gx$.

**Theorem 16.16**
For a group $G$, a $G$-set $X$, and $x\in X$, $|Gx|=(G:G_x)$ If $|G|$ is finite, $|Gx|$ divides $|G|$.
Proof idea: There is a bijection between $Gx$ and left cosets of $G_x$.

# Section 17
**Theorem 17.1 (Burnside's Lemma)**
For a finite group $G$ and a finite $G$-set $X$, let the number of orbits in $X$ under $G$ be $r$.
$$r|G|=\sum_{g\in G}|X_g|$$
**Corollary 17.2**
The number of orbits in $X$ is
$$r=\frac{1}{|G|}\sum_{g\in G}|X_g|$$