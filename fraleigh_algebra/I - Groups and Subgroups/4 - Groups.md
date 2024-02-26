**Exercise 1-6**

$\mathscr{G}_3$ does not hold

All axioms hold

$\mathscr{G}_1$ does not hold

$\mathscr{G}_3$ does not hold (no inverse for $0$)

$\mathscr{G}_2$ does not hold (no left identity)

$\mathscr{G}_2$ does not hold (no identity)



**Exercise 7**

$\mathbb{Z}_{1000}$



**Exercise 8**

```

.|1357

-+----

1|1357

3|3175

5|5713

7|7531

```



**Exercise 9**

"There exists $x \in S$ s.t. $x \neq e$ and $x*x=e$" is a structural property that $\langle U,\cdot\rangle$ satisfies but that $\langle \mathbb{R},+\rangle$ does not satisfy.

$-1$ is a suitable $x$ for $U$.

In $\langle \mathbb{R},+\rangle$:

$x+x=0$

$2x=0$

$x=0$

$x=e$ and the property is not satisfied, therefore the two groups cannot be isomorphic.

"There exists multiple $x \in S$ s.t. $x \neq e$ and $x*x*x*x=e$" is a structural property that $\langle U,\cdot\rangle$ satisfies but that $\langle \mathbb{R}^*,\cdot\rangle$ does not satisfy.

$i$ and $-1$ are suitable $x$ for $U$.

In $\langle \mathbb{R}^*,\cdot\rangle$, the only solutions to $x^4=1$ are $-1$ and $1$. $1=e$, so only $-1$ is a suitable $x$, meaning there aren't multiple $x$, meaning the property is not satisfied and the groups cannot be isomorphic.



**Exercise 10**

a.

	$\mathscr{G}_1$ is satisfied because of the associativity of addition.

	$\mathscr{G}_2$ is satisfied because $0$ is in $n\mathbb{Z}$ (can be represented as $0\cdot n$)

	$\mathscr{G}_3$:

	Let $x \in n\mathbb{Z}$ s.t. $x = ny$ ($y \in \mathbb{Z}$)

	$n(-y)$ is in $n\mathbb{Z}$ and $x+n(-y) = 0$, therefore $n(-y)$ is an inverse of $x$.

b.

	Let $\phi : \mathbb{Z} \mapsto n\mathbb{Z}$ and $\phi(x) = nx$

	$\phi$ is injective:

	$\phi(x) = \phi(y)$

	$nx = ny$

	$x=y$ (we can cancel because $n\neq 0$)

	$\phi$ is surjective by the definition of $n\mathbb{Z}$.

	$\phi$ has the homomorphism property:

	$n(x+y)=n(x+y)$

	By the distributive property of $\cdot$:

	$n(x+y)=nx+ny$

	By the definition of $\phi$:

	$\phi(x+y)=\phi(x)+\phi(y)$

	$\phi$ meets all the criteria to be an isomorphism, therefore the two groups are isomorphic.



**Exercise 11-18**

YNYYNYYY



**Exercise 19**

We will use the fact that $a*b=a+b+ab=(a+1)(b+1)-1$

a.

	Since $a*b$ is obviously a real number, we only need to show that $a*b$ cannot be $-1$.

	Suppose by contradiction:

	$a*b=a+b+ab=-1$

	$(a+1)(b+1)-1=-1$

	$(a+1)(b+1)=0$

	This implies that either $a+1$ or $b+1$ is $0$, which leads to a contradiction since $a+1=0$ means $a=-1$ which means that $a \notin S$ (and similarly for $b$).

