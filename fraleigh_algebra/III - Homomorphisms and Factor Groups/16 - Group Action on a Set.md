**Exercise 1**
$X_{\rho_0}=X$
$X_{\rho_1}=\{C\}$
$X_{\rho_2}=\{C,m_1,m_2,d_1,d_2\}$
$X_{\rho_3}=\{C\}$
$X_{\mu_1}=\{C,s_1,s_3,m_1,m_2,P_1,P_3\}$
$X_{\mu_2}=\{C,s_2,s_4,m_1,m_2,P_2,P_4\}$
$X_{\delta_1}=\{C, d_1,d_2,2,4\}$
$X_{\delta_2}=\{C, d_1,d_2,1,3\}$

**Exercise 2**
$G_C=G$
$G_{m_1}=G_{m_2}=\{\rho_0,\rho_2,\mu_1,\mu_2\}$
$G_{d_1}=G_{d_2}=\{\rho_0,\rho_2,\delta_1,\delta_2\}$
$G_{s_1}=G_{s_3}=G_{P_1}=G_{P_3}=\{\rho_0,\mu_1\}$
$G_{s_2}=G_{s_4}=G_{P_2}=G_{P_4}=\{\rho_0,\mu_2\}$
$G_{1}=G_{3}=\{\rho_0,\delta_2\}$
$G_{2}=G_{4}=\{\rho_0,\delta_1\}$

**Exercise 3**
$\{C\}$
$\{m_1,m_2\}$
$\{d_1,d_2\}$
$\{s_1,s_2,s_3,s_4\}$
$\{P_1,P_2,P_3,P_4\}$
$\{1,2,3,4\}$

**Exercise 4**
For a $g\in G$, and for all $x\in X$.

**Exercise 5**
What the statement is trying to say is correct, but not rigorous. A better way to put it would be:
For every $x,y\in X$, there exists $g\in G$ s.t. $gx=y$.

**Exercise 6**
A sub-$G$-set $S$ of a $G$-set $X$ is a disjoint union of any selection of orbits on $X$ under $G$.

**Exercise 7**
A transitive $G$-set is one that has only one orbit. Naturally, the orbit is equal to the entire set.

**Exercise 8**
a. F
b. T
c. F (only if $G$ acts faithfully)
d. T
e. F
f. T
g. T
h. F
i. T
j. T

**Exercise 9**
a.
The $P_i$ and the $s_i$ are isomorphic.
b.
$\delta_2$ fixes $1$ and $3$, whereas none of $s_i$ are fixed by $\delta_2$. This shows that they are not isomorphic.
c.
No. $P_i\cup m_i$ and $s_i\cup m_i$ are also isomorphic. However, $P_i$ and $s_i$ are the only isomorphic pair of _transitive_ sub-$D_4$-sets of $X$.

**Exercise 10**
a.
Yes. $\rho_0$ is the only group element that fixes the entire set.
b.
$\{1,2,3,4\}$, the $s_i$, and the $P_i$.

**Exercise 11**
Let $a,b\in G$ s.t. $a\neq b$ and $ax=bx$ for all $x\in X$. $b^{-1}(ax)=b^{-1}(bx)=(b^{-1}a)x=x$. Since $a\neq b$, $b^{-1}a\neq e$, meaning that $b^{-1}a$ is a nonidentity element that leaves all $x\in X$ fixed, showing that $G$ does not act faithfully on $X$.
Conversely, let $G$ act faithfully on $X$. For $a,b\in G$ s.t. $ax=bx$, since $b^{-1}a$ fixes all elements, it must be that $b^{-1}a=e$ by the faithfullness property. $bb^{-1}a=be$, $a=b$, meaning that no two distinct elements of $G$ can have the same action for all $x\in X$.

**Exercise 12**
Identity:
Since $e$ fixes everything, it also fixes $Y$, showing that $e\in G_Y$.
Inverse:
For any $g\in G_Y$ and any $y\in Y$, $gy=y$, $g^{-1}gy=g^{-1}y=y$, showing that $g^{-1}$ also fixes $y$, leading to $g^{-1}\in G_Y$.
Closure:
For any $g_1,g_2\in G_Y$ and any $y\in Y$, $(g_1g_2)y=g_1(g_2y)=g_1y=y$, showing that $g_1g_2$ fixes $Y$ and that $g_1g_2\in G_Y$.
This completes the proof that $G_Y$ is a subgroup.

**Exercise 13**
a.
Rotating by $0$ radians is leaving the plane untouched, meaning that the identity of $G$ fixes all elements of $\mathbb{R}^2$.
b.
The circle centered on the origin of radius $d$, where $d$ is the distance between the origin and $P$.
In other words, all points with the same distance to the origin as $P$.
c.
$\langle 2\pi\rangle$.

