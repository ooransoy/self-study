**Exercises 1-4**

$x^6+3x^5+4x^2-3x+2 \mod 7$

$=(x^2+2x-3)(x^4)+(x^5+3x^4+4x^2-3x+2)$

$=(x^2+2x-3)(x^4+x^3)+(x^4+3x^3+4x^2-3x+2)$

$=(x^2+2x-3)(x^4+x^3+x^2)+(x^3+7x^2-3x+2)$

$=(x^2+2x-3)(x^4+x^3+x^2+x)+(5x^2+2)$

$=(x^2+2x-3)(x^4+x^3+x^2+x+5)+(-10x+17)$

$=(x^2+2x-3)(x^4+x^3+x^2+x+5)+(4x+3)$



$x^6+3x^5+4x^2-3x+2 \mod 7$

$=(3x^2+2x-3)(5x^4)+(x^4+4x^2-3x+2)$

$=(3x^2+2x-3)(5x^4+5x^2)+(4x^3-2x^2-3x+2)$

$=(3x^2+2x-3)(5x^4+5x^2+6x)+(x+2)$



$x^5-2x^4+3x-5 \mod 11$

$=(2x+1)(6x^4)+(3x^4+3x-5)$

$=(2x+1)(6x^4+7x^3)+(4x^3+3x-5)$

$=(2x+1)(6x^4+7x^3+2x^2)+(9x^2+3x-5)$

$=(2x+1)(6x^4+7x^3+2x^2+10x)+(4x-5)$

$=(2x+1)(6x^4+7x^3+2x^2+10x+2)+(4)$



$x^4+5x^3-3x^2 \mod 11$

$=(5x^2-x+2)(9x^2)+(3x^3+x^2)$

$=(5x^2-x+2)(9x^2+5x)+(6x^2+x)$

$=(5x^2-x+2)(9x^2+5x+10)+(2)$



**Exercises 5-8**

$\langle 2\rangle=\{2,4,3,1\}$

$\langle 3\rangle=\{3,4,2,1\}$



$\langle 3\rangle=\{3, 2, 6, 4, 5, 1\}$

$\langle 5\rangle=\{5, 4, 6, 2, 3, 1\}$



$\langle 6\rangle=\{6, 2, 12, 4, 7, 8, 14, 16, 11, 15, 5, 13, 10, 9, 3, 1\}$

$\langle 6\rangle$, $\langle 12\rangle$, $\langle 7\rangle$, $\langle 14\rangle$, $\langle 11\rangle$, $\langle 5\rangle$, $\langle 10\rangle$, $\langle 3\rangle$



$\langle 5\rangle=\{5, 2, 10, 4, 20, 8, 17, 16, 11,$

$9, 22, 18, 21, 13, 19, 3, 15, 6, 7, 12, 14, 1\}$

$\langle 5\rangle$, $\langle 10\rangle$, $\langle 20\rangle$, $\langle 17\rangle$, $\langle 11\rangle$, $\langle 21\rangle$, $\langle 19\rangle$, $\langle 15\rangle$, $\langle 7\rangle$, $\langle 14\rangle$



**Exercise 9**

$1,2,3,4$ are the roots of the polynomial, therefore

$f(x)=(x-1)(x-2)(x-3)(x-4)$



**Exercise 10**

$2, 4, 6$ are the roots of the polynomial, therefore

$f(x)=(x-2)(x-4)(x-6)$



**Exercise 11**

$3, 4, 8$ are the roots of the polynomial, therefore

$f(x)=(x-3)(x-4)(x-8)$



**Exercise 12**

$f(x)=x^3+2x+3$ in $\mathbb{Z}_5[x]$ is not irreducible as $2$ is a root of the polynomial, meaning it has $(x-2)$ as a factor.

$f(x)=(x-2)(x^2+2x+1)$

The other factor is also obviously reducible.

$f(x)=(x-2)(x+1)(x+1)$



**Exercise 13**

Computing all possibilities, we see that $f(x)$ has no roots in $\mathbb{Z}_5$. Since $f(x)$ is cubic, if it were reducible it would have a linear factor, contradicting the absence of roots.



**Exercise 14**

$x^2+8x-2=0$

$x^2+8x=2$

$x^2+8x+16=18$

$(x+4)^2=18$

$x+4=\pm\sqrt{18}=\pm3\sqrt{2}$

$x=\pm3\sqrt{2}-4$

are the two zeros of $f(x)$. This means that $f(x)$ has no zeros in $\mathbb{Q}$. Since $f(x)$ is a quadratic, for it to be reducible it must have a linear factor $(x-\alpha)$ with $\alpha\in\mathbb{Q}$. This would mean a zero at $\alpha$, but neither zero of $f(x)$ is rational, which is a contradiction showing that $f(x)$ is irreducible over the rationals.

