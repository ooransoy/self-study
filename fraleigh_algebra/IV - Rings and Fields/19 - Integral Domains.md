**Exercise 1**

$x^3-2x^2-3x=0$

$x(x^2-2x-3)=0$

$x(x-3)(x+1)=0$



0, 3, 11 are obvious. A computation shows that 5, 8, 9 are also solutions.



**Exercise 2**

The reciprocal of $3$ in $\mathbb{Z}_7$ is $5$.

$3x=2$

$x=(5)2=10$



The reciprocal of $3$ in $\mathbb{Z}_{23}$ is $8$.

$3x=2$

$x=(8)2=16$



**Exercise 3**

$\varnothing$



**Exercise 4**

$\{2\}$



**Exercise 5-10**

0

0

0

3

12

30



**Exercise 11**

$a^4+4a^3b+6a^2b^2+4ab^3+b^4$

Since the field has characteristic 4, any term with coefficient $\geq 4$ is $0$. This cancels all terms other than $a^4$ and $b^4$. The expression is equal to $a^4+b^4$.



**Exercise 12**

All middle terms vanish again, leaving $a^9+b^9$.



**Exercise 13**

All middle terms vanish again, leaving $a^6+b^6$.



**Exercise 14**

$\begin{bmatrix}1&2\\2&4\end{bmatrix}\begin{bmatrix}2&0\\-1&0\end{bmatrix}=\begin{bmatrix}0&0\\0&0\end{bmatrix}$

This shows that the matrix is a divisor of zero, as the second factor is clearly nonzero.



**Exercise 15**

For nonzero $a,b$.



**Exercise 16**

It should be the _lowest_ $n$. Also, if there exists no such $n$, the characteristic is 0.



**Exercise 17**

a. F

b. T

c. F

d. F

e. T

f. T

g. F ($(0,x)(y,0)=(0,0)$) 

h. T ($ab=0$, $abb^{-1}=0b^{-1}$, $a=0$)

i. T

j. F



**Exercise 18**

1: $\mathbb{R}$

2: $\mathbb{Z}$

3: $\mathbb{Z}_6$

4: The subring $\{0,2,4\}$ of $\mathbb{Z}_6$

5: $M_2(\mathbb{Z})$

6: The subring of $M_2(\mathbb{Z})$ consisting of only even entries



**Exercise 19**

$\det(A)=0$ must hold.

TODO (not enough linalg knowledge)



**Exercise 20**

TODO (draw a figure)



**Exercise 21**

If the cancellation laws did hold, $a$ can be canceled from $ab=0=a0$ to show that $a,b$ weren't zero divisors in the first place.



**Exercise 22**

Multiplying all elements of the domain with the same nonzero element permutes them, because if there were zero divisors there would be multiple 0s, and the cancellation laws hold so distinct right factors lead to distinct products.



**Exercise 23**

0 is obviously idempotent. Let $a$ be some nonzero idempotent element. $a^2=a$. Since $a$ is a unit, $a^2a^{-1}=aa^{-1}$, so $a=1$, showing that the only idempotent nonzero element is 1 and that there are only two distinct idempotent elements.



**Exercise 24**

It is obvious that the intersection is a ring, is commutative, and has no divisors of 0.

Consider a domain $D$ with unity $1_D$ and a subdomain $E$. Consider any nonzero $x\in E$. Because $E$ is a subdomain, there is $y\in E$ s.t. $xy=yx=1_D$. Since $E$ is closed under multiplication, $1_D$ must be in $E$, showing that every subdomain of a domain contains the unity of the domain. This is sufficient to deduce that the intersection of subdomains contains unity, completing the proof that the intersection is a subdomain.



**Exercise 25**

Let $a$ be some nonzero of $R$.

By Theorem 19.5, since $R$ has no zero divisors, the cancellation laws hold. Therefore, the function $f_a:R^*\to R^*$ given by $f_a(x)=ax$ for nonzero $a$ is injective. ($f_a(x)=f_a(y)$, $ax=ay$, $x=y$ from cancellation). Since the domain and codomain of the function are the same, it being an injection shows that it is a bijection. Since $f$ is surjective, there must exist some $b$ s.t. $f_a(b)=1=ab$. It remains to show that $ba=1$, which follows from $b=b1=b(ab)=(ba)b$ and cancelling $b$ from the right of $b=bab$, completing the proof.



**Exercise 26**

for any $a$ there exists at most one $b$ s.t. $aba=a$

for any $a$ there exists at least one $b$ s.t. $aba=a$



for any nonzero $a$, $ab=ac\implies b=c$

for any nonzero $a,b$, $ab\neq 0$

for any $b$ there is at least one $a$ s.t. $aba=a$

for any $b$ there is at most one $a$ s.t. $aba=a$



nonzero $a$

$ab=ac$

$aba=aca$



**Exercise 27**

Since integral domains have unity, by Theorem 19.15 it suffices to consider only $n\cdot1=0$. Since the subdomain has the same unity $1$, the characteristic is determined by the same element in both the domain and the subdomain, showing that their characteristics are the same. (It is obvious that the smallest $n$ s.t. $n\cdot 1=0$ doesn't change in the subdomain.)



**Exercise 28**

$1$ is contained in every subdomain. Since subdomains are closed under addition, $1+1$, $1+1+1$... i.e. all $n\cdot 1$ are contained in every subdomain.



**Exercise 29**

Obviously, the characteristic cannot be 1. It suffices to show that for an integral domain of characteristic $c\geq 2$, $c$ is prime.

Suppose that $c$ is composite. There must be $p,q\geq 2$ s.t. $c=pq$. $c\cdot 1=0=pq\cdot 1=(p\cdot 1)(q\cdot 1)$. Since an integral domain has no zero divisors, either $p\cdot 1$ or $q\cdot 1$ must be $0$. Since both are $<c$, this contradicts that $c$ is the characteristic of the domain, completing the proof.



**Exercise 30**

TODO