**Exercise 14**
a.
We can define $*(g,x)$ to be $*_i(g,x)$ where $i$ is s.t. $x\in X_i$. This satisfies the conditions for a group action, rendering $\bigcup_{i\in I}X_i$ a $G$-set.
b.
Each orbit of $X$ is a sub-$G$-set so they are also $G$-sets. Taking their union gives us $X$, since every element in $X$ is in an orbit.

**Exercise 15**
Let $\phi : X\to L$ be given by $\phi(x)=gG_{x_0}$ for some $g\in G$ s.t. $x=gx_0$. We will first show that $\phi$ is well defined, meaning the result is the same for any choice of $g$.
Let $g_1,g_2\in G$ s.t. $x=g_1x_0$ and $x=g_2x_0$. $g_1x_0=g_2x_0$, $g_1^{-1}g_1x_0=g_1^{-1}g_2x_0=x_0$ showing that $g_1^{-1}g_2\in G_{x_0}$. $\phi(x)=g_1G_{x_0}=g_1(g^{-1}_1g_2)G_{x_0}=g_2G_{x_0}$, meaning that $\phi(x)$ is the same for any $g$ satisfying $x=gx_0$. This shows that $\phi$ is well-defined.
We will now show that $\phi$ is a homomorphism. For any $x,y\in X$, $\phi(xy)=(xy)G_{x_0}$ and since multiplication of cosets by representatives is well defined we have $(xy)G_{x_0}=(xG_{x_0})(yG_{x_0})=\phi(x)\phi(y)$, showing that $\phi$ is a homomorphism.
Lastly, we will show that $\phi$ is a bijection. For any coset $gG_{x_0}$ of $G_{x_0}$, we can simply pick a representative $g$ to see that $\phi(gx_0)=gG_{x_0}$, showing that $\phi$ is surjective. For $x,y\in X$ and $g_x,g_y\in G$ s.t. $g_xx_0=x\neq y=g_yx_0$, assume that $\phi(x)=\phi(y)=g_xG_{x_0}=g_yG_{x_0}$. $g_y^{-1}g_xG_{x_0}=G_{x_0}$, $g_y=g_x$, $g_yx_0=g_xx_0=y=x$, contradicting that $x\neq y$, showing that $\phi(x)\neq\phi(y)$ for $x\neq y$, meaning that $\phi$ is a bijection.
This completes the proof that $\phi$ is an isomorphism.

**Exercise 16**
Let $G$ be a group and $X$ a $G$-set. Consider all the orbits $X_i$ of $X$. By definition, orbits are transitive sub-$G$-sets. By Exercise 15, let $L_i$ be a group of left cosets of $G$ isomorphic to $X_i$. The union of all $X_i$ is naturally isomorphic to the disjoint union of all $L_i$, which is in turn isomorphic to $X$ by Exercise 14, completing the proof.

**Exercise 17**
a.
For any $k\in K$, $kg_0x_0=g_0x_0$, so $g_0^{-1}kg_0x_0=x_0$. This means that there exists some $h\in H$ s.t. $g_0^{-1}kg_0=h$. $kg_0=g_0h$, $k=g_0hg_0^{-1}$, showing that every $k\in K$ is of the form $g_0hg_0^{-1}$, showing that $K\subseteq g_0Hg_0^{-1}$. The other direction is obvious, leading to $K=g_0Hg_0^{-1}$.
b.
That $H$ and $K$ are conjugate subgroups.
c.
We will show that $L_H$ and $L_K$ are isomorphic iff $H$ and $K$ are conjugate.

For a group $G$ and subgroups $H$ and $K=g_0Hg_0^{-1}$ for $g_0\in G$, with $L_H$ and $L_K$ their left coset $G$-sets, consider $\phi:L_H\to L_K$ given by $\phi(gH)=gg_0^{-1}K$. We will start the proof that $\phi$ is an isomorphism by showing that $\phi$ is well defined for any choice of representative.
Let $gH\in L_H$ and $g_1,g_2\in gH$. There exist $h_1,h_2\in H$ s.t. $g_1=gh_1$ and $g_2=gh_2$.
$\phi(g_1H)=g_1g_0^{-1}K=g_1Hg_0^{-1}=gh_1Hg_0^{-1}=gHg_0^{-1}$
$\phi(g_2H)=g_2g_0^{-1}K=g_2Hg_0^{-1}=gh_2Hg_0^{-1}=gHg_0^{-1}$
This shows that $\phi$ is well defined.
For any $gK\in L_K$, $\phi(gg_0H)=gg_0g_0^{-1}K=gK$. This shows that $\phi$ is surjective. Since $H$ and $K$ are conjugate, $|H|=|K|$. This means that $|L_H|=|L_K|$, showing that $\phi$ is a bijection.
Let $g\in G$. $\phi(gH)=geg_0^{-1}K=g\phi(eH)=g\phi(H)$. This completes the proof that $\phi$ is an isomorphism.