Over $\mathbb{R}$ and $\mathbb{C}$, $f(x)=(x-(3\sqrt{2}-4))(x-(-3\sqrt{2}-4))$, so $f(x)$ is reducible over both $\mathbb{R}$ and $\mathbb{C}$.



**Exercise 15**

$x^2+6x+12=0$

$x^2+6x=-12$

$x^2+6x+9=-3$

$(x+3)^2=-3$

$x+3=\pm\sqrt{-3}$

$x=\pm\sqrt{-3}-3$

showing that $f(x)$ has no zeros in $\mathbb{R}$. Using the argument in Exercise 14, this means that $f(x)$ is irreducible over $\mathbb{Q}$ and $\mathbb{R}$, and reducible over $\mathbb{C}$.



**Exercise 16**

Assume that $f(x)=x^3+3x^2-8$ is reducible over $\mathbb{Q}$. Since it has integer coefficients it should also be also reducible over $\mathbb{Z}$. Also, since it is a cubic, it must factor into a linear and a quadratic. Since the product of their leading coefficients is $1$ and since they're all integers, the leading coefficients must be both $1$ or both $-1$. If there is a factorization with both leading coefficients $-1$, we can just negate both factors to get a factorization with both leading coefficients $1$. It must be the case that $f(x)=(x+a)(x^2+bx+c)$.

$(x+a)(x^2+bx+c)=x^3+(a+b)x^2+(ab+c)x+ac$

Equating to the coefficients:

$a+b=3$, $ab+c=0$, $ac=-8$

$c=-ab$

$a+b=3$, $a^2b=8$

Since $a^2$ is positive and $a^2b$ is positive, $b$ must be positive. $1\leq b\leq 3$. If $b=1$ or $b=3$, $a$ cannot be an integer so $b=2$, and $a=2$, contradicting that $a+b=3$, showing that $f(x)$ wasn't reducible after all.



**Exercise 17**

Obviously, an $\alpha\in\mathbb{Q}$ is a root of $f(x)=x^4-22x^2+1$ iff $\alpha^2$ is a root of $g(x)=x^2-22x+1$. If $g(x)$ has a rational root, that must mean that it is reducible over $\mathbb{Q}$, which means it is reducible over $\mathbb{Z}$, meaning that - WLOG - $g(x)=(x-n)(x-m)$ for some integer $n,m$, which obviously cannot be. Since $g(x)$ has no rational roots, and since the square of a rational is always a rational, by our initial observation $f(x)$ cannot have any rational roots.



**Exercises 18-21**

Satisfies $p=3$.

Satisfies $p=3$.

The constant term is $18=3^2(2)$, therefore the only possibility is $p=2$ which fails because it divides the leading coefficient. The criterion is not satisfied.

Satisfies $p=5$.



**Exercise 22**

$f(x)=6x^4+17x^3+7x^2+x-10$

$f'(x)=24x^3+51x^2+14x+1$

$f''(x)=72x^2+102x+14$

$x^2+\frac{34}{24}x=-\frac{7}{36}$

$x^2+\frac{34}{24}x+(\frac{17}{24})^2=-\frac{7}{36}+(\frac{17}{24})^2$



$36x^2+51x=-7$

$36x^2+51x=-7$

TODO



**Exercise 23**

It must be specified that $g(x)$ and $h(x)$ must be of degree lower than $f(x)$.



**Exercise 24**

Correct.



**Exercise 25**

a. T

b. T

c. T

d. F ($x^2+3=x^2-4=(x-2)(x+2)$)

e. T

f. T (identical to e.?)

g. T

h. T

i. T

j. F ($f(x)=0$)



**Exercise 26**

$x^4+x^3+x^2-x+1$

$=(x+2)(x^3)+(-x^3+x^2-x+1)$

$=(x+2)(x^3-x^2)+(3x^2-x+1)$

$=(x+2)(x^3-x^2+3x)+(-7x+1)$

$=(x+2)(x^3-x^2+3x-7)+(15)$

It must be the case that $15\equiv 0\mod p$. $15=3(5)$, therefore the only viable $p$ are $3$ and $5$.



**Exercise 27**

Observation: All irreducible polynomials of degree $\geq 2$ must have a nonzero constant term, otherwise $x$ will be a factor.

$x^2+x+1$ is irreducible

$x^2+1=(x+1)^2$



**Exercise 28**

$x^3+x^2+x+1=(x^2+1)(x+1)$

$x^3+x^2+1$ is irreducible

$x^3+x+1$ is irreducible

$x^3+1=(x-1)(x^2+x+1)$



