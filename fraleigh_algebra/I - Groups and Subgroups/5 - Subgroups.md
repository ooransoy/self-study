**Exercise 1-6**
YNYYYN

**Exercise 7**
YYNNNY

**Exercise 8-13**
NNNNYY

**Exercise 14-19**
(a) NYNNNY
(b) YNYYNN

**Exercise 20**
$G_2 \leq G_8 \leq G_7 \leq G_1 \leq G_4$
$G_9 \leq G_3 \leq G_5$
$G_6 \leq G_5$

**Exercise 21**
a.
	$-50, -25, 0, 25, 50$
b.
	$0.25, 0.5, 1, 2, 4$
c.
	$\frac{1}{\pi^2}, \frac{1}{\pi}, 1, \pi, \pi^2$

**Exercise 22-25**
$\begin{bmatrix}0 & -1 \\ -1 & 0\end{bmatrix},\begin{bmatrix}1 & 0 \\ 0 & 1\end{bmatrix}$

$\{\begin{bmatrix}1 & \pm 2^x \\ 0 & 1\end{bmatrix} | x \in \mathbb{N}\}$

$\{\begin{bmatrix}3^x & 0 \\ 0 & 2^x\end{bmatrix} | x \in \mathbb{Z}\}$

$\{\begin{bmatrix}2^x & 0 \\ 0 & 2^x\end{bmatrix}|x\in 2\mathbb{Z}\} \cup \{\begin{bmatrix}0 & -2^{x+1} \\ -2^{x+1} & 0\end{bmatrix}|x\in 2\mathbb{Z}\}$

**Exercise 26**
$\{1, -1\}$
$\varnothing$
$\varnothing$
$\{6, -6\}$
$\{6, \frac{1}{6}\}$
$\varnothing$

**Exercise 27-35**
4
2
3
5
4
8
2
4
3

**Exercise 36**
a.
```
+|012345
-+------
0|012345
1|123450
2|234501
3|345012
4|450123
5|501234
```
b.
	$\{0\}$
	$\{0, 1, 2, 3, 4, 5\}$
	$\{0, 2, 4\}$
	$\{0, 3\}$
	$\{0, 2, 4\}$
	$\{0, 1, 2, 3, 4, 5\}$
c.
	$1, 5$
d.
```
   1,5
  /   \
2,4   3
  \   /
    0
```

**Exercise 37**
It should be stated that $H$ should be closed under $G$'s operation.

**Exercise 38**
No correction is needed.

**Exercise 39**
TFTFFFFFTF

**Exercise 40**
In $V$, all four elements satisfy the equation.

**Exercise 41**
We will show that $\phi[H]$ is closed under $*'$. Let $x', y'\in \phi[H]$. We will show that $x'*'y'\in \phi[H]$.
Let $x, y\in H$ s.t $\phi(x)=x'$ and $\phi(y) = y'$ (this is possible by the definition of $\phi[H]$).
Because $H$ is a subgroup:
$x*y\in H$
Applying $\phi$ to the left side and using the definition of $\phi[H]$:
$\phi(x*y)\in \phi[H]$
Applying the homomorphism property of $\phi$:
$\phi(x)*'\phi(y)\in \phi[H]$
$x'*'y'\in \phi[H]$
Showing that $\phi[H]$ is closed under $*'$.

We will show that $\phi[H]$ contains the identity element of $G'$. Let $e$ be the identity of $G$. The identity of $G'$ is obviously $\phi(e)$. Since $H$ is a subgroup, $e\in H$. Then, by the definition of $\phi[H]$, $\phi(e) \in \phi[H]$, showing that $\phi[H]$ contains the identity element of $G'$.

We will show that for all $x'\in \phi[H]$, $x'^{-1}\in \phi[H]$. Let $x\in H$ s.t $\phi(x) = x'$. Since $H$ is a subgroup, $x^{-1}\in H$. Applying $\phi$, $\phi(x^{-1})\in \phi[H]$.
$x*x^{-1}=e$
$\phi(x*x^{-1})=e'$
$\phi(x)*'\phi(x^{-1})=e'$
$x'*\phi(x^{-1})=e'$
Therefore $\phi(x^{-1}) = x'^{-1}$, showing that $x'^{-1}\in \phi[H]$.

