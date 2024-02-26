**Exercises 1-13**
2, $\{1,\sqrt{2}\}$
4, $\{1,\sqrt{2},\sqrt{3},\sqrt{6}\}$
4, $\{1,\sqrt{2},\sqrt{3},\sqrt{6}\}$
8, $\{1,\sqrt[3]{2},\sqrt[3]{4},\sqrt{3},\sqrt[3]{2}\sqrt{3},\sqrt[3]{4}\sqrt{3}\}$
6, $\{1,\sqrt[6]{2},\sqrt[6]{4},\sqrt[6]{8},\sqrt[6]{16},\sqrt[6]{32}\}$
4, $\{1,\sqrt{2},\sqrt{3},\sqrt{6}\}$
2, $\{1,\sqrt{6}\}$
4, $\{1,\sqrt[3]{5},\sqrt[3]{25},\sqrt{2},\sqrt[3]{5}\sqrt{2},\sqrt[3]{25}\sqrt{2}\}$
9, $\{1,\sqrt[3]{2},\sqrt[3]{4},\sqrt[3]{3},\sqrt[3]{6},\sqrt[3]{12},\sqrt[3]{9},\sqrt[3]{18},\sqrt[3]{36}\}$
2, $\{1,\sqrt{2}\}$
2, $\{1,\sqrt{2}\}$
1, $\{1\}$
2, $\{1,\sqrt{2}\}$

**Exercises 14-17**
Not sure about countable $\alpha_i$; an algebraic extension is an extension $E$ of a field $F$ s.t. every element of $E$ is algebraic over $F$.
Acceptable.
True.
"every polynomial **in $F[x]$**"

**Exercise 18**
$\R$ is an extension of $\Q$ but $x^2+1$ is irreducible over the algebraic extension of $\Q$ in $\R$, therefore it is not algebraically closed.

**Exercise 19**
a. F
b. T
c. F
d. T
e. F
f. T? ("algebraically closed _in_?")
g. F
h. F
i. F
j. F 

**Exercise 20**
$\{1,\alpha,\ldots,\alpha^n\}$ must be linearly dependent and a linear combination equalling 0 is a polynomial with $\alpha$ as a zero.

**Exercise 21**
With bookkeeping we can show that $\alpha_i\beta_j$ gives a basis of $K$ as an $F$-vector space, where the $\alpha_i$ are a basis of $K$ over $E$ and the $\beta_j$ are a basis of $E$ over $F$.

**Exercise 22**
Since $\C$ is the algebraic closure of $\R$, it is obvious that $\R(a+bi)\subseteq\C$ since $a+bi$ is algebraic over $\R$. It remains to show that $\C\subseteq \R(a+bi)$. Consider any $x+yi\in \C$ s.t. $x,y\in\R$. Applying the field operations; subtracting $a$ from $a+bi$ we obtain $bi$, dividing by $b$ (which we can do since $b\neq0$) we obtain  $i$, then $yi$, then $x+yi$. This means that $\C\subseteq\R(a+bi)$ because fields are closed under their operations, showing that $\C=\R(a+bi)$.

**Exercise 23**
Let $[E:F]=n$. Since $n$ is prime, $n>1$ so $E$ is a proper extension of $F$, therefore there must be $\alpha\in E$ s.t. $\alpha\notin F$. That $E$ is a finite extensions means that $E$ is an algebraic extension thus $\alpha$ must be algebraic over $F$. Its degree must be $m>1$ because $\alpha\notin F$. $[F(\alpha):F]=m$, and by Theorem 31.4 $m|n$. $n$ is prime, so $m=n$ since $m>1$. We have $\deg(\alpha,F)=n=[E:F]$. $\{1,\alpha,\ldots,\alpha^{n-1}\}$ must be linearly independent, because if it were dependent then we would obtain a polynomial in $F$ of degree $<n$ with a zero at $\alpha$, contradicting that $\deg(\alpha,F)=n$. $\{1,\alpha,\ldots,\alpha^{n-1}\}$ is of size $[E:F]$, so since it is linearly independent it must be a basis. This means that every element of $E$ can be expressed as a linear combination of the powers of $\alpha$, so any field containing $F$ and $\alpha$ must contain every element of $E$ since fields are closed. This shows that $E=F(\alpha)$ for any $\alpha\in E-F$ (our choice of $\alpha$ was arbitrary in $E-F$).

