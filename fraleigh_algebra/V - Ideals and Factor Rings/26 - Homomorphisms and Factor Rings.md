**Exercise 1**

$\phi((n,m))=(n,m)$

$\phi((n,m))=(n,0)$

$\phi((n,m))=(0,n)$

$\phi((n,m))=(0,0)$



**Exercise 2**

$2n$ for all positive odd $n$.



**Exercise 3**

$\mathbb{Z}_{12}/\langle1\rangle=\{0\}$

$\mathbb{Z}_{12}/\langle2\rangle=\mathbb{Z}_2$

$\mathbb{Z}_{12}/\langle3\rangle=\mathbb{Z}_3$

$\mathbb{Z}_{12}/\langle4\rangle=\mathbb{Z}_4$

$\mathbb{Z}_{12}/\langle6\rangle=\mathbb{Z}_6$

$\mathbb{Z}_{12}/\langle12\rangle=\mathbb{Z}_{12}$



**Exercise 4**

```

+|0246

-+----

0|0246

2|2460

4|4602

6|6024



x|0246

-+----

0|0000

2|0404

4|0000

6|0404

```

$2\mathbb{Z}/8\mathbb{Z}$ is not isomorphic to $\mathbb{Z}_4$ as the latter has unity and the former does not.



**Exercise 5**

It should be added that $\phi$ has to be surjective.



**Exercise 6**

Correct, but "additive subgroup of $R$" would be nicer.



**Exercise 7**

Correct.



**Exercise 8**

$\delta$ satisfies the additive condition - $\delta(f+g)=(f+g)'=f'+g'=\delta(f)+\delta(g)$ - because differentiation is linear. However, it does not satisfy the multiplicative condition. Let $f:\mathbb{R}\to\mathbb{R}$ s.t. $f(x)=x$ $\delta(ff)(x)=2x\neq1=1(1)=\delta(f)\delta(f)$. The connection with Example 26.12 is that in both instances, the maps satisfy the additive condition but fail at the multiplicative condition.



**Exercise 9**

$\phi:\mathbb{Z}\to\mathbb{Z}\times\mathbb{Z}$ given by $\phi(x)=(x,0)$ is a viable example.



**Exercise 10**

a. T

