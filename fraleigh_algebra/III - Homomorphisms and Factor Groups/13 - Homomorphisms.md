**Exercise 1**

Yes.

$\phi(a+b)=a+b=\phi(a)+\phi(b)$



**Exercise 2**

No.

$\phi(0.5+0.5)=\phi(1)=1\neq0=0+0=\phi(0.5)+\phi(0.5)$

**Exercise 3**

Yes.

$\phi(ab)=|ab|=|a||b|=\phi(a)\phi(b)$



**Exercise 4**

Yes.

Subtracting 6 from an integer preserves parity, therefore $a+b \mod 6$ will have the same parity as $(a \mod 6) + (b \mod 6)$.



**Exercise 5**

No.

$\phi(1+8)=\phi(0)=0\neq1=1+0=\phi(1)+\phi(8)$



**Exercise 6**

Yes.

$\phi(a+b)=2^{a+b}=2^a2^b=\phi(a)\phi(b)$



**Exercise 7**

Yes.



**Exercise 8**

No. (Yes if the group is abelian, or if the destination group has the operation swapped.)



**Exercise 9**

Yes.



**Exercise 10**

Yes.



Yes.



No.



Yes.



No.



No.



**Exercises 16-24**

$A_3$

All $7n$, 2

All $5n$, 8

All $6n$, $\begin{pmatrix}1&2&3&4&5&6&7&8\\4&5&3&2&7&1&6&8\end{pmatrix}^{20}=(1,2,7)(4,5,6)$

$\{0, 5\}$, 4

$\{0, 4, 8, 12, 16, 20\}$, $(1,6)(4,7)$

All $(5n,3n)$, -19

$\{(0,0)\}$, $(2,18)$

All $(2n,4m)$, $(3,5)(2,4)(6,8)(10,9)$



**Exercise 25**

2



**Exercise 26**

As many as there are integers.



**Exercise 27**

2.



**Exercise 28**

Only $e$.

$\phi_g(xy)=gxy=gxgy=\phi_g(x)\phi_g(y)$

$gxy=gxgy\implies gx=gxg\implies x=xg\implies e=g$



**Exercise 29**

All.



**Exercise 30**

From a group $G$ to another group $G'$. Condition holds for all $x,y\in G$.



**Exercise 31**

Correct.



**Exercise 32**

a. T

b. T

c. F

d. T

e. F

f. F

g. T

h. T

i. F

j. F



**Exercises 33-43**

