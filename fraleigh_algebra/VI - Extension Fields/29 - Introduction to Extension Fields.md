**Exercise 1**

$1+\sqrt{2}=x$

$\sqrt{2}=x-1$

$2=(x-1)^2=x^2-2x+1$

$0=x^2-2x-1$



**Exercise 2**

$x=\sqrt{2}+\sqrt{3}$

$x^2=(\sqrt{2}+\sqrt{3})^2$

$x^2=2+2\sqrt{6}+3$

$x^2-5=2\sqrt{6}$

$(x^2-5)^2=x^4-10x^2+25=24$

$x^4-10x^2+1=0$



**Exercise 3**

$x=1+i$

$x-1=i$

$(x-1)^2=x^2-2x+1=-1$

$x^2-2x+2=0$



**Exercise 4**

$x=\sqrt{1+\sqrt[3]{2}}$ 

$x^2=1+\sqrt[3]{2}$

$x^2-1=\sqrt[3]{2}$

$(x^2-1)^3=x^6-3x^4+3x^2-1=2$

$x^6-3x^4+3x^2-3=0$



**Exercise 5**

$x=\sqrt{\sqrt[3]{2}+i}$

$x^2=\sqrt[3]{2}+i$

$x^2-i=\sqrt[3]{2}$

$(x^2-i)^3=x^6-3ix^4-3x^2+i=2$

$x^6-3x^2-2=3ix^4+i$

$x^6-3x^2-2=3ix^4+i$

$(x^6-3x^2-2)^2=(3ix^4+i)^2$

$x^{12}+9x^4+4-6x^8-4x^6+12x^2=-9x^8-6x^4-1$

$x^{12}+3x^8-4x^6+3x^4+12x^2+5=0$



**Exercise 6**

$x=\sqrt{3+\sqrt{6}}$

$x^2=3+\sqrt{6}$

$x^2-3=\sqrt{6}$

$(x^2-3)^2=x^4-6x^2+9=6$

$x^4-6x^2+3=0$

This polynomial is irreducible as seen by checking the Eisenstein criterion for $p=3$. This shows that $\deg(\sqrt{3+\sqrt{6}},\Q)=4$.



**Exercise 7**

$x=\sqrt{\frac{1}{3}+\sqrt{7}}$

$x^2=\frac{1}{3}+\sqrt{7}$

$3x^2=1+3\sqrt{7}$

$3x^2-1=3\sqrt{7}$

$(3x^2-1)^2=9x^4-6x^2+1=63$

$9x^4-6x^2-62=0$

This polynomial is irreducible as seen by checking the Eisenstein criterion for $p=2$. This shows that $\deg(\sqrt{\frac{1}{3}+\sqrt{7}},\Q)=4$.



**Exercise 8**

$x=\sqrt{2}+i$

$x-\sqrt{2}=i$

$x^2-2\sqrt{2}x+2=-1$

$x^2+3=2\sqrt{2}x$

$x^4+6x^2+9=8x^2$

$x^4-2x^2+9=0$

By a variety of methods (calculus, drawing a graph, etc) we see that $x^4-2x^2+9=0$ has no real roots, meaning by the factor theorem it has no linear factors in $\Q$. If it is reducible, it must factor into two quadratic factors. By Theorem 23.11 it must also factor into two quadratic factors in $\Z$. $pq=1$ in $\Z$ only for $p=q=\pm 1$, so $x^4-2x^2+9=(x^2+ax+b)(x^2+cx+d)$, leading to that $a+c=0$, $ac+b+d=-2$, $ad+bc=0$, $bd=9$. We have $a=-c$, so $ad-ab=0$ and $ad=ab$ then $d=b$. From $bd=9$ we have $b=d=\pm 3$. $a^2-2b=2$, For $b=3$, we have $a^2-6=2$ so $a^2=8$ which is not possible in $\Z$. For $b=-3$, we have $a^2+6=2$ so $a^2=-4$ which is also not possible in $\Z$, eliminating both possibilities and showing that $x^4-2x^2+9$ is irreducible and that $\deg(x^4-2x^2+9, \Q)=4$.



**Exercises 9-16**

$\deg(i, \Q)=2$

$\deg(1+i, \R)=2$

transcendental

$\deg(\sqrt{\pi}, \R)=1$

$\deg(\sqrt{\pi}, \Q(\pi))=2$

transcendental

$\deg(\pi^2, \Q(\pi))=2$

$\deg(\pi^2, \Q(\pi^3))=3$



**Exercise 17**

