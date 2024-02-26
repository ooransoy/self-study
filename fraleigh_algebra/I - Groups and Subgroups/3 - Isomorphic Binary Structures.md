**Exercise 1**
1. That $\phi$ is injective,
2. That $\phi$ is surjective,
3. And that $\phi$ satisfies the homomorphism property, i.e. $\phi(a*b)=\phi(a)*'\phi(b)$.

**Exercise 2-10**
Yes.
No, $\phi$ is not surjective.
Yes.
Yes.
No, $\phi$ is not surjective.
Yes.
No, $\phi$ is not injective.
Yes.
Yes.

**Exercise 11-15**
No, $\phi$ is not injective.
No, $\phi$ is not injective.
Yes.
Yes.
No, $\phi$ is not surjective. (the only function that would map to $f(x) = 1$ is $f(x) = \frac{1}{x}$ which has a discontinuity at 0 and is not part of $F$)

**Exercise 16**
a.
	$a*b=a+b-1$
	$1$
b.
	$a*b=a+b+1$
	$-1$

**Exercise 17**
a.
	$a*b=ab-a-b+2$
	$2$
b.
	$a*b=ab+a+b$
	$0$

**Exercise 18**
a.
	$a*b=a+b+1$
	$-1$
b.
	$a*b=a+b-\frac{1}{3}$
	$\frac{1}{3}$

**Exercise 19**
a.
	$a*b=\frac{ab+a+b-2}{3}$
	$2$
b.
	$3ab-a-b+\frac{2}{3}$
	$\frac{2}{3}$