**Exercise 24**
$x^2-3$ needs to have a zero in $\Q(\sqrt[3]{2})$ to be reducible over $\Q(\sqrt[3]{2})$. Clearly $x^2-3$ has no zeros in $\Q$, so it is irreducible over $\Q$. Therefore, $\alpha\in \Q(\sqrt[3]{2})$ s.t. $\alpha^2-3=3$ must have $\deg(\alpha,\Q)=2$. Since $\deg(\sqrt[3]{2},\Q)=3$, by Corollary 31.7 $2|3$ which is a contradiction, meaning that no such $\alpha$ exists, meaning that $x^2-3$ has no zeros in $\Q(\sqrt[3]{2})$ and that it is irreducible over $\Q(\sqrt[3]{2})$.

**Exercise 25**
Let $F$ be a field and $a\in F$ s.t. there is no $b\in F$ s.t. $b^2=a$. This means that $x^2-a=0$ has no zeros in $F$, because such a zero would be a suitable $b$. Let $E$ be an extension of $F$ s.t. $\alpha\in E$ is a root of $x^2-a=0$. $\deg(\alpha,F)=2$, so $[F(\alpha):F]=2$. This means that adjoining a square root to a field extends it by degree 1 or 2.
$p(x)=x^{14}-3x^2+12$ is irreducible over $\Q$ because it satisfies the Eisenstein criterion for $p=3$. This means that $\alpha\in\R$ that is a zero of $p(x)$ would be s.t. $\deg(\alpha,\Q)=14$. But 14 divides no power of 2, so it cannot be obtained by adjoining square roots to $\Q$.

(Maybe make more rigorous? But the exercise says "Argue" not "Prove")

**Exercise 26**
To prove that $D$ is a field, we need to prove that every element in it is a unit. Since $F$ is a field, every element of $F$ is a unit. It remains to show that elements of $D-F$ are units.
Let $\alpha\in D-F$. Since $E$ is a finite extension, $\alpha$ is algebraic over $F$ with degree $n$. Since $\alpha^{-1}\in F(\alpha)$, $\alpha^{-1}=a_0+a_1\alpha+\cdots+a_{n-1}\alpha^{n-1}$ for $a_i\in F$. This shows that $\alpha^{-1}$ can be constructed without taking any multiplicative inverses, showing that it must be included in $D$. (In other words, $\alpha^{-1}$ can be obtained with the operations of $D$, and since integral domains are closed $\alpha^{-1}\in D$).

**Exercise 27**
It is sufficient to show that $\sqrt{3}$ and $\sqrt{7}$ can be obtained from the elements of $\Q$ and $\sqrt{3}+\sqrt{7}$ via the field operations. Taking a reciprocal, we have $\frac{1}{\sqrt{7}+\sqrt{3}}=\frac{\sqrt{7}-\sqrt{3}}{(\sqrt{7}+\sqrt{3})(\sqrt{7}-\sqrt{3})}=\frac{\sqrt{7}-\sqrt{3}}{4}$, and $\sqrt{7}-\sqrt{3}$. Adding $\sqrt{3}+\sqrt{7}$, we have $2\sqrt{7}$. Dividing by 2, we have $\sqrt{7}$ giving us one desired value. Subtracting it from $\sqrt{3}+\sqrt{7}$, we have $\sqrt{3}$, giving us our other desired value. This shows that every element of $\Q(\sqrt{3},\sqrt{7})$ is in $\Q(\sqrt{3}+\sqrt{7})$. The other direction is obvious, completing the proof.

**Exercise 28**
The same procedure in the previous exercise can be administered, provided that $\sqrt{a}+\sqrt{b}\neq 0$, since we took the reciprocal of it.

**Exercise 29**
For the sake of contradiction let $\alpha\in E$ be a zero of $p(x)$. Since $p(x)$ is irreducible, its degree is the degree of $\alpha$. By Theorem 31.4, this degree should divide $[E:F]$, which contradicts our hypothesis that the degree of $p(x)$ (and thus the degree of $\alpha$ and $[F(\alpha):F]$) does not divide $[E:F]$. This shows that no element of $E$ is a zero of $p(x)$.

**Exercise 30**
TODO

**Exercise 31**
TODO

**Exercise 32**
