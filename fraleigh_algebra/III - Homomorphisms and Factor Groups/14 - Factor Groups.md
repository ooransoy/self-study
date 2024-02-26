**Exercises 1-8**
3
4
4
3
2
36
2
1

**Exercises 9-15**
4
6
3
2
4
8
3

**Exercise 16**
$i_{\rho_1}(\rho_0)=\rho_1\rho_0\rho_2=\rho_0$
$i_{\rho_1}(\mu_1)=\rho_1\mu_1\rho_2=\mu_3\rho_2=\mu_2$

**Exercise 17**
The condition should be "$gH=Hg$ for all $g\in G$".

**Exercise 18**
Correct.

**Exercise 19**
Isomorphism, not homomorphism.

**Exercise 20**
It leads to a factor group $G/H$, which would not be possible without normality.

**Exercise 21**
a. Because the elements of $G/H$ are cosets, and the student hasn't treated them as such.
b. "Let $aH$ and $bH$ be any two elements of $G/H$"
c.
$(aH)(bH)=(ab)H=(ba)H=(bH)(aH)$ showing that $aH$ and $bH$ commute, completing the proof.

**Exercise 22**
a. Again, the elements of $G/H$ are cosets.
b. "Let $xH\in G/H$"
c.
Because $G$ is a torsion group and $x\in G$, $x$ is of finite order and there exists $n\in\mathbb{Z}^+$ s.t. $x^n=e$. $(xH)^n=(x^n)H=eH=H$ showing that $xH$ is of finite order as well, completing the proof.

**Exercise 23**
a. T
b. T
c. T
d. T
e. T
f. F ($\mathbb{Z}/\mathbb{Z}_2$)
g. T
h. F ($S_n/A_n$)
i. T
j. F

**Exercise 24**
In $S_n$, $A_n$ has only two cosets (even and odd permutations), therefore it is normal (see Exercise (TODO: find)). $S_n/A_n$ is isomorphic to $\mathbb{Z}_2$.

**Exercise 25**
Let $x\in Ha$. $x=ha$ for some $h\in H$. $h^{-1}xh=ah$, so $h^{-1}xh\in aH$.
$(a^{-1}H)(h^{-1}xhH)=(a^{-1}H)(xH)=(a^{-1}x)H$
$a$ is also a representative from $aH$.
$(a^{-1}H)(aH)=eH=H$
By the assumption that left coset multiplication by representatives is well-defined, $a^{-1}x=h_1\in H$. $x=ah_1$, showing that $x\in aH$, completing the proof.

**Exercise 26**
Every subgroup of an abelian group is normal, therefore $T$ is normal. Let $xT\in G/T$ s.t. there is some $n\in\mathbb{Z}^+$ s.t. $(xT)^n=T$. It will suffice to show that $xT=T$, i.e. $x\in T$ (since $T=eT$ is the identity of $G/T$). $(xT)^n=x^nT=T$, meaning that $x^n\in T$. By the definition of $T$, there exists some $m\in\mathbb{Z}^+$ s.t. $(x^n)^m=e$. $x^{nm}=e$, and since $nm$ is finite then $x\in T$, completing the proof.

**Exercise 27**
Reflexivity:
$H=eHe^{-1}=i_e[H]$, meaning $H\sim H$
Symmetry:
$K\sim H$
$H=i_g[K]=gKg^{-1}$ for some $g\in G$
$g^{-1}Hg=K=i_{g^{-1}}[H]$
$H\sim K$
Transitivity:
$H\sim K$, $K\sim L$
$K=i_{g_1}[H]$, $L=i_{g_2}[K]$
$L=i_{g_2}[i_{g_1}[H]]=g_2g_1Hg_1^{-1}g_2^{-1}=g_2g_1H(g_2g_1)^{-1}$
$L=i_{g_2g_1}[H]$
$H\sim L$
and thus completing the proof.

**Exercise 28**
The normal subgroups are precisely the subgroups that are in cells of size 1. If there were two different elements in the cell, that would mean that a different subgroup was reached by conjugation, which contradicts the fact that normal subgroups are invariant under conjugation.

**Exercise 29**
$\{\rho_0, \mu_1\}$
$\{\rho_0, \mu_2\}$
$\{\rho_0, \mu_3\}$