$x^2+x+1=0(x-\alpha)+x^2+x+1$

$x^2+x+1=x(x-\alpha)+(1+\alpha)x+1$

$x^2+x+1=(x+(1+\alpha))(x-\alpha)$



**Exercise 18**

a)

Since $x^2+1$ is of degree 2, by Theorem 23.10 we can just check the zeros in $\Z_3$. By a simple computation we see that there are none, showing that $x^2+1$ is irreducible over $\Z_3$.

b)

$\alpha^2=2$, will not write out 162 table entries.



**Exercise 19-22**

"...in $F[x]$" should be added to the end.

Correct.

Only the leading coefficient must be 1, not all coefficients.

False, $\alpha=1$ satisfies the condition for all extension fields. A correct definition would be "iff there exists $\alpha\in E$ s.t. $E$ is the smallest field containing both $\alpha$ and $F$."



**Exercise 23**

a. T

b. T

c. T

d. T

e. F (the fields are of different characteristic)

f. T

g. F

h. T

i. F

j. T



**Exercise 24**

a)

$\Q(\pi^3)$

b)

$\Q(e^{10})$



**Exercise 25**

a)

Obvious, omitted.

b)

TODO



**Exercise 26**

TODO



**Exercise 27**

Because $\irr(\alpha, F)$ is the monic polynomial of _minimal_ degree that has a zero at $\alpha$. Irreducibility is a consequence of this. (proof omitted)



**Exercise 28**

For a field $F$ and an irreducible polynomial $p(x)$, $F[x]/\lrangle{p(x)}$ is a field that contains both a zero of $p(x)$ and the entirety of $F$. It is a field because $p(x)$ is irreducible, and $x$ is a zero of $p(x)$, as $p(x)+\lrangle{p(x)}=0+\lrangle{p(x)}$.



**Exercise 29**

Let $p(x)\in F(\beta)[x]$ be a nonzero polynomial with a zero at $\alpha$. Since every element of $F(\beta)$ can be represented as $a(\beta)b(\beta)^{-1}$ for $a(x),b(x)\in F[x]$, we have $p(x)=\sum_{i\in\N}a_i(\beta)b_i(\beta)^{-1}x^i$ for $a_i(x),b_i(x)\in F[x]$. Since this polynomial has a zero at $\alpha$, we have $p(\alpha)=\sum_{i\in\N}a_i(\beta)b_i(\beta)^{-1}\alpha^i=0$. Multiplying both sides by the LCM of all the $b_i$, we have $\sum_{i\in\N}c_i(\beta)\alpha^i=0$ for $c_i(x)\in F[x]$. At least one of the $c_i$ must be nonconstant since if all of them were constant then all $c_i(x)\in F$ giving us a nonconstant polynomial in $F[x]$ with a zero at $\alpha$ contradicting that $\alpha$ is transcendental. Expanding the $c_i(x)$, we have  $\sum_{i\in\N}\sum_{j\in\N}f_{i,j}\beta^{j}\alpha^i=0$ for $f_{i,j}\in F$ where $f_{i,j}\neq 0$ for some $i,j\in\N$ s.t. $j>0$. Rerranging, we have $\sum_{j\in\N}(\sum_{i\in\N}f_{i,j}\alpha^i)\beta^{j}=0$. Naming $\sum_{i\in\N}f_{i,j}\alpha^i=d_j(x)\in F[x]$, we have $\sum_{j\in\N}d_j(\alpha)\beta^{j}=0$. This is a nonconstant polynomial since there is a nonzero $f_{i,j}$ for some $j>0$ so there is a nonzero $d_j(x)$ for some $j>0$. Since $d_j(\alpha)\in F(\alpha)$, we have a nonconstant polynomial in $F(\alpha)[x]$ with a zero at $\beta$, showing that $\beta$ is algebraic over $F(\alpha)$.



**Exercise 30**

By Theorem 29.18, every element of $F(\alpha)$ can be expressed uniquely as $\sum_{i=0}^{n-1}f_i\alpha^i$. There are $q$ choices for each $f_i$, of which there are $n$. Therefore, combinatorially, the total number of configurations is $q^n$, since the expressions are unique.



**Exercise 31**

a.

Consider $p(x)=x^3+x^2-x+1$. Since $a^3\equiv a \mod 3$ by Fermat's theorem, we have $p(a)=a+a^2-a+1=a^2+1$ for all $a\in \Z_3$. $a=0$ gives us $1$, $a=1$ gives us $2$, $a=2$ gives us $2$, showing that $p(a)$ is nonzero for all possible $a$ and the degree is 3, by Theorem 23.10 we see that $p(x)$ is irreducible.

