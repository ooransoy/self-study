**Exercise 1-4**

$4, 6$

$-5, 3$

$-7, 6$

$6, 2$



**Exercise 5-7**

$8$

$8$

$60$



**Exercise 8-11**

$4$

$4$

$4$

$16$



**Exercise 12-16**

$1$

$2$

$4$

$2$

$4$



**Exercise 17-21**

$6$

$7$

$4$

$8$

$\infty$



**Exercise 22-24**

```

right and down is subgroup



Z_12:

<1><2><4>

<3><6><0>



Z_36:

< 1>< 2>< 4>

< 3>< 6><12>

< 9><18>< 0>



Z_8:

<1><2><4><0>

```



**Exercise 25-29**

1 6 3 2 3 6

1 8 4 8 2 8 4 8

1 12 6 4 3 12 2 12 3 4 6 12

1 20 10 20 5 4 10 20 5 20 2 20 5 20 10 4 5 20 10 20



**Exercise 30**

It should be mentioned that $n$ is the smallest positive solution to $a^n=e$.



**Exercise 31**

No correction is needed.



**Exercise 32**

TFFFTFFFTT



**Exercise 33-37**

$V$

$\mathbb{Q}$

$\mathbb{Z}_2$

Every infinite cyclic group is isomorphic to $\mathbb{Z}$, which has 2 generators, not 4.

$\mathbb{Z}_8$



**Exercise 38-41**

$\pm i$

$\frac{1\pm i\sqrt{3}}{2}$

$\frac{\pm\sqrt{2}\pm i\sqrt{2}}{2}$

$\frac{\pm\sqrt{3}\pm i}{2}$



**Exercise 42**

Since every element is a power of a fixed generator, we can swap the exponents because of the commutativity of addition.



**Exercise 43**

Let $m$ be the smallest positive number s.t. $a^m\in H$. $a^m$ generates $H$, because if it didn't we can apply the division algorithm on the exponent of the element that $\langle a^m\rangle$ misses and obtain a $k<m$ s.t. $a^k\in H$ which contradicts our initial pick of $m$.



**Exercise 44**

Let $n\in \mathbb{Z}$ s.t. $a^n=x$.

$\phi(a)^n=\psi(a)^n$

$\phi(a)^n=\psi(a)^n$

$\phi(a^n)=\psi(a^n)$

$\phi(x)=\psi(x)$



**Exercise 45**

Let $H$ be said subset. Consider $a=n_ar+m_as\in H$ and $b=n_br+m_bs\in H$. $a+b=n_ar+m_as+n_br+m_bs=(n_a+n_b)r+(m_a+m_b)s$, therefore $a+b$ satisfies the condition to be in $H$, showing that $H$ is closed and therefore is a subgroup.



**Exercise 46**

We will prove that $\phi(x)=a^{-1}xa$ is a bijection from $\langle ab\rangle$ to $\langle ba\rangle$.

Injective:

$\phi(x)=\phi(y)$

$\phi((ab)^p)=\phi((ab)^q)$

$\phi(ab)^p=\phi(ab)^q$

$(ba)^p=(ba)^q$

$a(ba)^pa^{-1}=a(ba)^qa^{-1}$

$(ab)^p=(ab)^q$

$x=y$

Surjective:

$\phi(x)=y=(ba)^p$

$(ab)^p$ is a suitable $x$.

Therefore, $|\langle ab\rangle|=|\langle ba\rangle|$



**Exercise 47**

a.

	$\{r\text{ and }s\text{ divide }x|x\in \mathbb{Z}\}$

b.

	If $r$ and $s$ are relatively prime.

c.

	bruh



**Exercise 48**

We will show that if a group $G$ is infinite then $G$ has to have an infinite number of subgroups.

If there is an element $g\in G$ with infinite order, $\langle g\rangle$ is isomorphic to $\mathbb{Z}$ which we know has an infinite number of subgroups.

If there is no such element and all elements are of finite order, consider the partition on $G$ by the equivalence relation $\langle a\rangle = \langle b\rangle$. No partition has an infinite number of elements, because if it did that would mean the elements in it have infinite order. Since every partition has a finite number of elements, there cannot be a finite number of partitions because that would mean that $G$ is finite. This shows that $G$ has an infinite number of elements.



**Exercise 49**

$V$



**Exercise 50**

Consider $(xax^{-1})^2=xax^{-1}xax^{-1}=xaax^{-1}=xex^{-1}=e$. Since $a$ is the unique element of order 2, it must be the case that $xax^{-1}=a$. Substituting into $ax$:

$ax=xax^{-1}x=xa$



**Exercise 51**

$(p-1)(q-1)$



**Exercise 52**

$p^r-p^{r-1}$



**Exercise 53**

Let $g$ be some generator of $G$.

Since every element of $G$ will be a power of $g$, we can reformulate our problem as showing that there are $m$ solutions $a\in\mathbb{Z}, 0\leq a<n$ for $(g^a)^m=e$ for every positive $m$ that divides $n$.

$g^{am}=e$ will hold only when $n|am$.

$n|am$

$\frac{n}{m}|a$

$a = \frac{n}{m}k \quad \exists k\in\mathbb{Z}$

All $0\leq k < m$ satisfies the constraints for $a$. Clearly, there are $m$ such solutions.



**Exercise 54**

Let $d$ be the GCD of $m$ and $n$. We will continue the proof from $n|am$.

Clearly, $n|am \iff n|ad$.

$\frac{n}{d}|a$

$a = \frac{n}{d}k \quad \exists k\in\mathbb{Z}$

All $0\leq k < d$ satisfies the constraints for $a$. Clearly, there are $d$ (i.e. $\gcd(n, m)$) such solutions.



**Exercise 55**

For all $x\in G$, if a subgroup contains $x$ then it must contain everything in $\langle x\rangle$. If $x$ is not the identity, $\langle x\rangle = G$ because $p$ is prime. Since a nontrivial subgroup has to contain a non-identity element, a nontrivial subgroup must be improper.



**Exercise 56**

**a)**

Let $n = |G|$. Let $d = \gcd(r, s)$ and $l = \frac{rs}{d}=\mathrm{lcm}(r, s)$

Let $\langle h\rangle=H$ and $\langle k\rangle = K$. We will show that $|\langle hk\rangle| = l$. It will suffice to show that $l$ is the smallest positive integer $x$ such that $(hk)^x=e$. Since $G$ is abelian, $(hk)^x=h^xk^x=e$, showing that $h^x$ and $k^x$ are inverses. We will show that $h^x=k^x=e$. Suppose by contradiction that $h^x \neq e$. Since $h^x$ and $k^x$ are inverses, $h^{-x} = k^x \neq e$ as well. This means that $x$ is not a multiple of $r$ nor a multiple of $s$. By 6.14, $|\langle k^x\rangle|=\frac{s}{\gcd(s, x)}$, and $|\langle h^x\rangle|=\frac{r}{\gcd(r, x)}$. Since $\langle k^x\rangle = \langle h^x\rangle$, we have $s\gcd(r,x)=r\gcd(s,x)$.

$r|s\gcd(r,x)$

$\frac{r}{d}|\frac{s}{d}\gcd(r,x)$

$\frac{r}{d}|\gcd(r,x)$

Since in this case $d=1$, $r|\gcd(r, x)$ meaning $x$ must be a multiple of $r$. WLOG we can say the same for $s$, meaning $x$ cannot be smaller than $l$ and $l$ is a suitable $x$.