**Exercise 30**
$m=(G:H)=|G/H|$. Let $a\in G$. Since the order of $aH$ will divide $m$ by Lagrange's theorem ($G/H$ is a group and $\langle aH\rangle$ is a subgroup of it, $m$ is the size of the group and $|\langle aH\rangle|$ i.e. the order of $aH$ will divide $m$), $(aH)^m=eH=H$. $(aH)^m=a^mH=H$ and so $a^m$ must be $\in H$, completing the proof.

**Exercise 31**
Let $H$ and $K$ be normal subgroups of $G$. We will show that $gxg^{-1}\in H\cap K$ for all $g\in G$ and $x\in H\cap K$.
Since $x\in H$, because $H$ is normal $gxg^{-1}\in H$ as well. Doing the same for $K$, it appears that $gxg^{-1}$ is in both groups, completing the proof.

**Exercise 32**
It is sufficient to show that there cannot be two different smallest normal subgroups of the same size that contain $S$. For the sake of contradiction assume that there are two different normal subgroups $H$ and $K$ of $G$ of the same size that both contain $S$. Obviously $H\cap K$ will also contain $S$. By Exercise 31, $H\cap K$ is also a normal subgroup. It is smaller than both $H$ and $K$, contradicting our initial assumption that they were the smallest such subgroups, completing the proof.

**Exercise 33**
Let $aC$ and $bC$ be from $G/C$. We will show that $(aC)(bC)=(bC)(aC)$. This is equivalent to $(ab)C=(ba)C$, which is in turn equivalent to $(a^{-1}b^{-1}ab)C=eC=C$. It is sufficient to show that $a^{-1}b^{-1}ab\in C$. Renaming $x=a^{-1}$ and $y=b^{-1}$, $a^{-1}b^{-1}ab=xyx^{-1}y^{-1}$, which is a commutator and therefore is in $C$, completing the proof.

**Exercise 34**
Since conjugating a subgroup gives a subgroup of the same size, the only possibility for a conjugation of $H$ is $H$ itself, since there are no other subgroups of that size. Since $H$ is invariant under conjugation, it is normal.

**Exercise 35**
Let $K=H\cap N$. We will show that for all $h\in H$ and $k\in K$, $hkh^{-1}\in K$.
Since $N$ is invariant under conjugation, $hkh^{-1}$ must be in $N$. Since $H$ is a subgroup and $hkh^{-1}$ is simply a product of elements from $H$, it is also in $H$. Since it is in both $H$ and $N$, it is in $K$, completing the proof.
TODO

**Exercise 36**
TODO

**Exercise 37**
a.
Let $\phi$ and $\psi$ be an automorphisms of $G$.
Closed:
Since the composition of two homomorphisms is again a homomorphism (proven in some exercise) and since the composition of two bijections is again a bijection, it follows that $\phi\psi$ is an automorphism.
Identity:
$\iota(x)=x$ is obviously an automorphism.
Associativity:
Already a property of functions
Inverse:
$\phi\phi^{-1}=\phi^{-1}\phi=\iota$ obviously.
b.
Let $i_a$ and $i_b$ be inner automorphisms of $G$. (some $a,b\in G$)
Closed:
$(i_ai_b)(x)=abxb^{-1}a^{-1}=abx(ab)^{-1}=i_{ab}(x)$
Associativity:
Already a property of functions
Identity:
$i_e(x)=exe^{-1}=x=\iota(x)$
Inverse:
$(i_ai_{a^{-1}})(x)=aa^{-1}xaa^{-1}=exe=x=\iota(x)$
Normal:
For any automorphism $\phi$ of $G$ and some $a\in G$
$\phi i_a\phi^{-1}(x)=\phi(a\phi^{-1}(x)a^{-1})=\phi(a)\phi(\phi^{-1}(x))\phi(a^{-1})$
$=\phi(a)x\phi(a)^{-1}=i_{\phi(a)}$
showing that conjugation of an inner automorphism by any automorphism is still an inner automorphism, completing the proof.

**Exercise 38**
$S=\{g\in G\ |\ i_g=i_e\}$
$i_g=i_e$ means that $gxg^{-1}=x$ for all $x\in G$.
Closed:
Let $x\in G$, $a,b\in S$
$abx(ab)^{-1}=abxb^{-1}a^{-1}=axa^{-1}=x$
showing that $ab$ also satisfies the property.
Inverse:
Let $x\in G$ and $a\in S$
$axa^{-1}=x$
$ax=xa$
$x=a^{-1}xa$
showing that $a^{-1}$ also satisfies the property.
Normal:
Let $a\in S$ and $g,x\in G$
$gag^{-1}x(gag^{-1})^{-1}=gag^{-1}xga^{-1}g^{-1}$
$=g(a(g^{-1}xg)a^{-1})g^{-1}$
Using that $a\in S$,
$=g(g^{-1}xg)g^{-1}$
$=x$
showing that $gag^{-1}\in S$, showing that $S$ is invariant under conjugation and completing the proof.

