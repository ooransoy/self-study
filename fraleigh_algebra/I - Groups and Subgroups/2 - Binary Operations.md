**Exercise 1-4**

$e$

$b$

$a$

No, because $e*b=b$ and $b*e=c$ thus $e*b\neq b*e$



**Exercise 5**

```

*|abcd

-+----

a|abcd

b|bdac

c|cadb

d|dcba

```



**Exercise 6**

```

*|abcd

-+----

a|abcd

b|bacd

c|cdcd

d|dccd 

```



**Exercise 7-11**

F, F

T, F

T, T

T, F

F, F



**Exercise 12**

1

16

19683

$n^{(n^2)}$



**Exercise 13**

8

729

$n^{\frac{n(n+1)}{2}}$



**Exercise 14-16**

Specify that $*$ is on S, and that the condition should hold for all $a, b \in S$.

No correction needed.

The condition should hold for all $a, b \in H$, not for all $a, b \in S$.



**Exercise 17-22**

C2 is violated, $1*2=1-2$ is not in $\mathbb{Z}^+$.

C1 is violated, $0*0=0^0$ is not defined.

No condition is violated.

No condition is violated.

C1 is violated, $1*2$ can be both $8$ or $9$.

C2 is violated, $1*1$ is not in $\mathbb{Z}^+$.



**Exercise 23**

a. Yes.

b. Yes.



**Exercise 24**

FTFFFTTTTF

(d is subjective?)



**Exercise 25**

On the set of graphs, define $*$ by letting $G_1 * G_2$ to be the cartesian graph product of $G_1$ and $G_2$.

On the set of graphs, define $*'$ by letting $G_1 * G_2$ to be the intersection of $G_1$ and $G_2$.



**Exercise 26**

$(a*b)*(c*d)=((d*c)*a)*b$

By commutativity:

$(a*b)*(d*c)=$

By transitivity:

$a*(b*(d*c))=$

By commutativity:

$(b*(d*c))*a=$

By transitivity:

$b*((d*c)*a)=$

By commutativity:

$((d*c)*a)*b=((d*c)*a)*b$



**Exercise 27**

Let's call the element in the set $x$.

We will prove $a*b=b*a$ for all $a, b \in S$. The only possibility is that $a=b=x$. Substituting $x$ for $a$ and $b$, we get $x*x=x*x$, which is obviously true.

We will prove $(a*b)*c=a*(b*c)$ for all $a, b, c \in S$. The only possibility is that $a=b=c=x$. Substituting $x$ for $a$ and $b$ and $c$, we get $(x*x)*x=x*(x*x)$, which is true by commutativity.



**Exercise 28**

The commutative operation defined by the table

```

*|ab

-+--

a|ba

b|aa

```

is not associative, $(a*a)*b = a \neq a*(a*b) = b$.



**Exercise 29-35**

We will prove $((f+g)+h)(x) = (f+(g+h))(x)$ for all $x \in \mathbb{R}$ and $f, g, h \in F$. By the defintion of $+$ on $F$, we have $(f(x)+g(x))+h(x)=f(x)+(g(x)+h(x))$ for all $x \in \mathbb{R}$, which is true by the associativity of $+$ on $\mathbb{R}$.

False, if $f(x)=1$ and $g(x)=0$, then $(f-g)(x)=1$ and $(g-f)(x)=-1$, which means $-$ is not commutative.

False, if $f(x)=g(x)=0$ and $h(x)=1$, then $((f-g)-h)(x)=-1$ and $(f-(g-h))(x)=1$, which means $-$ is not associative.

We will prove $(f\cdot g)(x) = (g\cdot f)(x)$ for all $x\in \mathbb{R}$ and $f, g \in F$. By the definition of $\cdot$ on $F$, we have $f(x)g(x)=g(x)f(x)$ for all $x\in \mathbb{R}$, which is true by the commutativity of $\cdot$ on $\mathbb{R}$.

We will prove $((f\cdot g)\cdot h)(x) = (f\cdot (g\cdot h))(x)$ for all $x \in \mathbb{R}$ and $f, g, h \in F$. By the defintion of $\cdot$ on $F$, we have $(f(x)\cdot g(x))\cdot h(x)=f(x)\cdot (g(x)\cdot h(x))$ for all $x \in \mathbb{R}$, which is true by the associativity of $\cdot$ on $\mathbb{R}$.

False, if $f(x)=1$ and $g(x)=0$, then $(f\circ g)(x)=1$ and $(g\circ f)(x)=0$, which means $\circ$ is not commutative.

False, let $S=\{a, b\}$ and $x*y=a$ and $x*'y = b$ for all $x, y \in S$. $a*(b*'c) = a \neq (a*b)*'(a*c) = b$.



**Exercise 36**

The case where $|H| = 0$ is trivially true. For any $a, b \in H$ and any $x \in S$:

By the associativity of $*$:

$(a*b)*x = a*(b*x)$

By the definition of $b$ and $H$:

$(a*b)*x = a*(x*b)$

By the associativity of $*$:

$(a*b)*x = (a*x)*b$

By the definition of $a$ and $H$:

$(a*b)*x = (x*a)*b$

By the associativity of $*$:

$(a*b)*x = x*(a*b)$

Showing us that $a*b$ satisfies the requirement to be in $H$.



**Exercise 37**

The case where $|H| = 0$ is trivially true. For any $a, b \in H$:

$a*b=a*b$

By the definition of $a$, $b$, and $H$:

$(a*a)*(b*b)=a*b$

By the associativity of $*$:

$a*(a*(b*b))=a*b$

By the commutativity of $*$:

$a*((b*b)*a)=a*b$

By the associativity of $*$:

$a*(b*(b*a))=a*b$

By the commutativity of $*$:

$a*(b*(a*b))=a*b$

By the associativity of $*$:

$(a*b)*(a*b)=a*b$

Showing us that $a*b$ satisfies the condition to be in $H$.



