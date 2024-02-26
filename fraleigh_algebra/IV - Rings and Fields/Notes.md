# Section 18
**Definition 18.1**
A **ring** $\langle R, +, \cdot\rangle$ is
1. $R$ is abelian under addition
2. Multiplication is associative on $R$
3. $a(b+c)=ab+ac$ and $(a+b)c=ac+bc$

**Theorem 18.8**
Let $R$ be a ring with additive identity 0.
1. $0a=a0=0$
2. $a(-b)=(-a)b=-(ab)$
3. $(-a)(-b)=ab$

**Definition 18.9**
$\phi : R\to R'$ is a **homomorphism** if
1. $\phi(a+b)=\phi(a)+\phi(b)$
2. $\phi(ab)=\phi(a)\phi(b)$

**Definition 18.12**
An **isomorphism** is a bijective homomorphism. Two rings are **isomorphic** if there is an isomorphism between them.

The **zero ring** is $\{0\}$ where $0+0=0$ and $0(0)=0$.

**Definition 18.14**
A **commutative ring** is one where multiplication is commutative.
A **ring with unity** is one with a multiplicative identity. The multiplicative identity is called **unity**. In a ring with unity, we can speak of the **multiplicative inverse** of an element.

**Definition 18.16**
In a ring with unity $1\neq 0$, an element with a multiplicative inverse is a **unit**. If every nonzero element is a unit, the ring is a **division ring** or a **skew ring**. A commutative division ring is a **field**. A noncommutative division ring is a **strictly skew field**.
A **subring** of a ring is a subset of the ring closed under its operations. A **subfield** is defined in the same way.

# Section 19
**Definition 19.2**
For two nonzero $a,b$ in a ring $R$ s.t. $ab=0$, $a$ and $b$ are called **0 divisors**.

**Theorem 19.3**
The 0 divisors of $\mathbb{Z}_n$ are precisely the elements not coprime to $n$.

**Corollary 19.4**
$\mathbb{Z}_p$ for prime $p$ has no divisors of 0.

**Theorem 19.5**
For any ring $R$, $ab=ac \iff b=c$ holds for all $a,b,c\in R$ iff $R$ has no divisors of 0.

**Definition 19.6**
An **integral domain** is a commutative ring with unity $1\neq 0$ that contains no divisors of 0.

**Theorem 19.9**
Every field is an integral domain.

![[Pasted image 20231018200611.png]]

**Theorem 19.11**
Every finite integral domain is a field.

**Corollary 19.12**
$\mathbb{Z}_p$ is a field for prime $p$.

**Definition 19.13**
The **characteristic** of a ring $R$ is the least positive integer $n$ s.t. $na=0$ for all $a\in R$. (Here, $na$ means $a+a+\ldots$), or 0 if such $n$ doesn't exist.

**Theorem 19.15**
In the previous definition, if the ring has unity it suffices to examine only $a=1$.
Idea of the proof:
$na=a+a+\ldots=a(1+1+\ldots)=a(n1)$