**Exercise 20**
What the condition is saying can be viewed as applying $\phi$ before the binary operation ($\phi(a) *' \phi(b)$) gives the same result as applying $\phi$ after the binary operation ($\phi(a*b)$). Hence, $\phi$ "commutes" with the binary operations.

**Exercise 21**
It should be specified that $\phi$ is a bijection (one-to-one and onto), and that the written condition should hold for all $a,b\in S$

**Exercise 22**
"for all $s \in S$" should come before "is an _identity element_"

**Exercise 23**
Given two identity elements $e$ and $\bar{e}$, using the definition of an identity element we get $e*\bar{e}=e$ and $e*\bar{e}=\bar{e}$, showing that $e=\bar{e}$.

**Exercise 24**
a.
	A left identity element $e_L$ for the binary operation $*$ on $S$ is an element such that $e_L * x = x$ for all $x \in S$
b.
	A right identity element $e_R$ for the binary operation $*$ on $S$ is an element such that $x * e_R = x$ for all $x \in S$
Consider the operation defined by the table
```
*|ab
-+--
a|ab
b|ab
```
For this operation, both $a$ and $b$ are left identity elements. For left identity elements, the proof for 3.13 breaks down where we say $e * \bar{e} = e$, because nowhere in the definition of a left identity element do we say that $x*e=x$ for all $x\in S$.

**Exercise 25**
Let $e_L$ be the left identity element for a binary operation $*$ on $S$, and $e_R$ be the right identity element for $*$. By the definition of a left identity, $e_L * e_R = e_R$, and by the definition of a right identity, $e_L * e_R = e_L$, showing that $e_L = e_R$. Therefore for a binary operation there cannot exist distinct left identity and right identity elements.

**Exercise 26**
(Omitting the proof that the inverse of a bijection is a bijection)
We will prove that $\phi^{-1}$ has the homomorphism property, i.e. $\phi^{-1}(a*'b)=\phi^{-1}(a)*\phi^{-1}(b)$ for all $a, b\in S'$.
$a*'b=a*'b$
Since $\phi(\phi^{-1}(x))=x$:
$a*'b=\phi(\phi^{-1}(a))*'\phi(\phi^{-1}(b))$
Applying the homomorphism property of $\phi$:
$a*'b=\phi(\phi^{-1}(a)*\phi^{-1}(b))$
Applying $\phi^{-1}$ to both sides:
$\phi^{-1}(a*'b)=\phi^{-1}(a)*\phi^{-1}(b)$
Which is the homomorphism property for $\phi^{-1}$, thus $\phi^{-1}$ is an isomorphism.

**Exercise 27**
(Omitting the proof that composing a bijection with a bijection yields a bijection)
We will prove that $\psi\circ\phi$ has the homomorphism property, i.e. $(\psi\circ\phi)(a*b)=(\psi\circ\phi)(a)*''(\psi\circ\phi)(b)$.
$\psi(\phi(a))*''\psi(\phi(b))=\psi(\phi(a))*''\psi(\phi(b))$
Applying the homomorphism property of $\psi$:
$\psi(\phi(a)*'\phi(b)))=\psi(\phi(a))*''\psi(\phi(b))$
Applying the homomorphism property of $\phi$:
$\psi(\phi(a*b))=\psi(\phi(a))*''\psi(\phi(b))$
and so:
$(\psi\circ\phi)(a*b)=(\psi\circ\phi)(a)*''(\psi\circ\phi)(b)$
Which is the homomorphism property for $\psi\circ\phi$, thus $\psi\circ\phi$ is an isomorphism.

**Exercise 28**
Reflexivity:
We will prove that the function $\phi(x) = x$ from $A$ to $A$ is an isomorphism.
$\phi$ is injective:
Consider $\phi(a) = \phi(b)$. By the definition of $\phi$, $a = b$, therefore $\phi$ is injective.
$\phi$ is surjective:
For all $y \in A$, there is an $x = y$ satisfies $\phi(x) = y$. Thereore, $\phi$ is surjective.
$\phi$ has the homomorphism property:
$a*b=a*b$
Applying the definition of $\phi$:
$\phi(a*b)=\phi(a)*\phi(b)$
Therefore, $\phi$ is an isomorphism from $A$ to $A$, showing that $A \simeq A$.
Symmetry:
If $A \simeq B$, this means that there is an isomorphism $\phi$ mapping $A$ onto $B$. By the result in exercise 26, $\phi^{-1}$ is an isomorphism mapping $B$ onto $A$, meaning that $A \simeq B$ implies $B \simeq A$.
Transitivity:
Let $A, B, C$ be binary structures such that $\phi$ is an isomorphism from $A$ to $B$ and $\psi$ is an isomorphism from $B$ to $C$. By the result in example 27, $\psi\circ\phi$ is an isomorphism from $A$ to $C$, showing that $A \simeq B$ and $B \simeq C$ implies $A \simeq C$.

We have shown that $\simeq$ is reflexive, symmetric and transitive. Therefore, $\simeq$ is an equivalence relation.

**Exercise 29**
We will show that if $\langle S, *\rangle$ and $\langle S', *'\rangle$ are isomorphic and $*$ is commutative, then $*'$ is commutative. Let $\phi$ be an isomorphism from $S$ to $S'$.
We will prove that $x*'y=y*'x$ for all $x, y \in S'$. Since $\phi$ is surjective, there must exist $a, b \in S$ such that $\phi(a) = x$ and $\phi(b)=y$.
Since $*$ is commutative:
$a*b=b*a$
Because $\phi$ is a function:
$\phi(a*b) = \phi(b*a)$
By the homomorphism property of $\phi$:
$\phi(a)*'\phi(b) = \phi(b)*'\phi(a)$
$x*'y = y*'x$
Showing that $*'$ is commutative.

**Exercise 30**
We will show that if $\langle S, *\rangle$ and $\langle S', *'\rangle$ are isomorphic and $*$ is associative, then $*'$ is associative. Let $\phi$ be an isomorphism from $S$ to $S'$.
We will prove that $(x *' y) *' z= x *' (y *' z)$ for all $x, y, z \in S'$. Since $\phi$ is surjective, there must exist $a, b, c \in S$ such that $\phi(a) = x$, $\phi(b)=y$, and $\phi(c) = z$.
Since $*$ is associative:
$(a*b)*c=a*(b*c)$
Because $\phi$ is a function:
$\phi((a*b)*c)=\phi(a*(b*c))$
By the homomorphism property of $\phi$:
$\phi(a*b)*'\phi(c)=\phi(a)*'\phi(b*c)$
Applying the homomorphism property of $\phi$ again:
$(\phi(a)*'\phi(b))*'\phi(c)=\phi(a)*'(\phi(b)*'\phi(c))$
$(x*'y)*'z=x*'(y*'z)$
Showing that $*'$ is associative.

**Exercise 31**
We will show that if $\langle S, *\rangle$ and $\langle S', *' \rangle$ are isomorphic and for all $b \in S$ there exists an $a \in S$ such that $a*a=b$, then for all $y \in S'$ there exists an $x \in S'$ such that $x*'x=y$. Let $\phi$ be an isomorphism from $S$ to $S'$.
Since $\phi$ is surjective, there must exist $p \in S$ such that $\phi(p) = y$. There must exist $q \in S$ such that $q*q=p$.
Since $\phi$ is a function:
$\phi(q*q)=\phi(p)$
By the homomorphism property of $\phi$:
$\phi(q)*'\phi(q)=\phi(p)$
$\phi(q)*'\phi(q)=y$
So, $\phi(q)$ is an $x \in S'$ satisfying $x*'x=y$.

**Exercise 32**
We will show that if $\langle S, *\rangle$ and $\langle S', *' \rangle$ are isomorphic and there exists $a\in S$ such that $a*a=a$ then there exists $x\in S'$ such that $x*'x=x$. Let $\phi$ be an isomorphism from $S$ to $S'$.
$a*a=a$
Since $\phi$ is a function:
$\phi(a*a)=\phi(a)$
By the homomorphism property of $\phi$:
$\phi(a)*'\phi(a)=\phi(a)$
So, $\phi(a)$ is an $x \in S'$ such that $x*'x=x$.

**Exercise 33**
Let $\phi(a+bi) = \begin{bmatrix}a & -b \\ b & a\end{bmatrix}$
We will show that $\phi$ is injective.
Let $x = a+bi$ and $y = c+di$.
$\phi(x) = \phi(y)$
$\begin{bmatrix}a & -b \\ b & a\end{bmatrix} = \begin{bmatrix}c & -d \\ d & c\end{bmatrix}$
$a=c$, $b =d$
Therefore, $x = y$, showing that $\phi$ is injective.
We will show that $\phi$ is surjective.
For all $a,b\in \mathbb{R}$, $\phi(a+bi) = \begin{bmatrix}a & -b \\ b & a\end{bmatrix}$, therefore $\phi$ is surjective.

**a)**
We will show that $\phi$ has the homomorphism property.
$$\phi((a+bi)+(c+di))=\begin{bmatrix}a & -b \\ b & a\end{bmatrix}+\begin{bmatrix}c & -d \\ d & c\end{bmatrix}$$
Summing out the complex numbers and the matrices:
$$\phi((a+c) + (b+d)i)=\begin{bmatrix}a+c & -b-d \\ b+d & a+c\end{bmatrix}$$
We get the definition of $\phi$, completing the proof.
**b)**
We will show that $\phi$ has the homomorphism property.
$$\phi((a+bi)(c+di))=\begin{bmatrix}a & -b \\ b & a\end{bmatrix}\begin{bmatrix}c & -d \\ d & c\end{bmatrix}$$
Multiplying out the complex numbers and the matrices:
$$\phi((ac-bd) + (ad+bc)i)=\begin{bmatrix}ac-bd & -ad-bc \\ ad+bc & ac-bd\end{bmatrix}$$
We get the definition of $\phi$, completing the proof.

**Exercise 34**
1
```
 |ab
-+--
a|aa
b|aa
```
2
```
 |ab
-+--
a|ab
b|aa
```
3
```
 |ab
-+--
a|aa
b|ba
```
4
```
 |ab
-+--
a|ba
b|aa
```
5
```
 |ab
-+--
a|aa
b|ab
```
6
```
 |ab
-+--
a|ab
b|ba
```
7
```
 |ab
-+--
a|bb
b|aa
```
8
```
 |ab
-+--
a|ba
b|ba
```
9
```
 |ab
-+--
a|aa
b|bb
```
10
```
 |ab
-+--
a|ab
b|ab
```

