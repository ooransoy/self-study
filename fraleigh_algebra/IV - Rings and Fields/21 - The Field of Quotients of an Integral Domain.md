**Exercise 1**
$\frac{a+bi}{c+di}=\frac{(a+bi)(c-di)}{(c+di)(c-di)}$
$=\frac{ac+bd+(bc-ad)i}{c^2+d^2}$
$\{x+yi\ |\ x,y\in\mathbb{Q}\}$

**Exercise 2**
$\frac{a+b\sqrt{2}}{c+d\sqrt{2}}=\frac{(a+b\sqrt{2})(c-d\sqrt{2})}{(c+d\sqrt{2})(c-d\sqrt{2})}$
$=\frac{ac-2bd+(bc-ad)\sqrt{2}}{c^2-2d^2}$
$\{x+y\sqrt{2}\ |\ x,y\in\mathbb{Q}\}$

**Exercise 3**
Correct.

**Exercise 4**
a. T
b. F
c. T
d. F
e. T
f. T
g. F
h. T
i. T
j. T

**Exercise 5**
The field of quotients of the integral domain $\{a2^b\ |\ a,b\in\mathbb{Z}\}$  is equivalent to the field of quotients of the subdomain $\mathbb{Z}$.

**Exercise 6**
$([(a,b)]+[(c,d)])+[(r,s)]=[(ad+bc,bd)]+[(r,s)]$
$=[(ads+bcs+bdr,bds)]$
$[(a,b)]+([(c,d)]+[(r,s)])=[(a,b)]+[(cs+dr,ds)]$
$=[(ads+bcs+bdr,bds)]$
showing that addition is associative.

**Exercise 7**
$[(a,b)]+[(0,1)]=[(b0+a1,b1)]=[(a,b)]$
showing that $[(0,1)]$ is an additive identity.

**Exercise 8**
$[(-a,b)]+[(a,b)]=[(ab-ab,bb)]=[(0,bb)]$
$0(1)=(bb)0$ showing that $(0,bb)\sim(0,1)$
$[(0,bb)]=[(0,1)]$ which is the additive identity. This shows that $[(-a,b)]$ is an additive inverse for $[(a,b)]$.

**Exercise 9**
$([(a,b)][(c,d)])[(r,s)]=[(ac,bd)][(r,s)]=[(acr,bds)]$
$=[(a,b)][(cr,ds)]=[(a,b)]([(c,d)(r,s)])$
showing that multiplication is associative.

**Exercise 10**
$[(a,b)][(c,d)]=[(ac,bd)]=[(ca,db)]=[(c,d)][(a,b)]$
showing that multiplication is commutative.

Lemma: $[(a,c)]+[(b,c)]=[(ac+bc,cc)]$
$(ac+bc)c=(cc)(a+b)$ therefore $(ac+bc,cc)\sim(a+b,c)$
$[(a,c)]+[(b,c)]=[(a+b,c)]$

Lemma: $(ac)b=(bc)a$, therefore $(ac,bc)\sim(a,b)$ and $[(ac,bc)]=[(a,b)]$

**Exercise 11**
Because we have already established commutativity, it suffices to check for left distributivity.
Continuing with the proof:
$[(a,b)]([(c,d)]+[(r,s)])=[(a,b)][(cs+dr,ds)]$
$=[(acs+adr,bds)]=[(acs,bds)]+[(adr,bds)]$
$=[(ac,bd)]+[(ar,bs)]=[(a,b)][(c,d)]+[(a,b)][(r,s)]$
showing distributivity.

**Exercise ??**
$[(a,b)][(1,1)]=[(a1,b1)]=[(a,b)]$
showing that $[(1,1)]$ is a multiplicative identity.

**Exercise 12**
a.
Let $a\in R$ and $b,t\in T$.
Since $T$ is closed under multiplication, $bt\in T$, and $(at,bt)\in Q(R,T)$
$(at)b=(bt)a$ holds in a commutative ring, therefore $(at,bt)\sim(a,b)$
$[(a,b)][(t,t)]=[(at,bt)]=[(a,b)]$
showing that $[(t,t)]$ is unity.
b.
Obviously, for an element of $Q(R,T)$ to be nonzero, the first component must be nonzero.
Let $t\in T$. $[(t,tt)][(tt,t)]=[(ttt,ttt)]$ which is unity, so $[(t,tt)]$ is an inverse of $[(tt,t)]$ and therefore $[(tt,t)]$ i.e. $t$ is a unit in $Q(R,T)$.

**Exercise 13**
Since $a$ is not a divisor of 0, none of $a^n$ are 0.
$Q(R, \{a^n\ |\ n\in\mathbb{Z}\})$ is a commutative ring with unity containing $R$.

**Exercise 14**
6.
$0, 1, 2, 3, 1/3, 2/3$

**Exercise 15**
It is isomorphic to the subring $\{n2^m\ |\ n,m\in\mathbb{Z}\}$ of $\mathbb{R}$.

**Exercise 16**
It is isomorphic to the subring $\{2^n3^m\ |\ n,m\in\mathbb{Z}\}$ of $\mathbb{R}$.

**Exercise 17**
In Lemma 21.2, while proving transitivity we use the cancellation law.