b. F (into ideals of $\phi[R]$, not necessarily $R'$.)

c. T

d. F

e. T

f. F

g. T

h. T

i. F ($\mathbb{Z}$ is not an ideal in $\mathbb{R}$ despite containing $1$)

j. T



**Exercise 11**

No. $R/\{0\}$ is simply $R$, and $R/R$ is simply $\{0\}$. This gives us no information about the structure of $R$.



**Exercise 12**

$\mathbb{Z}$ is a non-field integral domain, and $\mathbb{Z}/p\mathbb{Z}$ for any prime $p$ is a field.



**Exercise 13**

$\mathbb{Z}$ is a non-field integral domain, and $\mathbb{Z}/4\mathbb{Z}$ has divisors of zero. $(2+4\mathbb{Z})(2+4\mathbb{Z})=4+4\mathbb{Z}=4\mathbb{Z}$. ($\mathbb{Z}/c\mathbb{Z}$ for any composite $c$ works.)



**Exercise 14**

$\mathbb{Z}_4$ is a ring with divisors of zero ($2(2)=0$), and $\mathbb{Z}_4/\langle2\rangle$ is isomorphic to $\mathbb{Z}_2$, an integral domain. (Haven't found an example where the integral domain is not a field)



**Exercise 15**

$\langle(1,1)\rangle$ is a subring of $\mathbb{Z}\times\mathbb{Z}$ but is not an ideal. $(1,1)(0,1)=(0,1)\notin\langle(1,1)\rangle$.



**Exercise 16**

a.

Because elements of $R/N$ should be denoted $r+N$. $r\in R/N$ makes no sense, as there is no indication that the specified element is a coset.

b.

"Then $(r+N)(s+N)=(s+N)(r+N)$ for all $r,s\in R$."

c.

Assume that $R/N$ is commutative. For all $r,s\in R$, we have $(r+N)(s+N)=(s+N)(r+N)$. Since multiplication of additive cosets of rings by representatives is well-defined, we have $rs+N=sr+N$. This means that for all $n_1\in N$, there exists $n_2$ s.t. $rs+n_1=sr+n_2$. Rearranging, we have $rs-sr=n_2-n_1$, which is in $N$ since $N$ is a subring. This shows that $rs-sr\in N$ for all $r,s\in R$ if $R/N$ is commutative.



Assume that $rs-sr\in N$ for all $r,s\in R$. We need to show that $(r+N)(s+N)=(s+N)(r+N)$. It suffices to show that $rs+N=sr+N$. Starting with $rs-sr+N=N$, rearranging we get $rs+N=N+sr$, completing the proof.



**Exercise 17**

$(a+b\sqrt{2})-(c+d\sqrt{2})=(a-c)+(b-d)\sqrt{2}\in R$ showing that $R$ is closed under subtraction. $(a+b\sqrt{2})(c+d\sqrt{2})=(ac+2bd)+(cb+ad)\sqrt{2}\in R$ showing that $R$ is closed under multiplication. Since $R$ is a subset of $\mathbb{R}$, these properties show that $R$ is a subring of $\mathbb{R}$.

$\begin{bmatrix}a&2b\\ b&a\end{bmatrix}-\begin{bmatrix}c&2d\\ d&c\end{bmatrix}=\begin{bmatrix}a-c&2(b-d)\\ b-d&a-c\end{bmatrix}\in R'$, showing that $R'$ is closed under subtraction.

$\begin{bmatrix}a&2b\\ b&a\end{bmatrix}\begin{bmatrix}c&2d\\ d&c\end{bmatrix}=\begin{bmatrix}ac+2bd&2(ad+bc)\\ ad+bc&ac+2bd\end{bmatrix}\in R'$, showing that $R'$ is closed under multiplication. Since $R'\subseteq M_2(\mathbb{Z})$, we see that $R'$ is a subring of $M_2(\mathbb{Z})$.

It is clear by inspection that $\phi$ is a bijection. Additive condition: $\phi((a+b\sqrt{2})+(c+d\sqrt{2}))=\phi((a+c)+(b+d)\sqrt{2})$

$=\begin{bmatrix}a+c&2(b+d)\\ b+d&a+c\end{bmatrix}=\begin{bmatrix}a&2b\\ b&a\end{bmatrix}+\begin{bmatrix}c&2d\\ d&c\end{bmatrix}$

$=\phi(a+b\sqrt{2})+\phi(c+d\sqrt{2})$

Multiplicative condition: $\phi((a+b\sqrt{2})(c+d\sqrt{2}))=\phi((ac+2bd)+(ad+bc)\sqrt{2})=$

$=\begin{bmatrix}ac+2bd&2(ad+bc)\\ ad+bc&ac+2bd\end{bmatrix}=\begin{bmatrix}a&2b\\ b&a\end{bmatrix}\begin{bmatrix}c&2d\\ d&c\end{bmatrix}$

$=\phi(a+b\sqrt{2})\phi(c+d\sqrt{2})$

showing that $\phi$ is an isomorphism.



**Exercise 18**

Let $\phi : F\to R$ be a homomorphism. It suffices to show that if $\mathrm{Ker}(\phi)$ has any nonzero element of $F$ then $\phi(x)=0'$ for all $x\in F$.

Let $a\neq 0$ s.t. $\phi(a)=0'$. Let $b\neq 0$ be any element of $F$. $\phi(a)=0'$, so $\phi(a)\phi(a^{-1}b)=0'\phi(a^{-1}b)$, giving us $\phi(b)=0'$, completing the proof.



**Exercise 19**

From Exercise 49 of Section 13 we already know that the composition of two homomorphisms between groups is again a homomorphism. The same computation works for both addition and multiplication, showing that $\psi\phi$ is a homomorphism.



**Exercise 20**

$\phi_p(a+b)=(a+b)^p=\sum_{i=0}^{p}\binom{p}{i}\cdot a^ib^{p-i}$

Consider any $i$ s.t. $0<i<p$. $\binom{p}{i}=\frac{p!}{i!(p-i)!}$. The numerator is divisible by $p$, and the denominator is not. Therefore, $\binom{p}{i}$ is divisible by $p$. This means that all terms of $\sum_{i=0}^{p}\binom{p}{i}\cdot a^ib^{p-i}$ s.t. $0<i<p$ is $0$ because $R$ has characteristic $p$ and $\binom{p}{i}\cdot a^ib^{p-i}=kp\cdot a^ib^{p-i}=0$.

$\phi_p(a+b)=(a+b)^p=\sum_{i=0}^{p}\binom{p}{i}\cdot a^ib^{p-i}=a^p+b^p$

$=\phi_p(a)+\phi_p(b)$.

As for the multiplicative condition: $\phi_p(ab)=(ab)^p=a^pb^p$ since $R$ is commutative, $=\phi_p(a)\phi_p(b)$.



**Exercise 21**

The hypothesis is equivalent to that there exists $x\in R$ s.t. $\phi(x)\neq 0'$. $\phi(x)\phi(1)=\phi(x1)=\phi(x)\neq 0'$, so since $R'$ has no zero divisors, $\phi(1)\neq 0'$ as well. Now we will prove that $\phi(1)$ is identity for $R'$.

Let $r'$ be any nonzero element of $R'$.

$\phi(1)r'=\phi(1)r'$

$\phi(1(1))r'=\phi(1)r'$

$\phi(1)\phi(1)r'=\phi(1)r'$

Since $R'$ has no zero divisors, the cancellation laws hold.

$\phi(1)r'=r'$, showing that $\phi(1)$ is unity, completing the proof.



**Exercise 22**

a.

We will show that for any $n'\in\phi[N]$ and $r'\in\phi[R]$, $n'r'$ and $r'n'$ are elements of $\phi[N]$. There must be $n\in N$ and $r\in R$ s.t. $\phi(n)=n'$ and $\phi(r)=r'$. $n'r'=\phi(n)\phi(r)=\phi(nr)$. Since $N$ is an ideal in $R$, $nr\in N$. Therefore, $n'r'=\phi(nr)\in\phi[N]$. Likewise, $r'n'=\phi(rn)\in\phi[N]$.

b.

Consider $\phi:\mathbb{R}\to\mathbb{C}$ given by $\phi(x)=x$. $\mathbb{R}$ is an ideal of itself, so we can choose $R'=\mathbb{C}$ and $R=N=\mathbb{R}$. $\phi[R]=\mathbb{R}$, but this is not an ideal in $\mathbb{C}$ since $1i=i\notin\mathbb{R}$.

c.

For convenience, label $N=\phi^{-1}[N']$.

Being an ideal of $R'$ is also being an ideal for $\phi[R]$ since $\phi[R]\subseteq R'$. We can consider $N'$ an ideal of $\phi[R]$. We will show that for any $n\in N$ and $r\in R$ , $nr\in N$ and $rn\in N$. Since $n\in N=\phi^{-1}[N']$, it must be that $\phi(n)\in N'$. Since $N'$ is an ideal in $\phi[R]$, $\phi(n)\phi(r)\in N'$. $\phi(nr)\in N'$, and by extension, $nr\in N$. Likewise, $\phi(r)\phi(n)=\phi(rn)\in N'$ and $rn\in N$, completing the proof.



**Exercise 23**

To show that $N_S$ is an ideal in $F[x_1,\cdots,x_n]$, we will show that for any $n\in N_S$ and $f\in F[x_1,\cdots,x_n]$  that $nf$ and $fn$ are in $N_S$. For any $(a_1,\cdots,a_n)\in S$, $(nf)(a_1,\cdots,a_n)=n(a_1,\cdots a_n)f(a_1,\cdots a_n)$. Since $n\in N_S$, $n(a_1,\cdots a_n)=0$, so $n(a_1,\cdots a_n)f(a_1,\cdots a_n)=0=(nf)(a_1,\cdots a_n)$, showing that $nf\in N_S$. The same procedure can be applied for $fn$, completing the proof.



**Exercise 24**

Let $F$ be a field, and $F/N$ a factor ring. $N$ should be an ideal of $F$. $N$ is either the trivial ideal or not. In the case that $N$ is trivial, $F/N=F$, meaning it suffices to show that $N=F$ if $N$ is nontrivial.

Let $0\neq a\in N$. Since $F$ is a field, $a^{-1}$ exists. Let $f$ be any element of $F$. $a^{-1}f\in F$, so $a(a^{-1}f)\in N$ since $N$ is an ideal in $F$. This simply reduces to $f\in N$ for all $f$, showing that $F=N$, completing the proof.



**Exercise 25**

Consider the coset $1+N$. Let $a+N$ be any element of $R/N$. $(a+N)(1+N)=a1+N=a+N$, showing that $(1+N)$ is unity for $R/N$. 



**Exercise 26**

For any $i\in I_a$ and $r\in R$, $a(ir)=(ai)r=0r=0$, showing that $ir\in I_a$ since $a(ir)=0$. Since $R$ is commutative, the same follows for $ri$.



**Exercise 27**

Let $N$ and $M$ be ideals of a ring $R$. Let $a$ be any element of $N\cap M$, and $r$ any element of $R$. Since $a\in N$ and $N$ is an ideal of $R$, $ar\in N$. Likewise, $a\in M$ so $ar\in M$. $ar\in N\cap M$, showing that $N\cap M$ is an ideal of $R$.



**Exercise 28**

$\phi_*:R/N\to R'/N'$ given by $\phi_*(r+N)=\phi(r)+N'$ satisfies the additive condition by Exercise 39 of Section 14. This leaves the multiplicative condition.

$\phi_*((a+N)(b+N))=\phi_*(ab+N)=\phi(ab)+N'$

$=\phi(a)\phi(b)+N'=(\phi(a)+N')(\phi(b)+N')$, completing the proof.

TODO: make proof better, it should be shown that $\phi_*$ is well-defined



**Exercise 29**

Since $u$ is a unit, there must be $v\in R$ s.t. $uv=1$. $\phi(u)\phi(v)=\phi(uv)=\phi(1)$, so if $\phi(1)$ is unity in $R'$ then $\phi(v)$ is the inverse of $\phi(u)$, showing that $\phi(u)$ is a unit.



TODO: This proof doesn't show that $\phi(1)$ is unity in $R'$.



**Exercise 30**

Let $N$ be the nilradical of $R$. Let any $n\in N$ and $r\in R$. Since $n$ is nilpotent, let $a\in\mathbb{Z}^+$ be s.t. $n^a=0$. Since $R$ is commutative, $(nr)^a=n^ar^a$. $n^a=0$ so $n^ar^a=0r^a=0$, showing that $(nr)^a=0$ so $nr$ is nilpotent, meaning $nr\in N$ and that $N$ is an ideal. ($rn$ need not be checked since the ring is commutative.)



**Exercise 31**

The nilradical of $\mathbb{Z}_{12}$ is $\langle 6\rangle$. For $\mathbb{Z}$, $\{0\}$. For $\mathbb{Z}_{32}$, $\langle 2\rangle$.



Remark: For any $\mathbb{Z}_n$, its nilradical is $\langle x\rangle$ where $x$ is the product of the unique prime divisors of $n$.



**Exercise 32**

Let $r+N\in R/N$. For $r+N$ to be nilpotent, it must be that for some $a\in\mathbb{Z}^+$, $(r+N)^a=0+N$. $(r+N)^a=r^a+N$ since multiplication of cosets by representatives is well defined, and for $r^a+N$ to be $0+N$, $r$ must be nilpotent. This means that $r\in N$, so $r+N=0+N$. This means that any nilpotent element of $R/N$ is $0+N$, so the nilradical of $R/N$ is the trivial ideal.



**Exercise 33**

Since $R/N$ is its own nilradical, there exists $a\in\mathbb{Z}^+$ for any $r+N\in R/N$ s.t. $(r+N)^a=0+N$. $r^a+N=0+N$, meaning that $r$ is nilpotent. Since every element of $R$ belongs to at least one coset of $N$, this means that every element of $R$ is nilpotent, showing that $R$ is its own nilradical.



TODO: improve proofs for last few exercises, $r^a$ need not $=0$ for $r$ to be nilpotent!!!



**Exercise 34**

Let $n\in\sqrt{N}$ and $r\in R$. There exists $a\in\mathbb{Z}^+$ s.t. $n^a\in N$. $(nr)^a=n^ar^a$ by commutativity and since $n^a\in N$ and $N$ is an ideal, $n^ar^a\in N$ also. This means that $(nr)^a\in N$, showing that $nr=rn\in\sqrt{N}$, meaning that $\sqrt{N}$ is an ideal of $R$.



**Exercise 35**

a.

$\langle4\rangle$ is an ideal of $\mathbb{Z}$. $2^2=4$, so $2\in \sqrt{\langle4\rangle}$, meaning that for $N=\langle 4\rangle$ of $R=\mathbb{Z}$, $\sqrt{N}\neq N$.

b.

$R=\mathbb{Z}$, $N=\langle2\rangle$. $\langle 2\rangle$ are the even integers, and the power of an odd integer cannot be even, showing that $\sqrt{N}=N$.



**Exercise 36**

If $r+N\in R/N$ is nilpotent, $(r+N)^a=0+N$ for some positive integer $a$. $r^a+N=0+N$, meaning that $r^a\in N$, showing $r\in\sqrt{N}$. Conversely, if $r^a\in N$, $r^a+N=0+N$, and since $r^a+N=(r+N)^a$, $r+N$ is nilpotent. This means that the nilradical of $R/N$ is precisely the $n+N$ for all $n\in\sqrt{N}$.



**Exercise 37**

That $\phi$ is a bijection between $\mathbb{C}$ and $\phi[\mathbb{C}]$ is obvious. It remains to show the additive and multiplicative conditions.

$\phi((a+bi)+(c+di))=\phi((a+c)+(b+d)i)=\begin{bmatrix}a+c&b+d\\ -b-d&a+c\end{bmatrix}$

$=\begin{bmatrix}a&b\\ -b&a\end{bmatrix}+\begin{bmatrix}c&d\\ -d&c\end{bmatrix}=\phi(a+bi)+\phi(c+di)$

showing the additive condition. For the multiplicative condition,

$\phi((a+bi)(c+di))=\phi((ac-bd)+(ad+bc)i)$

$=\begin{bmatrix}ac-bd&ad+bc\\ -ad-bc&ac-bd\end{bmatrix}=\begin{bmatrix}a&b\\ -b&a\end{bmatrix}\begin{bmatrix}c&d\\ -d&c\end{bmatrix}$

$=\phi(a+bi)\phi(c+di)$

completing the proof.



**Exercise 38**

a.

$\lambda_a(x+y)=a(x+y)=ax+ay=\lambda_a(x)+\lambda_a(y)$

b.

$\lambda_0$ is the identity, as shown by $(\lambda_0+\lambda_a)(x)=\lambda_0(x)+\lambda_a(x)=0x+ax=0+ax=ax=\lambda_a(x)$, i.e. $\lambda_0+\lambda_a=\lambda_a$.

$(\lambda_a-\lambda_b)(x)=\lambda_a(x)-\lambda_b(x)=ax-bx=(a-b)x=\lambda_{a-b}(x)$

showing that $\lambda_a-\lambda_b=\lambda_{a-b}$ meaning that $R'$ is closed under subtraction.

$(\lambda_a\lambda_b)(x)=\lambda_a(\lambda_b(x))=\lambda_a(bx)=a(bx)=(ab)x=\lambda_{ab}(x)$ showing that $\lambda_a\lambda_b=\lambda_{ab}$ meaning that $R'$ is closed under multiplication.

This completes the proof that $R'$ is a subring of $\mathrm{End}(\langle R,+\rangle)$.

c.

Let $\phi : R \to R'$ be given by $\phi(x)=\lambda_x$. It is obvious that $\phi$ is a bijection. It remains to show that $\phi$ preserves structure.

$\phi(a+b)=\lambda_{a+b}=\lambda_a+\lambda_b=\phi(a)+\phi(b)$

$\phi(ab)=\lambda_{ab}=\lambda_a\lambda_b=\phi(a)\phi(b)$

This shows that $\phi$ is an isomorphism, so $R$ and $R'$ are isomorphic.
