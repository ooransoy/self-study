# Section 29
**Definition 29.1**
A field $E$ is an **extension field of $F$** if $E\geq F$.

**Theorem 29.3 (Kronecker's Theorem) (Basic Goal)**
Let $F$ be a field and $f(x)$ a nonconstant polynomial in $F[x]$. There exists an extension $E$ of $F$ s.t. there exists $\alpha\in E$ s.t. $f(\alpha)=0$.
Construction: Let $p(x)$ be some irreducible that divides $f(x)$. $F[x]/\lrangle{p(x)}$ is a sufficient $E$.

**Definition 29.6**
An element $\alpha$ in an extension $E$ of a field $F$ is **algebraic over $F$** if $f(\alpha)=0$ for some $f(x)\in F[x]$. Otherwise, it is **transcendental over $F$**.

**Example 29.9**
$\pi$ is transcendental over $\Q$ but algebraic over $\R$.

**Definition 29.11**
An element of $\C$ that is algebraic over $\Q$ is an **algebraic number**. An element of $\C$ that is transcendental over $\Q$ is a **transcendental number**.

**Theorem 29.12**
Let $E$ be an extension field of $F$ and $\alpha \in E$. Let $\phi_\alpha : F[x]\to E$ be the evaluation homomorphism given by $\phi_\alpha(a)=a$ for $a\in F$ and $\phi_\alpha(x)=\alpha$. $\alpha$ is transcendental over $F$ iff $\phi_\alpha$ is injective (i.e. $\phi_\alpha$ gives an isomorphism from $F[x]$ to a subdomain of $E$.)

**Theorem 29.13**
Let $E$ be an extension of $F$. For every $\alpha \in E$, there is an irreducible polynomial $p(x)\in F[x]$ with $\alpha$ as a root. $p(x)$ is of minimal degree $\geq 1$ in $F[x]$ and is uniquely determined up to a constant factor (a unit).
For any $f(x)\in F[x]$, if $\alpha$ is a root of $f(x)$ then $p(x)\ |\ f(x)$.

**Definition 29.14**
Let $E$ be an extension of the field $F$, and $\alpha\in E$. The unique irreducible monic polynomial in $F[x]$ with $\alpha$ as a root is the **irreducible polynomial for $\alpha$ over $F$** denoted by $\irr(\alpha, F)$. The degree of this polynomial is the **degree of $\alpha$ over $F$**, denoted by $\deg(\alpha, F)$.

**Example 29.15**
Consider $x=\sqrt{1+\sqrt{3}}$. $x^2=1+\sqrt{3}$, $x^2-1=\sqrt{3}$, $(x^2-1)^2=x^4-2x^2+1=3$, $x^4-2x^2-2=0$. Applying the Eisenstein criterion for $p=2$, $x^4-2x^2-2$ is irreducible. This completes our computation that $\irr(\sqrt{1+\sqrt{3}}, \Q)=x^4-2x^2-2$.

Remark: $\sqrt{2}$ is of degree 2 over $\Q$ but degree 1 over $\R$.

For an extension $E$ of a field $F$ and $\alpha\in E$, let $\phi_\alpha : F[x]\to E$ be the evaluation homomorphism given by $\phi_\alpha(a)=a$ for $a\in F$ and $\phi_\alpha(x)=\alpha$.
If $\alpha$ is algebraic over $F$:
The kernel of $\phi_\alpha$ is $\lrangle{\irr(\alpha, F)}$, that by Theorem 27.25 is a maximal ideal. This makes $F[x]/\lrangle{\irr(\alpha, F)}$ a field that is isomorphic to the image of $\phi_\alpha$ in $E$, $\phi_\alpha[F[x]]$. This subfield of $E$ is the smallest field containing $F$ and $\alpha$, which we denote by $F(\alpha)$.
If $\alpha$ is transcendental over $F$:
By Theorem 29.12, $\phi_\alpha$ gives an isomorphism of $F[x]$ with a subdomain of $E$. In the case that $\phi_\alpha[F[x]]$ is not a field but an integral domain we denote it by $F[\alpha]$. By Corollary 21.8, $E$ contains a field of quotients of $F[\alpha]$ as a subfield, which is the smallest field containing $F$ and $\alpha$. We denote this field of quotients by $F(\alpha)$.

**Example 29.16**
Since $\pi$ is transcendental over $\Q$, $\Q(\pi)$ is isomorphic to the field of rational functions on $\Q$ over an indeterminate $x$. From this we can see that an element that is transcendental over a field $F$ behaves structurally the same as an indeterminate over $F$.

**Definition 29.17**
An extension $E$ of a field $F$ is a **simple extension** if there exists $\alpha\in E$ s.t. $E=F(\alpha)$.

**Theorem 29.18**
Let $E$ be a simple extension $F(\alpha)$ of $F$, where $\alpha$ is algebraic over $F$ with $n=\deg(\alpha, F)\geq 1$. Every element $\beta$ of $E$ can be uniquely expressed as $\beta=b_0+b_1\alpha+b_2\alpha^2+\cdots+b_{n-1}\alpha^{n-1}$ for $b_i\in F$.

**Example 29.19**
TODO

# Section 30
**Definition 30.1**
For a field $F$, a **vector space over $F$** or an **$F$-vector space** consists of an abelian group of vectors $V$ equipped with vector addition, and a binary operation of scalar multiplication between elements of $F$ and $V$ (written with the scalar on the left and the vector on the right) s.t. the following conditions are satisfied for all $a,b\in F$ and $u,v\in V$:
1. $au\in V$
2. $a(bu)=(ab)u$
3. $(a+b)u=au+bu$
4. $a(u+v)=au+av$
5. $1\alpha=\alpha$
The elements of $V$ are the **vectors** and the elements of $F$ are the **scalars**. When there is only one field in consideration, we drop the reference to $F$ and simply refer to a **vector space**.

Both the $0$-vector and the $0$-scalar will be denoted by $0$.

**Example 30.2**
$\lrangle{\R^n,+}$ with $r\alpha=(ra_1,\ldots,ra_n)$ for $\alpha=(a_1,\ldots,a_n)\in \R^n$ and $r\in\R$ is a $\R$-vector space.

**Example 30.3**
For any field $F$, $F[x]$ is a vector space over $F$ with vector addition being addition in $F[x]$ scalar multiplication being defined naturally as multiplication in $F[x]$.

**Example 30.4**
Let $E$ be an extension of a field $F$. $E$ is a vector space over $F$.

**Theorem 30.5**
For a vector space $V$ on a field $F$, $a\in F$ and $\alpha\in V$:
1. $0\alpha=a0=0$
2. $(-a)\alpha=a(-\alpha)=-(a\alpha)$

**Definition 30.6**
For a vector space $V$ over a field $F$ and a subset $S=\{\alpha_i\ |\ i\in I\}\subseteq V$, $S$ **spans** (or **generates**) $V$ if every element $v$ in $V$ can be written as $v=\sum_{i\in I}f_i\alpha_i$ for $f_i\in F$ (denoted a **linear combination** of the $\alpha_i$).

**Example 30.7**
The vectors $(1,0,\ldots,0),(0,1,\ldots,0),(0,0,\ldots,1)$ span $\R^n$ defined in Example 30.2. Likewise, the monomials $x^m$ for $m\in\N$ span $F[x]$ defined in Example 30.3.

**Example 30.8**
Let $E$ be an extension of a field $F$. Let $\alpha \in E$ be algebraic over $F$. Then $F(\alpha)$ is a vector space over $F$ and is spanned by $\{1,\alpha,\alpha^2,\ldots,\alpha^{n-1}\}$ where $n=\deg(\alpha, F)$.

**Definition 30.9**
A vector space is **finite dimensional** if it is spanned by a finite subset of its vectors.

**Example 30.10**
Example 30.7 shows that the vector space $\R^n$ defined in Example 30.2 is finite dimensional. $F[x]$ cannot be finite dimensional as given a finite subset $S$ of $F[x]$ and $p(x)$ its element of highest degree, $xp(x)$ cannot be expressed as a linear combination of $S$.

**Example 30.11**
Example 30.8 shows that $F(\alpha)$ is finite dimensional. If $\alpha$ were transcendental over $F$, $F(\alpha)$ would not be finite dimensional. (Proof omitted)

**Definition 30.12**
A subset $S$ of an $F$-vector space $V$ is **linearly independent** if for $a_i\in F$ and $v_i\in V$, $\sum_{i\in I}a_iv_i=0$ implies $a_i=0$ for all $i\in I$. Otherwise, it is **linearly dependent**. In other words, a subset is linearly independent if none of its elements can be expressed as a linear combination of the others.

**Example 30.13**
Observe that the subsets of $\R^n$ and $F[x]$ given in Example 30.7 are linearly independent. Observe that $(1,-1),(2,1),(-3,2)$ of $\R^2$ is linearly dependent: $7(1,-1)+(2,1)+3(-3,2)=(0,0)$.

**Example 30.14**
Let $E$ be an extension of a field $F$ with $\alpha\in E$ algebraic over $F$ of degree $n$. As mentioned in Example 30.8, $F(\alpha)$ is spanned by $\{\alpha^m\ |\ m\in\N, m<n\}$. $0=0+0\alpha+0\alpha^2+\cdots+0\alpha^{n-1}$, and by Theorem 29.18 this representation of $0$ is unique, so it is the only representation of $0$. This means that the subset is linearly independent, and by the next definition it is a basis.

**Definition 30.15**
A linearly independent spanning subset is a **basis**.

**Lemma 30.16**
Let $V$ be a vector space over a field $F$. Let $\alpha,\beta_i,\gamma_j\in V$ for $i,j\in\N,i<n,j<m$. If $\alpha$ is a linear combination of the $\beta_i$ and each $\beta_i$ is a linear combination of the $\gamma_j$, then $\alpha$ is a linear combination of the $\gamma_j$.

**Theorem 30.17**
In a finite dimensional vector space, every spanning subset contains a basis.

**Corollary 30.18**
A finite dimensional vector space has a finite basis.

**Theorem 30.19**
Any linearly independent subset can be enlarged to a basis. Further, no linearly independent subset is larger than a basis.

**Corollary 30.20**
Any two bases are of the same size.

**Definition 30.21**
The **dimension** of a vector space is the size of its bases (independent of the choice of base, as shown earlier).

**Example 30.22**
Example 30.14 shows that the dimension of $F(\alpha)$ as an $F$-vector space is $\deg(\alpha, F)$.

**Theorem 30.23**
Let $E$ be an extension of a field $F$ with $\alpha\in E$ algebraic over $F$ of degree $n$. $E$ as an $F$-vector space is of dimension $n$, with $\{\alpha^i\ |\ i\in\N,i<n\}$ as a suitable basis. Further, every $\beta\in F(\alpha)$ is algebraic over $F$ and $\deg(\beta,F)\leq\deg(\alpha,F)$.
# Section 31
**Definition 31.1**
An extension $E$ of a field $F$ is an **algebraic extension** if every element of $E$ is algebraic over $F$.

**Definition 31.2**
If an extension $E$ of a field $F$ is a vector space of dimension $n$ over $F$, then $E$ is a **finite extension of degree $n$ over $F$**. We denote $n$ by $[E:F]$.

**Theorem 31.3**
A finite extension is an algebraic extension.
Proof idea: A linear combination of $\alpha^i$ is a polynomial

**Theorem 31.4**
For fields $K\geq E\geq F$, $[K:F]=[K:E][E:F]$

**Corollary 31.6**
$[F_r:F_1]=[F_r:F_{r-1}][F_{r-1}:F_{r-2}]\cdots[F_2:F_1]$

**Corollary 31.7**
For fields $E\geq F$, $\alpha\in E$ algebraic over $F$, and $\beta\in F(\alpha)$, we have $\deg(\beta,F)\ |\ \deg(\alpha, F)$.

**Theorem 31.11**
For fields $E\geq F$, $E$ is a finite extension of $F$ iff $E=F(\alpha_1,\ldots,\alpha_n)$ for a finite number of $\alpha_i$.

**Theorem 31.12**
Let $E\geq F$ be fields. $\bar{F}_E=\{\alpha\in E\ |\ \alpha \text{ is algebraic over } F\}$ is a subfield, the **algebraic closure of $F$ in $E$**.

**Corollary 31.13**
The algebraic numbers form a field.
Proof: The set is the algebraic closure of $\Q$ in $\C$, which is a field.

**Definition 31.14**
A field $F$ is **algebraically closed** if all nonconstant polynomials in $F[x]$ have a zero in $F$.

**Theorem 31.15**
A field $F$ is algebraically closed iff all polynomials in $F[x]$ factor into linear factors.

**Corollary 31.16**
An algebraically closed field has no proper algebraic extensions.

**Theorem 31.17**
Every field $F$ has an **algebraic closure** $\bar{F}$, an algebraic extension of $F$ that is algebraically closed.
Proof idea: Zorn's lemma

**Theorem 31.18 (Fundamental Theorem of Algebra)**
$\C$ is algebraically closed.
Proof idea: Liouville's theorem in complex analysis

**Lemma 31.21 (Zorn's Lemma)**
TODO

**Theorem 31.22**
TODO
Proof idea: Construct a poset of algebraic extensions of $F$, construct an upper bound for any chain.