**Exercise 42**
Since $G$ is cyclic, there must exist some $g\in G$ s.t. $\{g^n|n\in \mathbb{Z}\} = G$. Applying $\phi$, $\{\phi(g^n)|n\in \mathbb{Z}\}=G'$. Applying the homomorphism property, $\{\phi(g)^n|n\in \mathbb{Z}\}=G'$, showing that $\phi(g)$ generates $G'$ and that $G'$ is cyclic.

**Exercise 43**
Let's call this set $HK$. We will show that $HK$ is closed. Let $x, y\in HK$. We will show that $xy\in HK$. Let $h_x,h_y\in H$ and $k_x,k_y\in K$ s.t. $h_xk_x=x$ and $h_yk_y=y$.
$xy=h_xk_xh_yk_y$
Since $G$ is abelian,
$xy=h_xh_yk_xk_y$
Since $h_xh_y \in H$ and $k_xk_y\in K$ since $H$ and $K$ are closed, $xy\in HK$ by the definition of $HK$, showing that $HK$ is closed.

Let $e$ be the identity of $G$. We will show that $e\in HK$.
Since $e\in H$ and $e\in K$ since $H$ and $K$ are subgroups, then $ee$ is in $HK$ by definition. $ee=e$, therefore $e\in HK$.

Let $hk \in HK$. We will show that $(hk)^{-1}\in HK$. $(hk)^{-1}=k^{-1}h^{-1}$. Since $G$ is abelian, $(hk)^{-1}=h^{-1}k^{-1}$. Since $h^{-1}\in H$ and $k^{-1}\in K$ because $H$ and $K$ are subgroups,  $(hk)^{-1}\in HK$ by definition.

**Exercise 44**
Condition 3 depends on the identity element that Condition 2 introduces, therefore deriving Condition 2 from Condition 3 is circular reasoning.

**Exercise 45**
We will prove that $H$ contains $e$. Let $a\in H$. By our condition $aa^{-1}\in H$. $aa^{-1}=e$, therefore $e\in H$.
We will prove that for all $a\in H$, $a^{-1}\in H$. $e,a\in H$, therefore $ea^{-1}\in H$ by our condition. $ea^{-1}=a^{-1}$, therefore $a^{-1}\in H$.
We will prove that $H$ is closed. Let $a, b \in H$. We know that $b^{-1}\in H$, so $a(b^{-1})^{-1}\in H$ by our condition. $(b^{-1})^{-1}=b$, therefore $ab \in H$.

**Exercise 46**
Let $G$ be our cyclic group. Let $g$ be the generator for G. We will show that $g^{-1}$ is also a generator.
$\{g^n|n\in \mathbb{Z}\}=G$
$\{g^{-n}|n\in \mathbb{Z}\}=G$
$\{(g^{-1})^n|n\in \mathbb{Z}\}=G$
Therefore, $g^{-1}$ also generates $G$. Since there is only one generator, it has to be the case that $g=g^{-1}$. This implies $g^2=e$, from which we can also derive $g^{n}=g^{n+2}$.
Since we can add 2 to or subtract 2 from the exponent without changing the value, we can deduce that all $g^{2n}$ are equal, and that $g^{2n+1}$ are all equal as well. Since every integer can be represented as either $2n$ or $2n+1$, all powers of $g$ are either $g^{2n}$ (namely $e$) or $g^{2n+1}$ (namely $g$). Since $g$ is a generator for $G$, all elements of $G$ are powers of $g$. There are only 2 possible values for a power of $g$, therefore $G$ has only 2 elements.

**Exercise 47**
Since $ee=e$, $e$ satisfies the condition to be in $H$.
We will prove that $H$ is closed. Consider $a,b\in H$. By the definition of $H$, $aa=e$ and $bb=e$. Therefore $aabb=e$. Since $G$ is abelian, $abab=e$. Since $e\in H$, $ab$ satisfies the condition to be in $H$.
Since $xx=e$, $x=x^{-1}$. Therefore, if $x\in H$ then $x^{-1} \in H$.

