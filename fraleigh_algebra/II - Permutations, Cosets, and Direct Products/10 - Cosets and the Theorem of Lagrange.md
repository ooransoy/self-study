**Exercise 1-5**
$\{n | n\in\mathbb{Z}\}$
$\{1+n | n\in\mathbb{Z}\}$
$\{2+n | n\in\mathbb{Z}\}$
$\{3+n | n\in\mathbb{Z}\}$

$\{n | n\in\mathbb{Z}\}$
$\{2+n | n\in\mathbb{Z}\}$

$\{0, 2, 4, 6, 8, 10\}$
$\{1, 3, 5, 7, 9, 11\}$

$\{0, 4, 8\}$
$\{1, 5, 9\}$
$\{2, 6, 10\}$
$\{3, 7, 11\}$

$\{n,n+18\}$ for $0 \leq n < 18$

**Exercise 6**
$\{\rho_0, \mu_2\}$
$\{\rho_1, \delta_2\}$
$\{\rho_2, \mu_1\}$
$\{\rho_3, \delta_1\}$

**Exercise 7**
$\{\rho_0, \mu_2\}$
$\{\rho_1, \delta_1\}$
$\{\rho_2, \mu_1\}$
$\{\rho_3, \delta_2\}$

**Exercise 8**
```
   | p0 u2 p1 d2 p2 u1 p3 d1
---+------------------------
p0 | p0 u2 p1 d2 p2 u1 p3 d1
u2 | u2 p0 d1 p3 u1 p2 d2 p1
p1 | p1 d2 p2 u1 p3 d1 p0 u2
d2 | d2 p1 u2 p0 d1 p3 u1 p2
p2 | p2 u1 p3 d1 p0 u2 p1 d2
u1 | u1 p2 d2 p1 u2 p0 d1 p3
p3 | p3 d1 p0 u2 p1 d2 p2 u1
d1 | d1 p3 u1 p2 d2 p1 u2 p0
```
No coset group

**Exercise 9**
$\{\rho_0, \rho_2\}$
$\{\rho_1, \rho_3\}$
$\{\mu_1, \mu_2\}$
$\{\delta_1, \delta_2\}$

**Exercise 10**
Yes, the right cosets of $\{\rho_0, \rho_2\}$ are the same as its left cosets.

**Exercise 11**
```
   | p0 p2 p1 p3 u1 u2 d1 d2
---+------------------------
p0 | p0 p2 p1 p3 u1 u2 d1 d2
p2 | p2 p0 p3 p1 u2 u1 d2 d1
p1 | p1 p3 p2 p0 d1 d2 u2 u1
p3 | p3 p1 p0 p2 d2 d1 u1 u2
u1 | u1 u2 d2 d1 p0 p2 p3 p1
u2 | u2 u1 d1 d2 p2 p0 p1 p3
d1 | d1 d2 u1 u2 p1 p3 p0 p2
d2 | d2 d1 u2 u1 p3 p1 p2 p0
```
We seem to get a coset group isomorphic to the Klein 4-group.

**Remark:** I just noticed that $\rho_2$ commutes with all of the group elements, whereas $\mu_2$ does not. Maybe the elements of the subgroup need to commute with every element of the group for the subgroup's cosets to create a coset group?
**Edit:** Example 10.7 shows that commutativity is not necessary. Is it the partition into left cosets being the same as the partition into right cosets?

**Exercise 12**
8

**Exercise 13**
3

**Exercise 14**
4

**Exercise 15**
$\sigma = \begin{pmatrix}1&2&3&4&5\\ 2&3&5&1&4 \end{pmatrix} = (1, 2, 3, 5, 4)$
$|\langle\sigma\rangle|=5$
$(S_5:\langle\sigma\rangle)=24$

**Exercise 16**
$\sigma = \begin{pmatrix}1&2&3&4&5&6\\ 2&4&6&5&1&3 \end{pmatrix} = (1, 2, 4, 5)(3, 6)$
$|\langle\mu\rangle|=4$
$(S_6:\langle\mu\rangle)=180$

**Exercise 17**
Correction: $H \leq G$

**Exercise 18**
Correction: left cosets, not right cosets

**Exercise 19**
a. T
b. T
c. T
d. F
e. T
f. F
g. T
h. T!!!
i. F (if a group of order $n$ is not cyclic, then there is no element of order $n$, and $n$ divides the order of the group)
j. T