# Section 20
**Theorem 20.1 (Fermat's Little Theorem)**
For integer $a$ and prime $p$,
$a\not\equiv0\mod p \iff a^{p-1}\equiv1\mod p$

**Corollary 20.2**
For integer $a$ and prime $p$,
$a^p\equiv a\mod p$

**Theorem 20.6**
The set $G_n$ of nonzero elements in $\mathbb{Z}_n$ not divisors of 0 form a group under multiplication.
Remark: By Theorem 19.3, the nonzero elements not divisors of 0 are precisely the elements coprime to $n$.

**Theorem 20.8 (Euler's Theorem)**
For coprime positive integers $n$ and $a$,
$a^{\varphi(n)}\equiv 1\mod n$
Proof idea: Let $b$ be the remainder from $a$ when divided by $n$. $b\in G_n$, and $|\langle b\rangle|$ divides $|G_n|=\varphi(n)$ by Lagrange's theorem.

**Theorem 20.10**
Let $a$ be some element of $\mathbb{Z}_n$ coprime to $n$. For each $b\in\mathbb{Z}_n$ there is a unique $x\in\mathbb{Z}_n$ s.t. $ax=b$.
Remark: $a$ is a unit, $a^{-1}b$ is the unique solution.

**Theorem 20.12**
Let $a,b\in\mathbb{Z}_n$, and $d=\gcd(a,n)$. $ax=b$ is solvable iff $d|b$, in which case there are $d$ solutions.

# Section 21
To construct a field $F$ of quotients over some integral domain $D$:
1. Define the elements of $F$
2. Define addition and multiplication on $F$
3. Check that $F$ is a field
4. Show $D$ is contained in $F$.

Form a set $S$ consisting of $(a,b)$, representing the formal quotients $a/b$.

**Definition 21.1**
Two elements $(a,b)$ and $(c,d)$ of $S$ are equivalent - $(a,b)\sim(c,d)$ - iff $ad=bc$.

**Lemma 21.2**
The previous definition describes an equivalence relation on $S$.

We finish step 1 by defining the elements of $F$ to be $[(a,b)]$, the equivalence classes.

**Lemma 21.3**
Defining $[(a,b)]+[(c,d)]=[(ad+bc,bd)]$ and $[(a,b)][(c,d)]=[(ac,bd)]$ give well-defined field operations on $F$.

This finishes step 2.

**Lemma 21.4**
$i:D\to F$ given by $i(a)=[(a,1)]$ is an isomorphism of $D$ with some subring of $F$. $i[D]$ is a subdomain of $F$.

**Theorem 21.5**
Any integral domain can be expanded to a field s.t. every element of the field is expressed as a quotient of two elements of the domain. This is called the **field of quotients of $D$**.

**Theorem 21.6**
Let $F$ be a field of quotients of $D$, and let $L$ be some field containing $D$ as a subdomain. There exists some map $\psi:F\to L$ that gives an isomorphism of $F$ with some subfield of $L$ s.t. $\psi(i(a))=a$ for all $a\in D$.

**Corollary 21.8**
Every field $L$ containing an integral domain $D$ contains a field of quotients of $D$.

**Corollary 21.9**
Any two fields of quotients of an integral domain $D$ are isomorphic.

# Section 22
**Definition 22.1**
For some ring $R$, a **polynomial $f(x)$ with coefficients in $R$** is an infinite formal sum $\sum^\infty_{i=0}a_ix^i$ with $a_i\neq 0$ for only a finite number of $i$.
The $a_i$ are the **coefficients of $f(x)$**. The greatest $i$ s.t. $a_i\neq 0$ is the **degree of $f(x)$**, or the degree is undefined if no such $i$ exists.
An element of $R$ is a **constant polynomial**.

For $f(x)=\sum^\infty_{i=0}a_ix^i$ and $g(x)=\sum^\infty_{i=0}b_ix^i$,
$f(x)+g(x)=\sum^\infty_{i=0}(a_i+b_i)x^i$
$f(x)g(x)=\sum^\infty_{i=0}(\sum^i_{j=0}a_jb_{i-j})x^i$

**Theorem 22.2**
Let $R$ be a ring. The set $R[x]$ of all polynomials in an indeterminate $x$ with coefficients in $R$ is a ring under polynomial addition and multiplication. If $R$ is commutative, so is $R[x]$, and if $R$ has unity $1\neq 0$, $1$ is also unity for $R[x]$.

$(R[x])[y]$ is naturally isomorphic to $(R[y])[x]$. This is the **ring of polynomials in two indeterminates $x$ and $y$**, which is denoted by $R[x,y]$. The **ring of polynomials in $n$ indeterminates**: $R[x_1,x_2,\ldots,x_n]$.

Let $F$ be a field. $F[x]$ is not a field, the polynomial $x$ has no inverse. $F[x_1,\ldots,x_n]$ can be completed to a field of quotients $F(x_1,\ldots,x_n)$, the **field of rational functions in $n$ indeterminates**.

**Theorem 22.4 (The Evaluation Homomorphisms for Field Theory)**
Let $F,E$ be fields and $F\leq E$, and $x$ an indeterminate. $\phi_\alpha:F[x]\to E$ given by $\phi_\alpha(\sum^\infty_{i=0}a_ix^i)=\sum^\infty_{i=0}a_i\alpha^i$ is a homomorphism - the **evaluation** at $\alpha$. Note that $\phi_\alpha(a)=a$. for $a\in F$.
Remark: Also works for commutative rings with unity, but we are primarily interested in fields.

![[Pasted image 20231021134740.png]]

**Definition 22.10**
Let $F\leq E$ be fields, $f(x)\in F[x]$, and $\alpha\in E$. Denote $\phi_\alpha(f(x))$ by $f(\alpha)$. If $f(\alpha)=0$, then $\alpha$ is a **zero of $f(x)$**.

**Theorem 22.11**
$x^2-2$ has no zeros in the rational numbers. $\sqrt{2}$ is not a rational number.

# Section 23
**Theorem 23.1 (Division algorithm for $F[x]$)**
Let $f(x),g(x)\in F[x]$ be nonzeros s.t. the degree of $g$ is at least 1. There exist unique $q(x),r(x)\in F[x]$ s.t. $f(x)=g(x)q(x)+r(x)$ and either $r(x)=0$ or the degree of $r(x)$ is smaller than the degree of $g(x)$.
Note: Polynomials can be divided by long division.

**Corollary 23.3 (Factor Theorem)**
Let $f(x)\in F[x]$. $f(x)=g(x)(x-a)$ for some $g(x)\in F[x]$ if and only if $f(x)$ has a zero at $a$.
Proof idea: Divide by $x-a$ to leave a constant remainder, apply evaluation homomorphism at $a$ to find that the remainder must be 0.

**Corollary 23.5**
Let $f(x)\in F[x]$ be of degree $n$. $f(x)$ has at most $n$ zeros.
Proof idea: By the factor theorem every zero gives some linear factor, the product of $k$ linear factors is of degree $k$, so there must be at most $n$ linear factors and by extension at most $n$ zeros.

**Corollary 23.6**
Every finite subgroup of the multiplicative group $\langle F*,\cdot\rangle$ of a field is cyclic.
TODO: motivate proof

**Definition 23.7**
Let $f(x)\in F[x]$ of positive degree. If there is no $g(x),h(x)\in F[x]$ s.t. both are of degree lower than $f(x)$ and s.t. $f(x)=g(x)h(x)$, we call $f(x)$ **irreducible over $F$**. Else, it is **reducible over $F$**.

**Example 23.8**
Consider $f(x)=x^2-2$ over $\mathbb{Q}$. If it were reducible, it would need to have a linear factor $x-a$. By the factor theorem, that must mean $f(x)$ has a zero at $a$. But $f(x)$ has no zeros in $\mathbb{Q}$, therefore it must be irreducible over $\mathbb{Q}$. Note that $f(x)=(x-\sqrt{2})(x+\sqrt{2})$ so $f(x)$ is reducible over $\mathbb{R}$. 

**Theorem 23.10**
Let $f(x)\in F[x]$ be of degree 2 or 3. $f(x)$ is reducible over $F$ iff it has a zero in $F$.
Proof idea: A quadratic must factor into a linear and a linear, a cubic must factor into a quadratic and a linear. Both have a linear factor meaning both must have some zero by the factor theorem. The converse is trivial by the factor theorem.

**Theorem 23.11**
If $f(x)\in \mathbb{Z}[x]$ factors into polynomials in $\mathbb{Q}[x]$ of degree $r$ and $s$ iff it factors into polynomials of the same degree in $\mathbb{Z}[x]$.
TODO: proof omitted in book

**Corollary 23.12**
Let $f(x)\in\mathbb{Z}[x]$ with leading coefficient $1$ and with nonzero constant term $a_0$. If $f(x)$ has a zero in $\mathbb{Q}$, it also has a zero $m$ in $\mathbb{Z}$ and $m|a_0$.

**Theorem 23.15 (Eisenstein Criterion)**
Let $f(x)\in \mathbb{Q}[x]$ and $p$ a prime. If $p\nmid a_n$, $p|a_i$ for $i<n$, and $p^2 \nmid a_0$, then $f(x)$ is irreducible over $\mathbb{Q}$.
TODO: reread proof

**Corollary 23.17**
The **$p$th cyclotomic polynomial** $\Phi_p(x)=\frac{x^p-1}{x-1}=\sum_{i=0}^{p-1}x^i$ for a prime $p$ is irreducible over $\mathbb{Q}$.
Proof idea: Apply evaluation homomorphism at $x+1$, then apply Eisenstein's criterion.
(is it still a homomorphism? if $x$ is an indeterminate how does it make sense to talk about "evaluating at $x+1$"?)

**Definition**
For $f(x),g(x)\in F[x]$, we say that **$g(x)$ divides $f(x)$ in $F[x]$** if there exists some $q(x)\in F[x]$ s.t. $f(x)=g(x)q(x)$.

**Theorem 23.18**
Let $p(x),r(x),s(x)\in F[x]$ s.t. $p(x)$ is irreducible in $F[x]$. If $p(x)|r(x)s(x)$, either $p(x)|r(x)$ or $p(x)|s(x)$.
The proof is delayed to section 27.

**Corollary 23.19**
The previous theorem generalizes to any number of polynomials simply by mathematical induction.

**Theorem 23.20**
For $f(x)\in F[x]$, $f(x)$ has a unique factorization into irreducible polynomials in $F[x]$, up to order and unit factors.

# Section 24
An endomorphism is a homomorphism from a group to itself.
**Theorem 24.1**
The set $\mathrm{End}(A)$ of endomorphisms of an abelian group $A$ forms a ring with over addition and composition. ($(\phi+\psi)(x)=\phi(x)+\psi(x)$, $(\phi\psi)(x)=\phi(\psi(x))$).

**Example 24.3**
The subring of $\mathrm{End}(\langle F[x],+\rangle)$ generated by multiplication by $x$, multiplication by any element of $F$, and formal differentiation is the **Weyl algebra**.

**Theorem 24.4**
For a multiplicative group $G$ and a commutative ring with nonzero unity $R$, $\langle RG, +, \cdot\rangle$ forms a ring.
For $i\in I$ that indexes $G$, let us define $RG$ to consist of $\sum_{i\in I}r_ig_i$ for all $r_i\in R$. We define addition by
$$\left(\sum_{i\in I}a_ig_i\right)+\left(\sum_{i\in I}b_ig_i\right)=\sum_{i\in I}(a_i+b_i)g_i$$
and multiplication by
$$\left(\sum_{i\in I}a_ig_i\right)\left(\sum_{i\in I}b_ig_i\right)=\sum_{i\in I}\left(\sum_{g_jg_k=g_i}a_jb_k\right)g_i$$
Remark: I think this is similar to a vector space, where the basis vectors are analoguous to the $g_i$. Obviously they're not the same, but they look similar.
**Definition 24.5**
The ring $RG$ is the **group ring of $G$ over $R$**. If $F$ is a field, $FG$ is the **group algebra of $G$ over $F$**.

**Example 24.6**
Consider $\mathbb{Z}_2G$ where $G$ is the cyclic group $\{e,a\}$ of order 2. The elements are $0e+0a$, $0e+1a$, $1e+0a$, $1e+1a$, which we label naturally by $0$, $a$, $e$, $e+a$.
![[Pasted image 20231025141444.png]]

**Theorem 24.9**
The quaternions $\mathbb{H}$ form a strictly skew field.
$$i^2=j^2=k^2=ijk=-1$$
$ij=k=-ji$ so $\mathbb{H}$ is not a field.

**Theorem 24.10 (Wedderburn's Theorem)**
Every finite division ring is a field.

# Section 25
In this section assume all rings have nonzero unity.

**Definition 25.1**
An **ordered ring** is a ring $R$ equipped with a nonempty subset $P\subseteq R$ s.t. the closure and trichotomy properties are satisfied.
*Closure*:
If $a,b\in P$ then $a+b,ab\in P$
*Trichotomy*:
For any $a\in R$ one and only one of $a\in P$, $a=0$, $-a\in P$ hold.
Elements of $P$ are called positive.
For an ordered ring $R$ with positive elements $P$ and a subring $S\leq R$, $P\cap S$ is a suitable set of positive elements of $S$, and gives an **induced ordering** of $S$.

**Example 25.2**
For a ring $R$, define $P_{\mathrm{high}}$ to be the set containing precisely the elements of $R[x]$ that have a positive leading coefficient, and define $P_{\mathrm{low}}$ to be the subset of $R[x]$ of all polynomials with positive trailing coefficients.
(The leading coefficient is the highest indexed nonzero coefficient, and the trailing coefficient is the lowest indexed nonzero coefficient.)
$P_{\mathrm{high}}$ and $P_{\mathrm{low}}$ give orderings on $R[x]$.

**Theorem 25.3**
All squares of nonzero elements of an ordered ring are positive. Ordered rings have characteristic 0 and no divisors of 0. Unity is positive.
Proof idea: Either $a$ or $-a$ is positive, so at least one of $a^2$ or $(-a)^2$ is positive. $1^2=1$ is positive. They are equal, so $a^2$ is positive. $1$ is positive, so $1+1+\ldots+1=n\cdot 1$ is positive for all $n\in\mathbb{Z}$, whereas 0 is not positive. For nonzero $a,b\in R$, either $ab$ or $-ab$ is positive, and 0 isn't.

**Corollary 25.4**
Any ordered ring $R$ has a subring isomorphic to $\mathbb{Z}$. The induced ordering of $\mathbb{Z}$ from $R$ is the only and the natural ordering of $\mathbb{Z}$. The natural ordering of $\mathbb{R}$ is the only ordering.

Finite rings cannot be ordered as they can't have characteristic 0. $\mathbb{C}$ cannot be ordered as $1=1^2$ and $-1=i^2$ are squares so they must be both positive, breaking trichotomy.

**Theorem 25.5**
Let $R$ be an ordered ring with $P$ as positives. We define a relation $a<b\iff b-a\in P$. This relation has the following three properties:
*Trichotomy*:
Either $a<b$, $a=b$ or $b<a$.
*Transitivity*:
If $a<b$ and $b<c$ then $a<c$.
*Isotonicity*:
If $b<c$ then $a+b<a+c$.
If $0<a$ then $ab<ac$ and $ba<ca$

**Definition 25.7**
An ordering where for any positive $a,b\in R$ there exists a positive integer $n$ s.t. $b<na$ is an **Archimedean ordering**.
The ordering of $\mathbb{R}[x]$ given by $P_{\mathrm{low}}$ is not Archimedean. The natural ordering of $\mathbb{R}$, however, is Archimedean.

**Example 25.8**
Consider the formal sum $\sum_{i=0}^\infty a_ix^i$ for indeterminate $x$. For a polynomial, we require that there be only a finite number of nonzero coefficients. If we lift this restriction, we obtain the **formal power series**. These series form a ring which we denote by $R[[x]]$.
Remark: We can order $R[[x]]$ by $P_{\mathrm{low}}$, but not $P_{\mathrm{high}}$ as not all formal power series have a highest nonzero coefficient. For example, the formal power series with all coefficients set to 1.

**Example 25.9**
If we consider the formal sums of the form $\sum_{i=N}^\infty a_ix^i$ for any integer $N$, we obtain a field $F((x))$.
![[Pasted image 20231025191539.png]]
Remark: If $F$ is an ordered field, we can again order $F((x))$ with $P_{\mathrm{low}}$. $F((x))$ contains a field of quotients of $F[x]$, and induces an ordering on this field of quotients.

**Theorem 25.10**
Let $R$ be a ring ordered by positives $P$. Let $\phi:R\to R'$ be a ring homomorphism. $P'=\phi[P]$ satisfies the condition for an ordering, called the **ordering induced by $\phi$**. We also have that $a<b$ iff $\phi(a)<'\phi(b)$.

**Theroem 25.13**
Let $D$ be an ordered integral domain with positives $P$, and let $F$ be a field of quotients over $D$.
$$P'=\{x=a/b\ |\ a,b\in D, ab\in P\}$$ is well-defined and gives an ordering on $F$ which induces the ordering on $D$. $P'$ is the only subset with this property.