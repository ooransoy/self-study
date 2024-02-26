# Section 26

**Definition 26.1**

A **homomorphism** is a $\phi : R \to R'$ s.t. for all $a,b\in R$,

$$\phi(a+b)=\phi(a)+\phi(b)$$

and

$$\phi(ab)=\phi(a)\phi(b)$$



**Theorem 26.3**

Let $\phi : R \to R'$ be a homomorphism from a ring to another.

- If $0$ is the additive identity for $R$, then $\phi(0)$ is the additive identity for $R'$.

- For all $a\in R$, $\phi(-a)=-\phi(a)$.

- If $S\leq R$ is a subring, $\phi[S]\leq R'$.

- If $S'\leq R'$ is a subring, $\phi^{-1}[S']\leq R$.

- If $1$ is unity for $R$, then $\phi(1)$ is unity for $R'$.



**Definition 26.4**

Let $\phi : R \to R'$ be a homomorphism from a ring to another. We define the **kernel** of $\phi$ denoted by $\mathrm{Ker}(\phi)$ to be $\phi^{-1}[0']=\{r\in R\ |\ \phi(r)=0'\}$.



**Theorem 26.5**

Let $H$ be the kernel of a homomorphism $\phi : R \to R'$. $a+H=H+a=\phi^{-1}[\{\phi(a)\}]$ where $a+H=\{a+h\ |\ h\in H\}$ is the coset of $H$ containing $a$ in the additive abelian group $\langle R, +\rangle$.



**Corollary 26.6**

A homomorphism is one-to-one iff its kernel is $\{0\}$.



**Theorem 26.7**

Let $H$ be the kernel of a homomorphism $\phi : R \to R'$. The additive cosets of $H$ form a ring $R/H$.

Let $a,b\in R$ and $a+H$, $b+H$ be the additive cosets containing $a$ and $b$. Coset addition and multiplication by representatives are well defined.

$$(a+H)+(b+H)=(a+b)+H$$

$$(a+H)(b+H)=(ab)+H$$

Also, the map $\mu : R/H\to \phi[R]$ given by $\mu(a+H)=\phi(a)$ is an isomorphism.



**Theorem 26.9**

Let $H$ be a subring of a ring $R$. Multiplication of additive cosets of $H$ is well defined iff $ah\in H$ and $ha\in H$ for all $a\in R$ and $h\in H$.

$(a+h_1)(b+h_2)=ab+h_1b+ah_2+h_1h_2$. $h_1h_2\in H$ because $H$ is a subring, $ah_2,h_1b\in H$ by hypothesis, so $(a+h_1)(b+h_2)\in ab+H$.



**Definition 26.10**

An additive subgroup $N$ of a ring $R$ satisfying $aN\subseteq N$ and $Na\subseteq N$ for all $a\in R$ is called an **ideal**.

Remark: It is readily seen that all ideals are subrings.



**Example 26.11**

$n\mathbb{Z}$ is an ideal of $\mathbb{Z}$.



**Corollary 26.14**, **Definition 26.15**

Let $N$ be an ideal of a ring $R$. The additive cosets of $N$ form a ring $R/N$ under coset addition and multiplication by representatives. $R/N$ is called the **factor ring of $R$ by $N$**.



**Theorem 26.16**

Let $N$ be an ideal of a ring $R$. $\gamma: R\to R/N$ given by $\gamma(x)=x+N$ is a ring homomorphism with kernel $N$.



**Theorem 26.17 (Fundamental Homomorphism Theorem)**

Let $\phi: R\to R'$ be a ring homomorphism with kernel $N$. $\phi[R]$ is a ring, and $\mu:R/N\to \phi[R]$ given by $\mu(x+N)=\phi(x)$ is an isomorphism. If $\gamma:R\to R/N$ is the canonical homomorphism given by $\gamma(x)=x+N$, then $\phi=\mu\gamma$.



**Example 26.19**

From Example 26.11, we have that $n\mathbb{Z}$ is an ideal of $\mathbb{Z}$. Thus we can speak of the factor ring $\mathbb{Z}/n\mathbb{Z}$. From Example 18.11 we have that $\phi : \mathbb{Z}\to\mathbb{Z}_n$ given by $\phi(x)=x\mod n$ is a ring homomorphism. We see that $\mathrm{Ker}(\phi)=n\mathbb{Z}$. The Fundamental Homomorphism Theorem gives us the map $\mu:\mathbb{Z}/n\mathbb{Z}\to\mathbb{Z}_n$ given by $\mu(x+n\mathbb{Z})=x \mod n$ is well-defined and an isomorphism.



Remark:

Normal subgroup => Ideal

Factor group => Factor ring



# Section 27

**Theorem 27.5**

If an ideal $N$ of a ring with unity $R$ contains a unit, then $N=R$.



**Corollary 27.6**

A field has no proper nontrivial ideals.



**Definition 27.7**

A **maximal ideal** is one such that there is no proper ideal properly containing it.



**Theorem 27.9** (Analogue of Theorem 15.18)

Let $R$ be a commutative ring with unity. $R/N$ is a field iff $N$ is maximal.



**Corollary 27.11**

A commutative ring with unity is a field iff it has no proper nontrivial ideals.



**Definition 27.13**

An ideal $N$ is **prime** iff $ab\in N$ implies either $a\in N$ or $b\in N$.



**Theorem 27.15**

If $R$ is a commutative ring with unity and $N$ is a proper ideal of $R$, then $R/N$ is an integral domain iff $N$ is prime.

$(a+N)(b+N)=N\iff a+N=N\ \vee\ b+N=N$



**Corollary 27.16**

Every maximal ideal in a commutative ring with unity is prime.



Remark:

For a commutative ring with unity $R$,

1. An ideal $M$ of $R$ is maximal iff $R/M$ is a field.

2. An ideal $N$ of $R$ is prime iff $R/N$ is an integral domain.

3. Every maximal ideal is prime.



**Theorem 27.17**

If $R$ is a ring with unity, $\phi : \mathbb{Z}\to R$ given by $\phi(n)=n\cdot 1$ is a homomorphism.



**Corollary 27.18**

If $R$ is a ring with unity with characteristic $n>1$, $R$ contains a subring isomorphic to $\mathbb{Z}_n$. If $R$ has characteristic $0$, $R$ contains a subring isomorphic to $\mathbb{Z}$.



**Theorem 27.19**

If $F$ is a field with prime characteristic $p>1$, $F$ contains a subfield isomorphic to $\mathbb{Z}_p$. If $F$ is of characteristic $0$, $F$ contains a subfield isomorphic to $\mathbb{Q}$. (See corollaries 21.8 and 21.9.)



**Definition 27.20**

The fields $\mathbb{Z}_p$ and $\mathbb{Q}$ are **prime fields**.



**Definition 27.21**

If $R$ is a commutative ring with unity, $\{ra\ |\ r\in R\}$ is the **principal ideal generated by $a$**, denoted by $\langle a\rangle$.



**Theorem 27.24**

If $F$ is a field, every ideal of $F[x]$ is principal.



Proof idea: $g(x)$ is a nonzero element of minimal degree in the ideal $N$. If $g(x)$ has nonzero constant term, $N=R=\langle 1\rangle$. Otherwise: For any $f(x)\in N$, $f(x)=g(x)q(x)+r(x)$. LHS $\in N$, $g(x)q(x)\in N$ because ideals absorb products, so since $N$ is an additive subgroup $r(x)\in N$. Since $r(x)$ must have degree lower than $g(x)$ and since $g(x)$ is of minimal degree, $r(x)$ must be zero. This shows that $N=\langle g(x)\rangle$, completing the proof.



**Theorem 27.25**

An ideal $\langle p(x)\rangle\neq\{0\}$ of $F[x]$ is maximal iff $p(x)$ is irreducible over $F$.



![[Pasted image 20231129012331.png]]

**Theorem 27.27**

Let $p(x)$ be an irreducible in $F[x]$. If $p(x)|r(x)s(x)$, then either $p(x)|r(x)$ or $p(x)|s(x)$.





# Section 28

**Definition 28.1**

Let $S$ be a finite subset of $F[\mathbf{x}]$. The **algebraic variety** $V(S)$ in $F^n$ is the set of all common zeros of the polynomials in $S$.



**Example 28.2**

Let $S=\{2x+y-2\}\subset \mathbb{R}[x,y]$. The variety $V(S)$ is the line with x-intercept 1 and y-intercept 2.



**Definition 28.3**

Let $I$ be an ideal in a commutative ring with unity $R$. A subset $\{b_1, b_2, \ldots, b_n\}$ of $I$ is a **basis** for $I$ if $I=\langle b_1,b_2,\ldots,b_n\rangle$.



Remark: Unlike in linear algebra, there is no requirement of independence for a subset to be a basis.



**Theorem 28.4**

Let $f_1,f_2,\ldots,f_n\in F[\mathbf{x}]$. The common zeros of the $f_i$ are precisely the common zeros of the ideal $\langle f_1,f_2,\ldots,f_n\rangle$ in $F[\mathbf{x}]$.



**Theorem 28.5 (Hilbert Basis Theorem)**

Let $F$ be any field. Every ideal in $F[x_1,x_2,\ldots,x_n]$ has a finite basis.



**Theorem 28.6**

Let $f(\mathbf{x}), g(\mathbf{x}), q(\mathbf{x}), r(\mathbf{x})\in F[\mathbf{x}]$ s.t. $f(\mathbf{x})=g(\mathbf{x})q(\mathbf{x})+r(\mathbf{x})$. The common zeros of $f(\mathbf{x})$ and $g(\mathbf{x})$ are the same as the common zeros of $g(\mathbf{x})$ and $r(\mathbf{x})$. Also, the common divisors of $f(\mathbf{x})$ and $g(\mathbf{x})$ are the same as the common divisors of $g(\mathbf{x})$ and $r(\mathbf{x})$.

If $f(\mathbf{x})$ and $g(\mathbf{x})$ are members of a basis of an ideal $I$ in $F[\mathbf{x}]$, then the replacement of $f(\mathbf{x})$ by $r(\mathbf{x})$ again yields a basis of $I$.



We denote the leading term of $f$ by $1t(f)$, and the power product of that term by $1p(f)$.

**Definition 28.10**

A set $\{g_1,g_2,\ldots, g_n\}$ of nonzero polynomials in $F[\mathbf{x}]$ with some term ordering $<$ is a **Gröbner basis** of the ideal $I=\langle g_1,g_2,\ldots g_n\rangle$ iff for every element $f\in I$, there exists some $g_i$ s.t. $1p(g_i)|1p(f)$. 



Let $S(f,g)$ be the polynomial obtained by multiplying $f$ by the smallest power product possible s.t. $1p(g)|1p(S(f,g))$.



**Theorem 28.12**

A basis $\{g_1,g_2,\ldots,g_n\}$ of an ideal is a Gröbner basis iff for all pairs of $g_i$ and $g_j$ s.t. $i\neq j$, $S(g_i,g_j)$ can be reduced to zero by dividing remainders by elements of the basis.
