**Exercise 1**
Maximal and prime:
$\langle 2\rangle$
$\langle 3\rangle$
Only prime:
N/A

**Exercise 2**
Maximal and prime:
$\langle 2\rangle$
$\langle 3\rangle$
Only prime:
N/A
Not prime:
$\langle 4\rangle$
$\langle 6\rangle$

**Exercise 3**
Maximal and prime:
$\langle (1,0)\rangle$
$\langle (0,1)\rangle$
Only prime:
N/A

**Exercise 4**
Maximal and prime:
$\langle (0,1)\rangle$
$\langle (1,0), (0,2)\rangle$
Only prime:
N/A
Not prime:
$\langle (1,0)\rangle$ ($(1,2)(1,2)=(1,0)$)
$\langle (0,2)\rangle$ ($(1,2)(0,1)=(0,2)$)

Remark:
In a finite commutative ring, every prime ideal is maximal. If $N$ is prime, $R/N$ is an integral domain. Since $R$ is finite, $R/N$ is also finite. All finite integral domains are fields, so $R/N$ is a field, showing that $N$ is maximal.

**Exercise 5**
For $\mathbb{Z}_3[x]/\langle x^2+c\rangle$ to be a field, it must be that $\langle x^2+c\rangle$ is a maximal ideal. By Theorem 27.25, it must be that $x^2+c$ is irreducible. $c$ is one of $0,1,2$. Checking $c=0$, $x^2=xx$. Checking $c=2$, $x^2+2=x^2-1=(x-1)(x+1)$. Checking $c=1$, $x^2+1$ has no roots and is of degree 2, so by Theorem 23.10 it is irreducible. Only $c=1$ makes $\mathbb{Z}_3[x]/\langle x^2+c\rangle$ a field.

**Exercise 6**
$x^3+x^2+c$ must be irreducible over $\mathbb{Z}_3$. Since it is of degree 3, it suffices for us to check if it has any roots. $c=0$ has $x=0$ as a root, and $c=1$ has $x=1$ as a root. $c=2$ has no roots, so only $c=2$ makes $\mathbb{Z}_3[x]/\langle x^3+x^2+c\rangle$ a field.

**Exercise 7**
$x^3+cx^2+1$ must be irreducible over $\mathbb{Z}_3$. Since it is of degree 3, it suffices for us to check if it has any roots. $c=0$ has a root at $x=2$, $c=1$ has a root at $x=1$, and $c=2$ has no roots. Only $c=2$ works.

**Exercise 8**
$x^2+x+c$ is of degree 2, only checking for roots. By an exhaustive computation, $c=1$ and $c=2$ have no roots, meaning that only $c=1$ and $c=2$ make $\mathbb{Z}_5[x]/\langle x^2+x+c\rangle$ a field.

**Exercise 9**
$x^2+cx+1$
By computation, only $c=1$ and $c=4$.

Remark:
```python
def zeros(s, m):
    return [i for i in range(m) if eval(s.replace("x", str(i)))%m == 0]
c = 1 # or 4
zeros(f"x**2+{c}*x+1", 5) # []
```

**Exercise 10**
"...not contained in any _proper_ ideal of $R$"

**Exercise 11**
wtf?
A prime ideal is an ideal $N$ of a ring $R$ s.t. for any $a,b\in R$, $ab\in N$ implies $a\in N\ \vee\ b\in N$.

**Exercise 12**
Correct.

**Exercise 13**
Correct.