**Exercise 48**
Since $e^n=e$, $e$ satisfies the condition to be in $H$.
We will prove that $H$ is closed. Consider $a,b\in H$. By the definition of $H$, $a^n=e$ and $b^n=e$. Therefore $a^nb^n=e$. Since $G$ is abelian, $(ab)^n=e$. Since $e\in H$, $ab$ satisfies the condition to be in $H$.
We will prove that if $x\in H$ then $x^{-1}\in H$.
$x^n=e$
$(x^n)^{-1}=e^{-1}$
$x^{-n}=e$
$(x^{-1})^n=e$
Showing that $x^{-1}$ satisfies the condition to be in $H$

**Exercise 49**
Let $m$ be the order of $G$. Consider the list $x^1, x^2, x^3, ... , x^m, x^{m+1}$. By the pigeonhole principle, there must be a pair of equal elements in this list. Let them be $x^i$ and $x^j$ (WLOG $i>j$).
$x^i=x^j$
$x^ix^{-j}=x^jx^{-j}$
$x^{i-j}=e$
Since $i>j$, $i-j \in \mathbb{Z}^+$. $i-j$ is a suitable $n$.

**Exercise 50**
Since $H$ is nonempty, let $x\in H$. By the result in Exercise 49, there exists $n\in \mathbb{Z}^+$ s.t. $x^n=e$. Since $H$ is closed, $x^n$ must be in $H$, showing that $H$ contains the identity element. $x^{n-1}x=e$, therefore $x^{n-1}$ is the inverse of $x$. Since $H$ is closed, $x^{n-1}$ is contained in $H$ showing  that $x^{-1}\in H$.

**Exercise 51**
We will show that $H_a$ is closed. Consider $x, y \in H_a$.
$axy=axy$
Since $ax=xa$,
$xay=axy$
Since $ay=ya$,
$xya=axy$
Showing that $xy$ satisfies the condition to be in $H_a$.
By the result in Exercise 50, this is sufficient to show that $H_a$ is a subgroup.

**Exercise 52**
a.
	If $S$ is empty, then the condition is vacuously true for all $x\in G$. $H_S=G$, therefore $H_S$ is a subgroup.
	If $S$ is nonempty, the proof in Exercise 51 works for all $a\in S$.
b.
	Consider $x,y\in H_G$. Since $y\in G$, $xy=yx$ by the definition of $H_G$.

**Exercise 53**
Reflexivity:
$aa^{-1}=e$, and since $H$ is a subgroup $e$ is contained in $H$, showing that $a~a$
Symmetry:
$a\sim b$
$ab^{-1}\in H$
Since $H$ is a subgroup,
$(ab^{-1})^{-1}\in H$
$(b^{-1})^{-1}a^{-1}\in H$
$ba^{-1}\in H$
$b\sim a$
Transitivity:
$a\sim b$ and $b \sim c$
$ab^{-1}\in H$ and $bc^{-1}\in H$
Since $H$ is closed,
$ab^{-1}bc^{-1}\in H$
$ac^{-1}\in H$
$a\sim c$

**Exercise 54**
Consider $x,y \in H \cap K$.
$x,y\in H$
Since $H$ is closed, $xy\in H$
$x,y\in K$
Since $H$ is closed, $xy\in K$
Therefore, $xy$ is in both $H$ and $K$ and satisfies the condition to be in $H\cap K$, showing that $H\cap K$ is closed and is a subgroup.

**Exercise 55**
Let $G$ be our group, and let $g$ be a generator for $G$.
Consider $x, y\in G$. Since $g$ generates $G$, there must exist $n,m\in \mathbb{Z}$ s.t. $g^n=x$ and $g^m=y$.
$g^{n+m}=g^{n+m}$
$g^{n+m}=g^{m+n}$
$g^{n}g^{m}=g^{m}g^{n}$
$xy=yx$
showing that $G$ is abelian.

**Exercise 56**
That $G$ is abelian.

**Exercise 57**
The statement is obviously true for a trivial group.
For a nontrivial group, consider a non-identity element $x\in G$. $\langle x\rangle$ is obviously nontrivial. By our condition, it cannot be a proper subgroup. Therefore it is an improper subgroup, and $\langle x\rangle = G$. Therefore, $x$ generates $G$, showing that $G$ is cyclic.