**Exercises 20-24**
Impossible. If a group is abelian, its left and right cosets will be the same.
For any group $G$, the subgroup $G$ will partition into a single cell.
The trivial subgroup of any group of order 6 will partition into 6 cells.
Impossible. A partitioning cannot have more cells than the original set, as some partitions will need to be empty, invalidating the partitioning.
Impossible. The number of cells needs to divide the order of the group (by Lagrange's theorem).

**Exercise 25**
The order of the group will be the order of the subgroup multiplied by how many cosets it has, therefore both the number of cosets and the order of the subgroup must divide the order of the group.

**Exercise 26**
Reflexive:
$e\in H$
$aa^{-1} \in H$ for all $a$
$a\sim_Ra$ for all $a$
Symmetric:
$a\sim_Rb$
$ab^{-1}\in H$
$(ab^{-1})^{-1}\in H$
$ba^{-1}\in H$
$b\sim_Ra$
Transitive:
$a\sim_Rb$
$b\sim_Rc$
$ab^{-1}\in H$
$bc^{-1}\in H$
$ab^{-1}bc^{-1} \in H$
$ac^{-1} \in H$
$a\sim_Rc$

**Exercise 27**
$f(a) = ag$
Surjective:
$Hg=\{hg|h\in H\}=\{f(h)|h\in H\}$
Injective:
$f(a)=f(b)$
$ag=bg$
$a=b$ by simple cancellation

**Exercise 28**
$f_a(x)=a^{-1}xa$ is a permutation of $H$ for any $a\in G$
Surjective:
Take any $y\in H$
$(a^{-1})^{-1}ya^{-1}$ must also be in $H$
$aya^{-1}$ is a sufficient $x\in H$ where $f_a(x)=y$ since $f_a(x)=f_a(aya^{-1})=a^{-1}aya^{-1}a=eye=y$
Injective:
Proving injectivity is trivial by using simple cancellation.

Take any $a\in G$
$aH=\{ah\ |\ h\in H\}$
Since $f_a$ is a permutation of $H$,
$aH=\{af_a(h)\ |\ h\in H\}$
$aH=\{aa^{-1}ha\ |\ h\in H\}$
$aH=\{ha\ |\ h\in H\}$
$aH=Ha$

**Exercise 29**
Take any $g\in G$
$g^{-1}Hg = g^{-1}gH = H$ since $Hg=gH$

**Exercise 30**
$H=\{\rho_0, \mu_2\}$, $G=D_4$, $a=\rho_1$, $b=\delta_2$
$\rho_1H=\delta_2H$ however $\mu_2\rho_1=\delta_1$ is in $H\rho_1$ but not $H\delta_2$ since $\rho_2\delta_2=\delta_1$ and $\rho_2$ is not in $H$.

**Exercise 31**
$b=eb\in Hb$
$b\in Ha$ from $Ha=Hb$

**Exercise 32**
$aH=bH$
$\{ah\ |\ h\in H\}=\{bh\ |\ h\in H\}$
$\{ah\ |\ h\in H\}=\{bh\ |\ h\in H\}$
since $f(h)=h^{-1}$ is a permutation of $H$,
$\{ah^{-1}\ |\ h\in H\}=\{bh^{-1}\ |\ h\in H\}$
$\{(ah^{-1})^{-1}\ |\ h\in H\}=\{(bh^{-1})^{-1}\ |\ h\in H\}$
$\{ha^{-1}\ |\ h\in H\}=\{hb^{-1}\ |\ h\in H\}$
$Ha^{-1}=Hb^{-1}$

**Exercise 33**
TODO

**Exercise 34**
By Lagrange's theorem, any proper subgroup must be of order $p$, $q$, or $1$. By Corollary 10.11, the first two cases are cyclic, and the last case is trivially cyclic.

**Exercise 35**
TODO

**Exercise 36**
Suppose for the sake of contradiction that there are more than one elements of order 2. Let $a$ and $b$ be distinct elements of order 2. The subgroup generated by $\{a, b\}$ will have $4$ elements. By Lagrange's theorem, $4$ should divide $2n$. This is a contradiction because $n$ is odd, completing the proof.

**Exercise 37**
Since there are at least two elements, at least one element must be non-identity. Call this element $a$. $\langle a\rangle$ is a nontrivial subgroup of $G$, and since $G$ has no proper nontrivial subgroups, $\langle a\rangle=G$  must be the case, showing that $G$ is cyclic. Any infinite cyclic group is isomorphic to $\mathbb{Z}$, which does have nontrivial proper subgroups, so $G$ must be finite. Any finite cyclic group of composite order will also have a nontrivial proper subgroup, as the order can be factored into $n=xy$ where $x>1, y>1$ and $\langle a^x\rangle$ will be a proper nontrivial subgroup of $G$ since $x$ is not coprime to $n$.

**Exercise 38**
TODO

**Exercise 39**
Since the index of $H$ is 2, there is only one left coset that is not $H$ itself. An element of $G$ is either in $H$ or in that left coset. Likewise, every element is either in $H$ or in the single right coset that is not $H$ itself. $H$ is both a left coset and a right coset, so it will suffice to show that the remaining left and right cosets are the same. If an element is in the left coset, it is not in $H$ and therefore in the right coset, and vice versa. This shows that the two sets are equivalent, showing that the 2 left cosets of $H$ are the same as its 2 right cosets.

**Exercise 40**
$\langle a\rangle$ is a subgroup of $G$. Call its order $k$. By Lagrange's theorem, $k$ divides $n$, therefore $a^n$ is a power of $a^k$, which is $e$. All powers of $e$ are $e$, therefore $a^n=e$.

**Exercise 41**
Consider any real $x$. The coset $x+\mathbb{Z}$ is by definition $\{x+n\ |\ n\in\mathbb{Z}\}$. Since $\lfloor x\rfloor$ is in $\mathbb{Z}$, $x-\lfloor x\rfloor$ must be in $x+\mathbb{Z}$. $0\leq x-\lfloor x\rfloor < 1$ by definition, showing that there is at least one such element. To show that there is at most one such element, consider $a,b\in x+\mathbb{Z}$ s.t. $0\leq a \leq b < 1$. By the definition of $x+\mathbb{Z}$, $a=x+n_0$ and $b=x+n_1$. $0\leq b-a<1$ then $0\leq x+n_1-(x+n_0)<1$ so $0\leq n_1-n_0 < 1$ and since both $n_1$ and $n_0$ are integers $n_1-n_0$ must also be integer so the only possibility is that $n_1-n_0=0$ showing that $n_1=n_0$ and by extension that $a=b$, completing the proof.

**Exercise 42**
Let $a+\langle 2\pi\rangle$ be our fixed coset. Its elements are $a+2\pi n$ for $n\in\mathbb{Z}$. $\sin(a+2\pi n)=\sin(a)$ for all $n$ by basic trigonometry, showing that for a fixed $a$ all elements of that coset are sent to the same number by $\sin$. 

**Exercise 43**
a.
Reflexivity:
$e\in H$ and $e\in K$
For any $a\in G$, $a=eae$
therefore $a\sim a$
Symmetry:
$a\sim b$
$a=hbk$ for some $h\in H$ and $k\in K$
$ak^{-1}=hb$
$h^{-1}ak^{-1}=b$
$b=h^{-1}ak^{-1}$
$b\sim a$ since $h^{-1}\in H$ and $k^{-1}\in K$
Transitivity:
$a\sim b$, $b\sim c$
$a=h_0bk_0$, $b=h_1ck_1$ for some $h_0,h_1 \in H$ and $k_0,k_1\in K$
$a=h_0h_1ck_1k_0$
$a\sim c$ since $h_0h_1 \in H$ and $k_1k_0\in K$.
b.
TODO

**Exercise 44**
a.
Closure:
For $\sigma$ and $\pi$ in $S_{c,c}$, $(\sigma\pi)(c)=\sigma(\pi(c))=\sigma(c)=c$ showing that $\sigma\pi$ is in $S_{c,c}$
Associativity is trivial
Identity:
$\iota(c)=c$ showing that $\iota$ is in $S_{c,c}$
Inverse:
$(\sigma\sigma^{-1})(c)=\iota(c)=c=\sigma(c)=\sigma(\sigma^{-1}(c))$
showing that $\sigma^{-1}(c)=c$ and that $\sigma^{-1}$ is in $S_{c,c}$
b.
Consider $A=\{1,2,3\}$ and $\sigma=(1,2,3)$ in $S_{1,2}$. $\sigma^{-1}=(1,3,2)$, which is clearly not in $S_{1,2}$, showing a counterexample for $S_{c,d}$ where $c\neq d$ being a subgroup.
c.
$S_{c,d}$ is the left coset of $S_{c,c}$ containing the transposition $(c,d)$

**Exercise 45**
Let $G=\langle g\rangle$. Name the order of $G$ as $n$.
It is sufficient to prove that for every $d|n$ there is exactly one subgroup of order $d$. It is trivial to show that these will be the only subgroups by Lagrange's theorem.
Let $d$ be any $d|n$ and $d>1$. Let $k=\frac{n}{d}$.
$\langle g^k\rangle$ is obviously a subgroup of order $d$. Consider a different subgroup of order $d$. Since this is a subgroup of a cyclic group, it is also cyclic and msut have a generator. Let's call it $h$. Since $G$ is cyclic, $h=g^a$ for some nonnegative integer $a$. It is sufficient to show that $\langle g^k\rangle = \langle g^a\rangle$ to show that the subgroup of order $d$ is unique. By Theorem 6.14, this is equivalent to $\gcd(k,n)=\gcd(a,n)$. $k$ is a divisor of $n$, so it is sufficient to show that $\gcd(a,n)=k$. 
Also by Theorem 6.14, $\langle g^a\rangle$ is of order $n/\gcd(a,n)$. We initially took that this order is $d$. $n/\gcd(a,n)=n/k$, so $\gcd(a,n)=k$, completing the proof.

**Exercise 46**
TODO

**Exercise 47**
TODO