b.

	Associativity of $*$:

	$(a*b)*c=a*(b*c)$

	$((a+1)(b+1)-1)*c=a*((b+1)(c+1)-1)$

	$(((a+1)(b+1)-1)+1)(c+1)-1=(a+1)(((b+1)(c+1)-1)+1)-1$

	$(a+1)(b+1)(c+1)-1=(a+1)(b+1)(c+1)-1$

	Identity of $*$ is $0$:

	$a*0=a+0+a\cdot 0= a$

	(and likewise for $0*a$ by the symmetry of $*$)

	Inverse of $a$ is $\frac{1}{a+1}-1$:

	$a*(\frac{1}{a+1}-1)$

	$(a+1)((\frac{1}{a+1}-1)+1)-1$

	$(a+1)\frac{1}{a+1}-1$

	$1-1$

	$0$, which is the identity element we just identified.

c.

	$-\frac{1}{3}$



**Exercise 20**

```

T_1

*|eabc

-+----

e|eabc

a|aecb

b|bcea

c|cbae



T_2

*|eabc

-+----

e|eabc

a|aecb

b|bcae

c|cbea



T_3

*|eabc

-+----

e|eabc

a|abce

b|bcea

c|ceab

```



The mapping

```

T2|eabc

T3|ebac

```

gives an isomorphism between $T_2$ and $T_3$.



a.

	Yes.

b.

	$T_3$

c.

	$T_1$ is isomorphic to the group of all 2x2 diagonal matrices with all diagonal entries 1 or -1.

	Isomorphism:

	$e \mapsto \begin{bmatrix}1 & 0 \\ 0 & 1\end{bmatrix}$

	$a \mapsto \begin{bmatrix}-1 & 0 \\ 0 & 1\end{bmatrix}$

	$b \mapsto \begin{bmatrix}1 & 0 \\ 0 & -1\end{bmatrix}$

	$c \mapsto \begin{bmatrix}-1 & 0 \\ 0 & -1\end{bmatrix}$

	The table is verified by computation.



**Exercise 21**

2,  6.



**Exercise 22**

$\mathscr{G}_3$ uses the identity element defined in $\mathscr{G}_2$ so $\mathscr{G}_3$ has to come after $\mathscr{G}_2$. Only 123, 213, and 231 satisfy this condition.



**Exercise 23**

a.

	The statement that $e*x=x*e=x=\text{identity}$ is incorrect. $x$ may not be equal to the identity element.

b.

	A group is not just a set, it has to also have an operation. What "identity element" and "inverse" mean is not specified.

c.

	It is not stated that the binary operation has to be associative. What "identity element" and "inverse" mean is not specified.

d.

	It is not clear what "associative under addition" means. The definition of an identity element is given incorrectly, it may not be the case that $e*a=e$.



**Exercise 24**

```

*|eab

-+---

e|eab

a|aea

b|bae

```



**Exercise 25**

FTTFFTTTFT

(d is subjective?)



**Exercise 26**

Apply $a^{-1}$ on the left of both sides of the equation $a*b=a*c$ , then apply associativity and remove the identity element to get $b=c$.



**Exercise 27**

Apply $a^{-1}$ on the left of both sides of the equation, then apply associativity and remove the identity element. Compute the right side of the equation.



**Exercise 28**

We will prove that $\phi(a)*'\phi(a')=e'$.

Starting with:

$\phi(e)=e'$

$\phi(a*a')=e'$

Applying the homomorphism property of $\phi$:

$\phi(a)*'\phi(a')=e'$



**Exercise 29**

$a*a=e$ means $a=a'$, so it is sufficient to show that there is at least one non-identity element that is its own inverse.

Consider the set $S = \{x \in G, x \neq e\}$. $|S|$ is obviously odd. If we match every element with its inverse, if every element were distinct from its inverse then $|S|$ would be even, which means there needs to be at least one element of $S$ that is its own inverse.



**Exercise 30**

a.

	$(a*b)*c=a*(b*c)$ means $||a|b|c=|a||b|c$ which is true by the properties of $|x|$, and so $*$ is associative.

b.

	The element $1$ is the left identity element:

	$1*x = |1|x = x$

	$\frac{1}{|x|}$ is the right inverse for all $x \in \mathbb{R}^*$:

	$x * \frac{1}{|x|}=|x|\frac{1}{|x|}=1$