DNE, the only integer dividing both 12 and 5 is 1 meaning that the image of the homomorphism will be $\{e'\}$ meaning that it has to be the trivial homomorphism.

$\phi(x)=x\mod 4$

$\phi(x, y)=(x,0)$

For all elements $x$ in $\mathbb{Z}_3$, $x^3=e$. $\phi(x^3)=e=\phi(x)^3$ and the only element in $\mathbb{Z}$ s.t. its cube is $0$ is $0$ so $\phi(x)$ must be $0$ for all $x$ meaning that it is the trivial homomorphism.

$\phi(n)=(1,2,3)^n$

$\phi(n)=(1,2,3)^n$

$\phi(x, y)=2x$

$\phi(x)=(\frac{x}{2},0)$

$\phi(x)=0$ if $x$ preserves orientation, $\phi(x)=1$ otherwise.

$\phi(\sigma)=\pi$ s.t. $\pi(x)=4$ if $x=4$ and $\pi(x)=\sigma(x)$ otherwise.

$\phi(\sigma)=\iota$ if $\sigma$ is even, $\phi(\sigma)=(1,2)$ if $\sigma$ is odd.



**Exercise 44**

$|\phi[G]|$ is obviously the number of cosets of the kernel of $\phi$. By Lagrange's theorem, the size of the kernel divides $|G|$, and by extension so does the number of cosets, completing the proof.



**Exercise 45**

Since the image of a group is again a subgroup, $\phi[G]$ must be a subgroup of $G'$. Lagrange's theorem completes the proof.



**Exercise 46**

We will show that $\phi(x)=\mu(x)$ for all $x\in G$.

$\phi(x)=\phi(\prod_{j\in J}a_{i_j}^{r_j})$

$=\prod_{j\in J}\phi(a_{i_j}^{r_j})$

$=\prod_{j\in J}\phi(a_{i_j})^{r_j}$

$=\prod_{j\in J}\mu(a_{i_j})^{r_j}$

$=\prod_{j\in J}\mu(a_{i_j}^{r_j})$

$=\mu(\prod_{j\in J}a_{i_j}^{r_j})$

$=\mu(x)$

thus completing the proof.



**Exercise 47**

Let $|G|=p$. By Lagrange's theorem, the order of the kernel must divide $p$. There are two cases. Either the order of the kernel is 1, which means the homomorphism is injective, or the order of the kernel is $p$, meaning that all elements are mapped to $e$ meaning the homomorphism is trivial.



**Exercise 48**

$A_n$. The said group is isomorphic to $\mathbb{Z}_2$.



**Exercise 49**

$(\gamma\phi)(ab)=\gamma(\phi(ab))=\gamma(\phi(a)\phi(b))$

$=\gamma(\phi(a))\gamma(\phi(b))=(\gamma\phi)(a)(\gamma\phi)(b)$

showing that $\gamma\phi$ is a homomorphism.



**Exercise 50**

For any $x,y\in G$,

$\phi(xyx^{-1}y^{-1})=e=\phi(xy)\phi(x^{-1}y^{-1})$

$\phi(xy)=\phi(x^{-1}y^{-1})^{-1}=\phi((x^{-1}y^{-1})^{-1})$

$=\phi((x^{-1}y^{-1})^{-1})=\phi(yx)$

$\phi(xy)=\phi(yx)$

$\phi(x)\phi(y)=\phi(y)\phi(x)$



Since for any $a,b\in \phi[G]$ there exist $x,y\in G$ s.t. $\phi(x)=a$ and $\phi(y)=b$, $ab=\phi(x)\phi(y)=\phi(y)\phi(x)=ba$, showing that $\phi[G]$ is abelian.



**Exercise 51**

$\phi(n+m)=a^{n+m}=a^na^m=\phi(n)\phi(m)$

showing that $\phi$ is a homomorphism.

The range of $\phi$ is $\langle a\rangle$. The kernel will consist of $a^{kn}$ where $n$ is any integer and $k$ is the order of $a$.



**Exercise 52**

Let $a$ be any element of $G$.

We will first show that $\{x\in G\ |\ \phi(x)=\phi(a)\} \subseteq Ha$, then that $Ha \subseteq \{x\in G\ |\ \phi(x)=\phi(a)\}$.

It is sufficient to show for all $x\in G$ satisfying $\phi(x)=\phi(a)$ that $x=ha$ for some $h\in H$.

$\phi(x)\phi(a)^{-1}=e'$

$\phi(x)\phi(a^{-1})=e'$

$\phi(xa^{-1})=e'$

showing that $xa^{-1}\in H$. $x=(xa^{-1})a$ holds, so $xa^{-1}$ is a suitable $H$, showing the first component of the proof.

It is sufficient to show that $\phi(ha)=\phi(a)$ for any $h\in H$. $\phi(ha)=\phi(h)\phi(a)=e'\phi(a)=\phi(a)$, showing the second component and completing the proof.



**Exercise 53**

$\phi((a,b)+(c,d))=\phi(a+c,b+d)=h^{a+c}k^{b+d}$

$=h^ah^ck^bk^d$

$\phi(a,b)\phi(c,d)=h^ak^bh^ck^d$

$\phi$ being a homomorphism is equivalent to $h^ah^ck^bk^d=h^ak^bh^ck^d$ for all $a,b,c,d\in \mathbb{Z}$, which is in turn equivalent to $h^ck^b=k^bh^c$ for all $b,c\in\mathbb{Z}$, which is obviously equivalent to $hk=kh$, giving us our necessary and sufficient condition.



**Exercise 54**

That $G$ is abelian.



**Exercise 55**

$\phi(i+j)=h^{i+j\mod n}$

$\phi(i)\phi(j)=h^ih^j=h^{i+j}$

The homomorphism condition is equivalent to $h^{i+j\mod n}=h^{i+j}$, which obviously equivalent to $h^n=e$. This in turn is equivalent to $n$ being a multiple of the order of $h$, giving us our necessary and sufficient proof.