**Exercise 29**

Considering only leading coefficient 1.

$x^2+x+1=(x-1)(x-1)$

$x^2+x-1$ is irreducible

$x^2-x+1=(x+1)(x+1)$

$x^2-x-1$ is irreducible

$x^2+1$ is irreducible

$x^2-1=(x-1)(x+1)$



**Exercise 30**

Considering only leading coefficient 1.

$x^3+x^2+x+1=(x+1)(x^2+1)$

$x^3+x^2-x+1$ is irreducible.

$x^3+x^2-x+1$ is irreducible.

TODO



**Exercise 31**

TODO



**Exercise 32**

Every zero gives a linear factor. If there are $k$ linear factors, the degree of the product is at least $k$, therefore there must be at most $n$ linear factors and by extension at most $n$ zeros.



**Exercise 33**

By the fundamental theorem of finitely generated abelian groups, the group must be a product of cyclic abelian groups. If $m$ is the LCM of the orders of the factors, all elements in the product group must be a zero of $x^m-1$, of which there are at most $m$, meaning that the product group is of order at most $m$. Since the LCM cannot be higher than the product, the LCM must equal the product of the orders of the factors, meaning that they are all coprime and the product group is cyclic.



**Exercise 34**

By Corollary 20.2, in $\mathbb{Z}_p$ every zero of $x-a$ is a zero of $x^p-a$. $a$ is obviously a zero. By the factor theorem, the polynomial is reducible.



**Exercise 35**

$\sum_{i=0}^n a_ia^i=0$. Dividing by $a^n$, $\sum_{i=0}^n a_ia^{i-n}=0$. Reindexing $j=n-i$, $\sum_{j=0}^n a_{-j}a^j=a_n+a_{n-1}a^{-1}+\ldots+a_0a^{-n}=0$, completing the proof.



**Exercise 36**

We set $g(x)=x-\alpha$. By the division algorithm, there exist $q(x),r(x)\in F[x]$ s.t. $f(x)=(x-\alpha)q(x)+r(x)$. Applying the $\phi_\alpha$ evaluation homomorphism at $\alpha$, $f(\alpha)=0q(\alpha)+r(\alpha)=r(\alpha)$ which since $r(x)$ is a constant (lower degree than $g(x)$ which is linear, so constant) is in turn equal to $r(x)$. This means that $r(x)=f(\alpha)$, completing the proof.



**Exercise 37**

a.

Let $f(x),g(x)\in \mathbb{Z}[x]$ s.t. $f(x)=\sum_{i=0}^\infty a_ix^i$ and $g(x)=\sum_{i=0}^\infty b_ix^i$.

For additivity:

$\overline{\sigma_m}(f(x)+g(x))=\overline{\sigma_m}(\sum_{i=0}^\infty (a_i+b_i)x^i)$

$=\sum_{i=0}^\infty \sigma_m(a_i+b_i)x^i=\sum_{i=0}^\infty (\sigma_m(a_i)+\sigma_m(b_i))x^i$

$=\overline{\sigma_m}(f(x))+\overline{\sigma_m}(g(x))$.

For multiplicativity:

$\overline{\sigma_m}(f(x)+g(x))=\overline{\sigma_m}(\sum_{i=0}^\infty\sum_{j=0}^i(a_jb_{i-j})x^i)$

$=\sum_{i=0}^\infty \sigma_m(\sum_{j=0}^i(a_jb_{i-j}))x^i$

$=\sum_{i=0}^\infty \sum_{j=0}^i\sigma_m(a_jb_{i-j})x^i$

$=\sum_{i=0}^\infty \sum_{j=0}^i\sigma_m(a_j)\sigma_m(b_{i-j})x^i$

$=\overline{\sigma_m}(f(x))\overline{\sigma_m}(g(x))$.

b.

$f(x)=g(x)h(x)$ for $g(x),h(x)\in\mathbb{Z}[x]$ means that

$\overline{\sigma_m}(f(x))=\overline{\sigma_m}(g(x))\overline{\sigma_m}(h(x))$. This contradicts our hypothesis that $\overline{\sigma_m}(f(x))$ is irreducible in $\mathbb{Z}_n[x]$. We have that $f(x)$ is irreducible in $\mathbb{Z}[x]$, which by Theorem 23.11 means that it is irreducible in $\mathbb{Q}[x]$, completing the proof.

c.

Setting $m=5$, we have $\overline{\sigma_m}(f(x))=x^3+2x+1$. Trying all values, this polynomial has no roots in $\mathbb{Z}_5$. By Theorem 23.10, this means that it is irreducible over $\mathbb{Z}_5$, which by (b) means it is irreducible over $\mathbb{Q}[x]$, completing the proof.