Let $G$ be a group and let $H$ and $K$ be subgroups of $G$. Let $L_H$ and $L_K$ be their left coset $G$-sets and let $\phi:L_H\to L_K$ be an isomorphism. We will show that $H$ and $K$ are conjugate.
Since $\phi$ is surjective, let $g_0$ be the element of $G$ satisfying $\phi(g_0H)=K$. For any $k\in K$, $k\phi(g_0H)=kK=K=\phi(kg_0H)=\phi(g_0H)$, meaning that $kg_0\in g_0H$ so there exists $h\in H$ s.t. $kg_0=g_0h$. This shows that for all $k\in K$, there exists $h\in H$ s.t. $k=g_0hg_0^{-1}$, meaning that $K\subseteq g_0Hg_0^{-1}$. Since $\phi$ is a bijection, $|L_H|=|L_K|$, so $|K|=|H|=|g_0Hg_0^{-1}|$, leading to that $K=g_0Hg_0^{-1}$. This completes the proof.

**Exercise 18**
All transitive $\mathbb{Z}_4$-sets are by Exercise 15 isomorphic to the $\mathbb{Z}_4$-set of left cosets of some subgroup of $\mathbb{Z}_4$. It is sufficient for us to enumerate all subgroups of $\mathbb{Z}_4$.

$\langle0\rangle=\{0\}$:
```
 |abcd
-+----
0|abcd
1|bcda
2|cdab
3|dabc
```

$\langle2\rangle=\{0, 2\}$
```
 |ab
-+--
0|ab
1|ba
2|ab
3|ba
```

$\langle1\rangle=\{0, 1, 2, 3\}$
```
 |a
-+-
0|a
1|a
2|a
3|a
```

There are 3 transitive $\mathbb{Z}_4$-sets up to isomorphism.

**Exercise 19**
$\langle0\rangle=\{0\}$:
```
 |abcdef
-+------
0|abcdef
1|bcdefa
2|cdefab
3|defabc
4|efabcd
5|fabcde
```

$\langle3\rangle=\{0, 3\}$
```
 |abc
-+---
0|abc
1|bca
2|cab
3|abc
4|bca
5|cab
```

$\langle2\rangle=\{0, 2, 4\}$
```
 |ab
-+--
0|ab
1|ba
2|ab
3|ba
4|ab
5|ba
```

$\langle1\rangle=\{0, 1, 2, 3, 4, 5\}$
```
 |a
-+-
0|a
1|a
2|a
3|a
4|a
5|a
```

There are 4 transitive $\mathbb{Z}_6$-sets up to isomorphism.

**Exercise 20**
$\langle\rho_0\rangle=\{\rho_0\}$
```
   |abcdef
---+------
i  |abcdef
123|bcaefd
132|cabfde
23 |dfeacb
13 |fedcba
12 |edfbac
```

$\langle\rho_1\rangle=\{\rho_0,\rho_1,\rho_2\}$
```
   |ab
---+--
i  |ab
123|ab
132|ab
23 |ba
13 |ba
12 |ba
```

$\langle\mu_1\rangle=\{\rho_0,\mu_1\}$
```
   |abc
---+---
i  |abc
123|bca
132|cab
23 |acb
13 |cba
12 |bac
```
$\langle \mu_2\rangle$ and $\langle \mu_3\rangle$ are conjugate to $\langle \mu_1\rangle$, so there are no other $S_3$-sets up to isomorphism.

---
Unused work below

$\phi(gH)=gK$ fails because $\phi(kH)=kK=K=eK=\phi(eH)$ and since $\phi$ is bijective, $kH=H$ so $k\in H$ for all $k\in K$, which means either $|L_K|\neq|L_H|$ contradicting that $\phi$ is a bijection, or $H=K$ contradicting that they were distinct
$\phi(gH)=g_0gg_0^{-1}K$ fails
$\phi(gH)=g_0gg_0^{-1}g_0Hg_0^{-1}=g_0gHg_0^{-1}$
$g\phi(H)=gg_0Hg_0^{-1}$
$g_0gh_1g^{-1}_0=gg_0h_2g^{-1}_0$
$g_0gh_1=gg_0h_2$
$g_0^{-1}g^{-1}g_0g=h_3$

$\rho_0H=\{\rho_0, \mu_1\}=\mu_1H$
$\rho_1H=\{\rho_1, \mu_3\}=\mu_3H$
$\rho_2H=\{\rho_2, \mu_2\}=\mu_2H$
$\rho_0K=\{\rho_0, \mu_2\}=\mu_2K=\rho_1H\rho_1^{-1}$
$\rho_1K=\{\rho_1, \mu_1\}=\mu_1K$
$\rho_2K=\{\rho_2, \mu_3\}=\mu_3K$