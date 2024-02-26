**Exercise 1**
$(x-a)\in P_{\mathrm{high}}$, therefore $a<x$.
If $i>j$ then $(x^i-x^j)\in P_{\mathrm{high}}$, therefore $x^j<x^i$ for $j<i$.
This gives $a<x<x^2<x^3<\ldots$

**Exercise 2**
$(x^j-x^i)\in P_{\mathrm{low}}$ for $j<i$, therefore $x^i < x^j$ for $i>j$.
$\ldots>x^{-2}>x^{-1}>x^0>x^1>x^2>\ldots$

**Exercise 3**
That ordering is defined such that $m+n\sqrt{2}$ is positive iff its conjugate $m-n\sqrt{2}$ is positive in $\mathbb{R}$. This means that an element is positive if $m$ and $-n$ are positive, or $m$ is positive and $m^2>2n^2$, or $-n$ is positive and $2n^2>m^2$.

**Exercises 4-9**
(i) acdeb (ii) dbaec
(i) acedb (ii) ecbad
(i) cabed (ii) ecabd
(i) dabce (ii) dceab
(i) eacbd (ii) cdaeb
(i) caedb (ii) ecbad

**Exercises 10-13**
bdace
TODO

**Exercise 14**
Because there is an ordering on $\mathbb{R}$, there are orderings on all subfields of $\mathbb{R}$, including the one described. For an isomorphism $\phi$ between two fields, Theorem 25.10 shows that if there is an ordering on one, the other can be ordered as well. The subfield of $\mathbb{C}$ described is isomorphic to an ordered field, meaning that that subfield can also be ordered. The subfield contains elements that are not of $\mathbb{R}$, showing that an ordered subfield of $\mathbb{C}$ can contain non-real numbers.

**Exercise 15**
a. T
b. F?
c. F
d. T
e. T
f. F
g. T
h. F
i. T
j. T

**Exercise 16**
$P_{\mathrm{high}}$ satisfies the property.

**Exercise 17**
$\phi((a+b\sqrt{2})+(c+d\sqrt{2}))=\phi((a+c)+(b+d)\sqrt{2})$
$=(a+c)-(b+d)\sqrt{2}=(a-b\sqrt{2})+(c-d\sqrt{2})$
$=\phi(a+b\sqrt{2})+\phi(c+d\sqrt{2})$

$\phi((a+b\sqrt{2})(c+d\sqrt{2}))=\phi((ac+2bd)+(ad+bc)\sqrt{2})$
$=(ac+2bd)-(ad+bc)\sqrt{2}=(a-b\sqrt{2})(c-d\sqrt{2})$
$=\phi(a+b\sqrt{2})\phi(c+d\sqrt{2})$

**Exercise 18**
$a=a-0$, $a\in P \implies (a-0)\in P$ and by the definition of $<$, $\implies 0<a$.

**Exercise 19**
Lemma A: The multiplicative inverse of a positive element is positive.
Proof: For $a\in P$, for the sake of contradiction assume that $-a^{-1}\in P$. By closure, $a(-a^{-1})\in P$, $-1\in P$. But $1\in P$, contradicting trichotomy. This shows that $a^{-1}\in P$.

Lemma B: For $b\in P$ and $ab\in P$, $a\in P$.
Proof: Since $b\in P$, $b^{-1}\in P$. By closure, $(ab)b^{-1}\in P$ so $a\in P$.

If $c=0$, $ac=bd=0$ and by Theorem 25.3, there are no zero divisors so $d=0$ ($b\neq0$ since $b\in P$). If one of $c,d$ are 0, then both of $c,d$ are 0. If neither are 0,
$ac=bd$
$b^{-1}a=dc^{-1}$
Since $b\in P$, by Lemma A $b^{-1}\in P$. By closure, $b^{-1}a\in P$. It must be that $dc^{-1}\in P$. By Theorem 25.3, $cc\in P$. By closure, $dc^{-1}cc\in P$, $dc\in P$, completing the proof.

**Exercise 20**
If $a<b$, then $b-a\in P$. $b=-(-b)$, so $-(-b)-a\in P$.
$(-a)-(-b)\in P$, so $-b<-a$, completing the proof.

**Exercise 21**
$0-a\in P$, $b-0\in P$. So, $-a\in P$, $b\in P$. By closure, $-ab\in P$.  $0-ab\in P$, $ab<0$.

**Exercise 22**
By Lemma A, $1/b\in P$. By closure, $a(1/b)\in P$, $a/b\in P$.

**Exercise 23**
$1-a\in P$, $a-0\in P$ i.e. $a\in P$. By Lemma A, $1/a\in P$. $(1-a)/a\in P$ by closure, $1/a-a/a\in P$ by distribution, $1/a-1\in P$ so $1<1/a$.

**Exercise 24**
$-1<a$, so by Exercise 20, $-a<1$. $a<0$, so by Exercise 20, $0<-a$. We have $0<-a<1$, so by Exercise 23 we have $1<-1/a$. By Exercise 20, $1/a<-1$, completing the proof.

**Exercise 25**
Closure:
Let $a',b'\in P'$. There must be $a,b$ s.t. $\phi(a)=a'$ and $\phi(b)=b'$. $ab\in P$ by closure in $R$, $\phi(ab)\in P'$, $\phi(a)\phi(b)=a'b'\in P'$. Likewise for addition.
Trichotomy:
Let $a'\in P'$. $\phi(a)=a'$.
$a\in P$ iff $a'\in P$. $a=0 \iff a'=0'$. $-a\in P$ iff $\phi(-a)=-a'\in P$.

**Exercise 26**
Closure:
Let $a,b\in P\cap S$. $a+b\in S$ because $S$ is a subring, $a+b\in P$ because of closure for $R$, so $a+b\in P\cap S$. Likewise for multiplication.
Trichotomy:
Let $a\in S$. $a\in P \iff a\in P\cap S$. $a=0\iff a=0$, $-a\in P \iff -a\in P\cap S$ because $-a\in S$.

**Exercise 27**
For all $a,b\in R$, define $P$ s.t. $a<b\implies b-a\in P$.
Closure:
Let $a,b\in P$. There must be $a_r,a_l,b_r,b_l\in R$ s.t. $b_l<b_r$ and $b_r-b_l=b$, $a_l<a_r$ and $a_r-a_l=a$.
$b_l<b_r$ so by isotonicity $0<b_r-b_l$ so $0<b$. Likewise for $a$, $0<a$. By isotonicity, multiplying both sides of $0<a$ by $b$ (since $0<b$), we have $0<ab$, showing that $ab-0=ab\in P$. Likewise, adding $b$ to both sides of $0<a$ by isotonicity we have $b<a+b$, and since we have $0<b$ we have $0<a+b$ by transitivity, showing that $a+b\in P$.
Trichotomy:
