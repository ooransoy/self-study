**Exercises 1-4**
$f+g$: $2x^2+5$, $fg$: $2x^2+4x+6$
$f+g$: $0$, $fg$: $x^2+1$
$f+g$: $5x^2+5x+1$, $fg$: $x^3+5x$
$f+g$: $3x^4+2x^3+4x^2+3$: $fg$: $x^7+2x^6+4x^5+x^3+2x^2+3$

**Exercise 5**
16

**Exercise 6**
125

**Exercises 7-8**
7
3+i

**Exercises 9-11**
$(3^4+2(3))(3^3-3(3)^2+3)=87(3)=2$
$(127)(103)(81)=6$
$5+5+4=0$

**Exercises 12-15**
$\{1\}$
$\{2, 3\}$
$\{0, 4\}$
$\{0, 1, 3\}$

**Exercise 16**
$3^3+3(3)-2(3)+1=2+4-1+1=1$ 

**Exercise 17**
$2x^3+3x^2+2x+3=(2x+3)(x^2+1)$
$\{0,1,2,3\}$
Note: almost forgot $0$, accidentally cancelling a 0 with Fermat's theorem

**Exercise 18**
With only a finite amount of $i$ s.t. $a_i\neq 0$, otherwise correct.

**Exercise 19**
$F[x]\to F$, otherwise correct.

**Exercise 20**
$f(y,x)=(y+1)x^4+(3y^3)x^3+(y^2-3)x^2+$
$(2y^3-6y^2-2y)x+(y^2+2)$

**Exercise 21**
$(x-5)(x-n)$

**Exercise 22**
$2x$

**Exercise 23**
a. T
b. T
c. T
d. T
e. F
f. F
g. T
h. T
i. T
j. F

**Exercise 24**
Let $f(x),g(x)\in D[x]$ s.t. $f(x)\neq 0$ and $g(x)\neq 0$. Let $i$ be the degree of $f(x)$, let $j$ be the degree of $g(x)$. (We know that they are not undefined because the polynomials are nonzero.) Let $a$ be the coefficient of $x^i$ in $f(x)$, and let $b$ be the coefficient of $x^j$ in $g(x)$. We know that they are nonzero. By the definition of polynomial multiplication, the coefficient of $x^{i+j}$ will be $ab$. Since $a$ and $b$ are nonzero and $D$ has no zero divisors, $ab$ must be nonzero. This gives at least one nonzero coefficient of $f(x)g(x)$ showing that $f(x)g(x)\neq 0$, completing the proof that $D[x]$ has no zero divisors and is an integral domain. (For the other conditions: $1$ is unity, and $D[x]$ is obviously commutative.)

**Exercise 25**
a.
The units of $D[x]$ are precisely the units of $D$.
b.
$\{1, -1\}$
c.
$\{1,2,3,4,5,6\}$

**Exercise 26**
Let $f(x),g(x),h(x)\in R[x]$ s.t. $f(x)=\sum_{i=0}^\infty a_ix^i$, $g(x)=\sum_{i=0}^\infty b_ix^i$, and $h(x)=\sum_{i=0}^\infty c_ix^i$.
$f(x)(g(x)+h(x))=(\sum_{i=0}^\infty a_ix^i)(\sum_{i=0}^\infty (b_i+c_i)x^i)$
$=\sum_{i=0}^\infty\sum_{j=0}^ia_{i-j}(b_j+c_j)x^i$
$=\sum_{i=0}^\infty\sum_{j=0}^i(a_{i-j}b_j+a_{i-j}c_j)x^i$
$=\sum_{i=0}^\infty\sum_{j=0}^ia_{i-j}b_jx^i+a_{i-j}c_jx^i$
$=(\sum_{i=0}^\infty\sum_{j=0}^ia_{i-j}b_jx^i)+(\sum_{i=0}^\infty\sum_{j=0}^ia_{i-j}c_jx^i)$
$=f(x)g(x)+f(x)h(x)$
showing that $R[x]$ is left distributive.

**Exercise 27**
a.
We have $D(\sum_{i=0}^\infty a_ix^i)=\sum_{i=1}^\infty i\cdot a_ix^{i-1}$
Let $f(x),g(x)\in R[x]$ s.t. $f(x)=\sum_{i=0}^\infty a_ix^i$ and $g(x)=\sum_{i=0}^\infty b_ix^i$.
$D(f(x)+g(x))=D(\sum_{i=0}^\infty(a_i+b_i)x^i)$
$=\sum_{i=1}^\infty i\cdot (a_i+b_i)x^{i-1}$
$=\sum_{i=1}^\infty i\cdot (a_ix^{i-1}+b_ix^{i-1})$
$=\sum_{i=1}^\infty (i\cdot a_ix^{i-1}+i\cdot b_ix^{i-1})$
$=\sum_{i=1}^\infty i\cdot a_ix^{i-1} + \sum_{i=1}^\infty i\cdot b_ix^{i-1}$
$=D(f(x))+D(g(x))$
showing that $D$ is a homomorphism from $\langle F[x], +\rangle$ to itself.

$D$ is not a ring homomorphism. $D((x)(x))=D(x^2)=2x\neq1=(1)(1)=D(x)D(x)$
b.
Precisely the elements of $F$.
c.
TODO

**Exercise 28**
TODO

**Exercise 29**
Additive commutativity (this will allow us to check only one side of symmetric properties):
$(\phi+\psi)(x)=\phi(x)+\psi(x)=\psi(x)+\phi(x)=(\psi+\phi)(x)$
Additive associativity:
$((\phi+\psi)+\chi)(x)=(\phi+\psi)(x)+\chi(x)=\phi(x)+\psi(x)+\chi(x)$
$=\phi(x)+(\psi+\chi)(x)=(\phi+(\psi+\chi))(x)$
Additive identity: $\iota(x)=0$
$(\phi+\iota)(x)=\phi(x)+\iota(x)=\phi(x)+0=\phi(x)$
Additive inverse: $\psi(x)=-\phi(x)$
$(\phi+\psi)(x)=\phi(x)+\psi(x)=\phi(x)-\phi(x)=0=\iota(x)$
Multiplicative associativity:
$((\phi\psi)\chi)(x)=(\phi\psi)(x)\chi(x)=$
$\phi(x)\psi(x)\chi(x)=\phi(x)(\psi\chi)(x)=(\phi(\psi\chi))(x)$
Distributivity:
$(\phi(\psi+\chi))(x)=\phi(x)(\psi+\chi)(x)=\phi(x)(\psi(x)+\chi(x))$
$=\phi(x)\psi(x)+\phi(x)\chi(x)=(\phi\psi)(x)+(\phi\chi)(x)=(\phi\psi+\phi\chi)(x)$
showing that $R^R$ is a ring.

**Exercise 30**
TODO

**Exercise 31**
TODO