**Exercise 14**
a. F (Only in finite commutative rings with unity.)
b. T
c. T
d. F (It's $\mathbb{Q}$. $\mathbb{R}$ is not a prime field, but its prime field is $\mathbb{Q}$.)
e. T
f. T ($\mathbb{Z}_2\times\mathbb{Z}_2$ has zero divisors ($(0,1)(1,0)=(0,0)$) but contains the prime field $\mathbb{Z}_2$ as a subring)
g. T
h. F ($xx\in\langle x^2\rangle$, so $\langle x^2\rangle$ is not prime)
i. T (Theorem 27.24)
j. F ($\langle x^2\rangle\subseteq\langle x\rangle$)
Remark: $\langle x^n\rangle$ is the ideal of $F[x]$ consisting of all elements of degree $\geq n$.

**Exercise 15**
$\langle(1,0), (0,2)\rangle$

**Exercise 16**
$\langle(1,0)\rangle$

**Exercise 17**
$\langle(2,0), (0,2)\rangle$
Not prime, $(2,1)(1,0)=(2,0)\in N$

**Exercise 18**
No. $x^2-5x+6$ is reducible as $(x-6)(x+1)$, so the factor ring is not a field.

**Exercise 19**
Yes. $x^2-6x+6$ is irreducible, shown by checking the Eisenstein criterion for $p=$ either $2$ or $3$.

**Exercise 20**
If $R/N$ is a field, it has no nontrivial proper ideals. If there were an ideal $M$ s.t. $N\subset M\subset R$, then $R/N$ would contain a proper nontrivial ideal isomorphic to $R/M$, contradicting that it is a field.

**Exercise 21**
TODO

**Exercise 22**
TODO

**Exercise 23**
TODO

**Exercise 24**
Let $N$ be a prime ideal of $R$. $R/N$ is an integral domain. Since $R$ is finite, $R/N$ is finite. $R/N$ is a finite integral domain. All finite integral domains are fields, so $R/N$ is a field. This means that $N$ is a maximal ideal, completing the proof.

**Exercise 25-26**
Consider $\langle2\rangle$ and $\langle3\rangle$ of $\mathbb{Z}_6$.

$\langle3\rangle$ is isomorphic to $\mathbb{Z}_2$.
$\langle3\rangle$:
```
+|03 x|03
-+-- -+--
0|03 0|00
3|30 3|03
```
$\mathbb{Z}_2$:
```
+|01 x|01
-+-- -+--
0|01 0|00
1|10 1|01
```

$\langle2\rangle$ is isomorphic to $\mathbb{Z}_3$.
$\langle2\rangle$:
```
+|042 x|042
-+--- -+---
0|042 0|000
4|420 4|042
2|204 2|024
```
$\mathbb{Z}_3$:
```
+|012 x|012
-+--- -+---
0|012 0|000
1|120 1|012
2|201 2|021
```

**Exercise 27**
No. As the characteristic of a subdomain is equal to that of the domain (proof omitted), $p$ and $q$ would be equal to the characteristic of the domain leading to $p=q$.

**Exercise 28**
Let $M$ be a maximal ideal of $R$, a commutative ring with unity. Let $a,b\in R$ s.t. $ab\in M$. It is sufficient to prove that $a\notin M\implies b\in M$.
Since $M$ is maximal, the only ideal properly containing it is $R$. The smallest ideal $\{ra+m\ |\ r\in R,\ m\in M\}$ containing both $M$ and $a$ would properly contain $M$ since $a\notin M$, so that ideal would be $R$. This means it contains $1$ as well, meaning that $1=ra+m$ for some $r\in R$ and $m\in M$. Multiplying both sides by $b$, we have $b=rab+mb$. $ab\in M$, so $rab\in M$. $m\in M$ and $M$ is an ideal, so $mb\in M$. $rab+mb\in M$, meaning that $b\in M$, completing the proof.

**Exercise 29**
If $N$ is a maximal ideal of $R$, then $R/N$ is a field. Therefore it has no proper nontrivial ideals. It is obviously nontrivial, showing that $R/N$ is simple.
Conversely, if $R/N$ is nontrivial and has no proper nontrivial ideals it is a field, therefore $N$ is a maximal ideal.

**Exercise 30**
Let $N$ be a proper nontrivial prime ideal of $F[x]$. By Theorem 27.24, $N$ is a principal ideal. Let $p(x)\in F[x]$ be a generator of $N$, i.e. $N=\langle f(x)\rangle$. $p(x)$ is obviously of positive degree since $N$ is proper. (If it had degree 0, it would be a unit, and the ideal would be equal to the ring, meaning the ideal is improper.) Let $r(x),s(x)\in F[x]$ s.t. $r(x)s(x)=p(x)$. $r(x)s(x)\in N$, and since $N$ is a prime ideal, either $r(x)\in N$ or $s(x)\in N$. WLOG, let $r(x)\in N$. Obviously, $p(x)$ is of minimal positive degree $k$ out of all elements in $N$. This means all elements of $N$ are of degree at least $k$, meaning that $r(x)$ is at least of degree $k$. Since it divides $r(x)$, it is exactly of degree $k$, so $s(x)$ is of degree 0. This shows that $p(x)$ is irreducible. $N=\langle p(x)\rangle$, therefore $N$ is a maximal ideal by Theorem 27.25.

**Exercise 31**
That $f(x)$ divides $g(x)$ is equivalent to that there exists $q(x)$ s.t. $f(x)q(x)=g(x)$.
Assume that such $q(x)$ exists. Since $\langle f(x)\rangle$ is an ideal of $F[x]$ and $f(x)\in \langle f(x)\rangle$, $f(x)q(x)=g(x)$ is also $\in\langle f(x)\rangle$.
Conversely, if $g(x)\in \langle f(x)\rangle$, we consider the two cases where the degree of $f(x)$ is 0 or positive. If $f(x)$ is of degree 0, it is a unit, and every ideal containing a unit is equal to the ring itself, meaning it contains $g(x)$.
Otherwise, applying the division algorithm on $g(x)$ by $f(x)$ gives $g(x)=f(x)q'(x)+r(x)$, where $r(x)$ has degree less than $f(x)$. Since $f(x)$ is of lowest positive degree in $\langle f(x)\rangle$, $r(x)$ having degree lower than it means that it has degree $0$. Since $g(x)\in \langle f(x)\rangle$ and $f(x)q'(x)\in \langle f(x)\rangle$, we have $r(x)\in \langle f(x)\rangle$ since ideals are closed under addition. Since $f(x)$ is of positive degree and $r(x)$ is of degree 0, it must be that $r(x)=0$ so $g(x)=f(x)q'(x)$, meaning $f(x)$ divides $g(x)$.

**Exercise 32**
$N$ is an additive subgroup:
$r_1(x)f(x)+s_1(x)g(x)\in N$
$r_2(x)f(x)+s_2(x)g(x)\in N$
$r_1(x)f(x)+s_1(x)g(x)+r_2(x)f(x)+s_2(x)g(x)$
$=r_1(x)f(x)+r_2(x)f(x)+s_1(x)g(x)+s_2(x)g(x)$
$=(r_1(x)+r_2(x))f(x)+(s_1(x)+s_2(x))g(x)\in N$
$N$ is invariant under multiplication:
$p(x)\in F[x]$, $r(x)f(x)+s(x)g(x)\in N$
$(r(x)f(x)+s(x)g(x))p(x)$
$=(r(x)p(x))f(x)+(s(x)p(x))g(x)\in N$

WLOG, let $f(x)$ be of degree lower than $g(x)$. We will show the contrapositive, that if both $f(x)$ and $g(x)$ are irreducible, $N=F[x]$.
Since $g(x)$ is irreducible, $\langle g(x)\rangle$ is maximal. Since $g(x)$ is of positive degree higher than $f(x)$ which also has positive degree, $f(x)\notin \langle g(x)\rangle$. $N$ contains both $\langle g(x)\rangle$ and $f(x)$ so $N$ properly contains $\langle g(x)\rangle$, which was maximal so $N=F[x]$.

**Exercise 33**
TODO

**Exercise 34**
Let $a_1,a_2\in A$ and $b_1,b_2\in B$. $a_1+b_1\in A+B$ and $a_2+b_2\in A+B$. $a_1+b_1-(a_2+b_2)=(a_1-a_2)+(b_1-b_2)\in A+B$ since $a_1+a_2\in A$ and $b_1+b_2\in B$, showing that $A+B$ is closed under subtraction. Let $r\in R$, $a\in A$ and $b\in B$. $a+b\in A+B$. $r(a+b)=ra+rb\in A+B$, since $ra\in A$ and $rb\in B$ following from $A$ and $B$ being ideals of $R$. This shows that $A+B$ is an ideal.

Let $b\in B$. Since $0\in A$, $0+b\in A+B$, showing that $B\subseteq A+B$. This generalizes to $A\subseteq A+B$ as well.

**Exercise 35**
It is trivial but very tedious to prove that $AB$ is an additive subgroup, so it is omitted here.
Let $n\in \mathbb{Z}^+$, $a_i\in A$ and $b_i \in B$. $\sum_{i=0}^n a_ib_i\in AB$. $r(\sum_{i=0}^n a_ib_i)=\sum_{i=0}^n ra_ib_i\in AB$ since $ra_i\in A$ from $A$ being an ideal, showing that $AB$ is an ideal.
Since $A$ is an ideal, $a_ib_i\in A$. This means that all terms of an element in $AB$ are also in $A$, meaning that it is a sum of elements in $A$ and therefore an element of $A$ itself. The same can be seen for $B$, since it is also an ideal. This means that $AB\subseteq A$ and $AB\subseteq B$, meaning $AB\subseteq A\cap B$.

**Exercise 36**
Let $r_1,r_2\in A : B$. Let $b\in B$. $r_1b\in B$, $r_2b\in B$. $r_1b-r_2b=(r_1-r_2)b\in B$, showing that $r_1-r_2\in A:B$.
Let $n\in A:B$ and $r\in R$. $nb\in B$, and since $B$ is an ideal, $rnb\in B$. $(rn)b\in B$, so $rn\in A:B$, showing that $A:B$ is an ideal.

**Exercise 37**
$\begin{bmatrix}a&b\\0&0\end{bmatrix}-\begin{bmatrix}c&d\\0&0\end{bmatrix}=\begin{bmatrix}a-c&b-d\\0&0\end{bmatrix}\in S$, showing that $S$ is closed under subtraction.
$\begin{bmatrix}a&b\\0&0\end{bmatrix}\begin{bmatrix}c&d\\0&0\end{bmatrix}=\begin{bmatrix}ac&ad\\0&0\end{bmatrix}\in S$, showing that $S$ is a subring.
$\begin{bmatrix}a&b\\0&0\end{bmatrix}\begin{bmatrix}c&d\\ e&f\end{bmatrix}=\begin{bmatrix}ac+be&ad+bf\\0&0\end{bmatrix}\in S$, showing that $S$ is right ideal.
$\begin{bmatrix}c&d\\ e&f\end{bmatrix}\begin{bmatrix}a&b\\0&0\end{bmatrix}=\begin{bmatrix}ac&bc\\ ae&be\end{bmatrix}\notin S$, showing that $S$ is _not_ a left ideal.

**Exercise 38**
For the ideal to be proper, it must not contain any units. Recalling Exercise 14 of Section 24, these are:
$\begin{bmatrix}1&0\\0&1\end{bmatrix}$, $\begin{bmatrix}0&1\\1&0\end{bmatrix}$, $\begin{bmatrix}1&1\\1&0\end{bmatrix}$, $\begin{bmatrix}1&1\\0&1\end{bmatrix}$, $\begin{bmatrix}0&1\\1&1\end{bmatrix}$, $\begin{bmatrix}1&0\\1&1\end{bmatrix}$. A proper ideal mustn't contain any of these six matrices.

$\begin{bmatrix}1&0\\0&0\end{bmatrix}\begin{bmatrix}0&1\\1&1\end{bmatrix}=\begin{bmatrix}0&1\\0&0\end{bmatrix}$, so any ideal containing $\begin{bmatrix}1&0\\0&0\end{bmatrix}$ must also contain $\begin{bmatrix}0&1\\0&0\end{bmatrix}$.
$\begin{bmatrix}0&1\\1&1\end{bmatrix}\begin{bmatrix}0&1\\0&0\end{bmatrix}=\begin{bmatrix}0&0\\0&1\end{bmatrix}$, so any ideal containing $\begin{bmatrix}0&1\\0&0\end{bmatrix}$ must also contain $\begin{bmatrix}0&0\\0&1\end{bmatrix}$.
$\begin{bmatrix}0&0\\0&1\end{bmatrix}\begin{bmatrix}1&1\\1&0\end{bmatrix}=\begin{bmatrix}0&0\\1&0\end{bmatrix}$, so any ideal containing $\begin{bmatrix}0&0\\0&1\end{bmatrix}$ must also contain $\begin{bmatrix}0&0\\1&0\end{bmatrix}$.
$\begin{bmatrix}1&1\\1&0\end{bmatrix}\begin{bmatrix}0&0\\1&0\end{bmatrix}=\begin{bmatrix}1&0\\0&0\end{bmatrix}$, so any ideal containing $\begin{bmatrix}0&0\\1&0\end{bmatrix}$ must also contain $\begin{bmatrix}1&0\\0&0\end{bmatrix}$.

Combining these four statements, we have that an ideal must contain either all or none of  $\begin{bmatrix}0&1\\0&0\end{bmatrix}$, $\begin{bmatrix}0&0\\0&1\end{bmatrix}$, $\begin{bmatrix}0&0\\1&0\end{bmatrix}$, $\begin{bmatrix}1&0\\0&0\end{bmatrix}$. If it contains all four matrices, it also contains $\begin{bmatrix}0&1\\1&1\end{bmatrix}=\begin{bmatrix}0&1\\0&0\end{bmatrix}+\begin{bmatrix}0&0\\0&1\end{bmatrix}+\begin{bmatrix}0&0\\1&0\end{bmatrix}$ since an ideal is a subring and therefore closed under addition. But $\begin{bmatrix}0&1\\1&1\end{bmatrix}$ is a unit, so this would mean that the ideal is improper, so an ideal mustn't contain any four of these matrices.

Considering that
$\begin{bmatrix}1&1\\0&0\end{bmatrix}\begin{bmatrix}1&0\\0&0\end{bmatrix}=\begin{bmatrix}1&0\\0&0\end{bmatrix}$
$\begin{bmatrix}0&0\\1&1\end{bmatrix}\begin{bmatrix}0&0\\1&0\end{bmatrix}=\begin{bmatrix}0&0\\1&0\end{bmatrix}$
$\begin{bmatrix}0&1\\0&0\end{bmatrix}\begin{bmatrix}1&0\\1&0\end{bmatrix}=\begin{bmatrix}1&0\\0&0\end{bmatrix}$
$\begin{bmatrix}0&0\\0&1\end{bmatrix}\begin{bmatrix}0&1\\0&1\end{bmatrix}=\begin{bmatrix}0&0\\0&1\end{bmatrix}$
, a proper ideal must not contain any of $\begin{bmatrix}1&1\\0&0\end{bmatrix}$, $\begin{bmatrix}0&0\\1&1\end{bmatrix}$, $\begin{bmatrix}1&0\\1&0\end{bmatrix}$, and $\begin{bmatrix}0&1\\0&1\end{bmatrix}$.

Lastly, $\begin{bmatrix}1&1\\1&1\end{bmatrix}\begin{bmatrix}0&1\\0&0\end{bmatrix}=\begin{bmatrix}0&1\\0&1\end{bmatrix}$, therefore a proper ideal cannot contain $\begin{bmatrix}1&1\\1&1\end{bmatrix}$ either.

We have eliminated 15 matrices as unfit to be part of a proper ideal. Therefore the only matrix that a proper ideal can contain is the remaining 16th matrix - the zero matrix. This means that a proper ideal of $M_2(\mathbb{Z}_2)$ must be trivial, showing that $M_2(\mathbb{Z}_2)$ is simple.