**Exercise 39**
Consider $\psi : G/H \to G'/H'$ given by $\psi(gH)=\phi(g)H'$. We will show that this is well-defined (same result when any representative of $gH$ is picked) and is a homomorphism.
Well-defined:
Let $a,b\in gH$. Let $h=a^{-1}b$ (we know from a previous result that this is in $H$) and let $h'=\phi(h)$ (by our hypothesis this is in $H'$).
$\psi(aH)=\phi(a)H'=\phi(a)h'H'=\phi(a)\phi(h)H'$
$=\phi(ah)H'=\phi(aa^{-1}b)H'=\phi(b)H'=\psi(bH)$
showing that $\psi(aH)=\psi(bH)$, showing that $\psi$ is well-defined.
Homomorphism:
$\psi((aH)(bH))=\psi(abH)=\phi(ab)H'=\phi(a)\phi(b)H'$
$=(\phi(a)H')(\phi(b)H')=\psi(aH)\psi(bH)$
showing that $\psi$ has the homomorphism property.

**Exercise 40**
a.
It is obvious that a subgroup is formed.
Normal:
Let $A,B\in GL(n,\mathbb{R})$ s.t. $\det(B)=1$.
$\det(ABA^{-1})=\det(A)\det(B)\det(A^{-1})$
$=\det(A)\det(A^{-1})$
$=1$
showing that $\det(ABA^{-1})=1$, completing the proof.
b.
It is obvious that a subgroup is formed.
Normal:
Let $A,B\in GL(n,\mathbb{R})$ s.t. $\det(B)=\pm1$.
$\det(ABA^{-1})=\det(A)\det(B)\det(A^{-1})$
$=\pm\det(A)\det(A^{-1})$
$=\pm1$
completing the proof.

**Exercise 41**
a.
Let $A,B,C\in P(G)$.
$A(BC)=A\{bc\ |\ b\in B, c\in C\}$
$=\{a(bc)\ |\ a\in A,b\in B,c\in C\}$
$=\{(ab)c\ |\ a\in A,b\in B,c\in C\}$
$=\{ab\ |\ a\in A,b\in B\}C$
$=(AB)C$
showing that the operation is associative.

$\{e\}A=\{ea\ |\ a\in A\}=\{a\ |\ a\in A\}=A$
$A\{e\}=\{ae\ |\ a\in A\}=\{a\ |\ a\in A\}=A$
showing that $\{e\}$ is the identity.

$\{\}$ has no inverse, so a group is not formed.
b.
$(aN)(bN)=\{an_1bn_2\ |\ n_1,n_2\in N\}$
$=\{abn_1b^{-1}bn_2\ |\ n_1,n_2\in N\}$
$=\{abn_1n_2\ |\ n_1,n_2\in N\}$
$=(ab)\{n_1n_2\ |\ n_1,n_2\in N\}$
$=(ab)N$ (proof omitted)
which is the result we get with coset multiplication by representatives, completing the proof.
c.
We know the operation is closed from (b) and is associative from (a).
Identity:
$N(aN)=\{n_1an_2\ |\ n_1,n_2\in N\}$
$=\{an_1a^{-1}an_2\ |\ n_1,n_2\in N\}$
$=\{an_1n_2\ |\ n_1,n_2\in N\}$
$=aN$
$(aN)N=\{an_1n_2\ |\ n_1,n_2\in N\}$
$=aN$
showing that $N$ is the identity.
Inverse:
$(aN)(a^{-1}N)=\{an_1a^{-1}n_2\ |\ n_1,n_2\in N\}$
$=\{aa^{-1}n_1n_2\ |\ n_1,n_2\in N\}$
$=\{n_1n_2\ |\ n_1,n_2\in N\}$
$=N$
$(a^{-1}N)(aN)=\{a^{-1}n_1an_2\ |\ n_1,n_2\in N\}$
$=\{a^{-1}an_1n_2\ |\ n_1,n_2\in N\}$
$=\{n_1n_2\ |\ n_1,n_2\in N\}$
$=N$
Showing that $a^{-1}N$ is an inverse of $aN$.