b.

By Kronecker's theorem, there exists an extension $E$ of $\Z_3$ s.t. there exists $\alpha\in E$ that is a zero of $p(x)=x^3+x^2-x+1$. Since by (a) $p(x)$ is irreducible, we have $\deg(\alpha,\Z_3)=3$. $|\Z_3|=3$, and by Exercise 30, we have $|F(\alpha)|=3^3$.



**Exercise 32**

a.

Let $f:\Z_p\to\Z_p$ given by $f(x)=x^2$. Since $1^2=(p-1)^2=1$, $f(1)=f(p-1)=1$ ($1\neq p-1$ since $p\neq 2$) showing that $f$ is _not_ injective. Since the cardinality of the domain and the codomain are equal, it must also be that $f$ is not surjective, meaning that there is at least one element $x\in \Z_p$ for which there exists no $y$ s.t. $f(y)=y^2=x$, completing the proof.

b.

For $p=2$, a field of order $4$ is already given in the book. For $p\neq 2$, using (a) we see that there exists $a\in\Z_p$ s.t. $p(x)=x^2-a$ has no zeros in $\Z_p$. By Kronecker's theorem, we can construct an extension $E$ of $\Z_p$ s.t. there exists $\alpha\in E$ s.t. $p(\alpha)=0$. Since $p(x)$ is irreducible over $\Z_p$ because it is of degree 2 and Theorem 23.10, $\deg(\alpha, \Z_p)=2$ so by Exercise 30 we have $|F(\alpha)|=p^2$, showing that $F(\alpha)$ is a suitable finite field.



**Exercise 33**

Let $a\in F(\alpha)$ s.t. $a\notin F$. For the sake of contradiction assume that $a$ is algebraic over $F$, meaning there exists a nonzero polynomial $p(x)\in F[x]$ with a zero at $a$. $a=q(\alpha)r(\alpha)^{-1}$ for some $q(x),r(x)\in F[x]$. $p(x)=\sum_{i=0}^{n}f_iq(\alpha)^ir(\alpha)^{-i}=0$ for $f_i\in F$ where $n$ is the degree of $p(x)$. Multiplying both sides by $r(x)^n$ we have $\sum_{i=0}^{n}f_iq(\alpha)^ir(\alpha)^{n-i}=0$. Since $q(x)^ir(x)^{n-i}\in F[x]$, we have $\sum_{i=0}^{n}f_i\sum_{j\in\N}g_{i,j}\alpha^j=0$ for $g_{i,j}\in F$. Rearranging, we have $\sum_{j\in\N}(\sum_{i=0}^{n}g_{i,j}f_i)\alpha^j=0$. Since $\sum_{i=0}^{n}g_{i,j}f_i\in F$, this gives us a polynomial in $F$ with a zero at $\alpha$, contradicting our assumption that $\alpha$ is transcendental over $F$. (Note my poor choice of variable name, $a$ and $\alpha$ can be confusing.)



**Exercise 34**

Consider $p(x)=x^3-2\in\Q[x]$. Since $p(x)$ is irreducible, $\deg(\sqrt[3]{2},\Q)=3$. By Theorem 29.18, the elements of $\Q(\sqrt[3]{2})$ are uniquely expressible as $a+b\sqrt[3]{2}+c(\sqrt[3]{2})^2$ for $a,b,c\in \Q$, and all such expressions are elements of $\Q(\sqrt[3]{2})$. This gives us a subfield of $\R$ equal to the given set, completing the proof.



**Exercise 35**

$8=2^3$

$16=2^4$



Since $5$ is a prime, by (b) of Exercise 32 there exists a field of $5^2=25$ elements.



**Exercise 36**

Consider any nonzero element $a$ of $F$. Since $F$ is finite, let $n$ be the finite order of $a$ in $F^*$. $a^n=1$, so $a^n-1=0$. This gives us that $p(x)=x^n-1\in\Z_p[x]$ has a zero at $a$. This shows that $a$ is algebraic over $\Z_p$.



**Exercise 37**

Let $F$ be a finite field of characteristic $p$. $F$ is an extension of its prime field $\Z_p$. By Exercise 36, every element in $F$ is algebraic over $\Z_p$, meaning that all simple extensions of $\Z_p$ are finite. (Not sure how to word this, but they're pretty much just trivialities.) We can obtain $F$ from a finite number of simple extensions of $\Z_p$, each of which apply a power to the order, meaning that $|F|$ is a power of a prime.