c.

	No. There is no identity element. Suppose by contradiction that there were an identity element. This element would also act as a right identity element. Previously in the text we have shown that if a group has a left identity element and a right identity element they must be equal. If there is a right identity element, it must equal $1$ because we just showed that $1$ is the left identity element. However $(-1)*1 = |-1|1=1\neq -1$, so $1$ cannot be the right identity element, leading to a contradiction.

d.

	A binary structure is not necessarily a group just because it has a one-sided identity element and a one-sided inverse for every element. Those two things must be of the same side (e.g. left identity and left inverse).



**Exercise 31**

If an element $x$ is idempotent, $x=e$.

$x*x=x$

$x*x*x'=x*x'$

$x*e=e$

$x=e$

Since there is only one $x$ that satisfies $x=e$, there is only one idempotent element.



**Exercise 32**

We will prove that $a*b=b*a$ for all $a,b\in G$.

$a*b*a*b=e$

$a*b*a*b*b*a=e*b*a$

$a*b*a*a=b*a$

$a*b=b*a$



**Exercise 33**

Consider the base case $n=1$:

$(a*b)^1=a^1*b^1$

$a*b=a*b$

We assume inductively that $(a*b)^n=a^n*b^n$, we will prove $(a*b)^{n-1}=a^{n+1}*b^{n+1}$

$(a*b)^n=a^n*b^n$

$(a*b)^n*a*b=a^n*b^n*a*b$

$(a*b)^n*a*b=a^n*a*b^n*b$

$(a*b)^{n+1}=a^{n+1}*b^{n+1}$

thus closing the induction.



**Exercise 34**

Consider $a^1, a^2, a^3, ..., a^m, a^{m+1}$, where $m$ is the number of elements in $G$. Since there are $m+1$ elements here, by the pigeonhole principle, there must be two elements in this list that are equal. Let $a^i$ and $a^j$ be the equal elements, where $i>j$.

$a^i=a^j$

$a^i*a'^j=a^j*a'^j$

$a^{i-j}=e$



**Exercise 35**

$(a*b)^2=a^2*b^2$

$a*b*a*b = a*a*b*b$

$b*a = a*b$



**Exercise 36**

$a*b=b*a$ implies $(a*b)'=a'*b'$:

$b*a*a'*b'=e$

$a*b*a'*b'=e$

Therefore, the inverse of $a*b$ is $a'*b'$, i.e. $(a*b)'=a'*b'$.



$(a*b)'=a'*b'$ implies $a*b=b*a$:

$a*b*a'*b'=e$

$a*b*a'*b'*b*a=e*b*a$

$a*b*a'*a=b*a$

$a*b=b*a$



**Exercise 37**

$a*b*c=e$

$a'*a*b*c=a'*e$

$b*c=a'$

$b*c*a=a'*a$

$b*c*a=e$



**Exercise 38**

$ex=x$



**Exercise 39**

TODO



**Exercise 40**

We will prove that $\phi(a) = a'$ is an isomorphism.

$\phi$ is injective:

$\phi(a) = \phi(b)$

$a' = b'$

$a = b$

$\phi$ is surjective:

$a'$ is a valid $x$ for $\phi(x)=a$ for all $a\in G$.

$\phi$ has the homomorphism property:

$b'*a' = b'*a'$

$b'*a' = a'\cdot b'$

$(a*b)' = a'\cdot b'$

$\phi(a*b) = \phi(a)\cdot \phi(b)$



**Exercise 41**

We will prove that $i_g(x)=gxg'$ is an isomorphism.

$i_g$ is injective:

$i_g(a)=i_g(b)$

$gag'=gbg'$

$a=b$

$i_g$ is surjective:

$g'ag$ is a valid $x$ for $i_g(x)=a$ for all $a\in G$

$a=a$

$eae=a$

$gg'agg'=a$

$i_g(g'ag)=a$

$i_g$ has the homomorphism property:

$gabg'=gabg'$

$gabg'=gag'gbg'$

$i_g(ab)=i_g(a)i_g(b)$
