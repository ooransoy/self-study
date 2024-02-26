**Exercise 1**

a.

$K=\{0,3,6,9\}$

b.

$0+K=\{0,3,6,9\}$

$1+K=\{1,4,7,10\}$

$2+K=\{2,5,8,11\}$

c.

$\mu(0+K) = 0$

$\mu(1+K) = 1$

$\mu(1+K) = 2$



**Exercise 2**

a.

$K = \{0, 6, 12\}$

b.

$0+K=\{0, 6, 12\}$

$1+K=\{1, 7, 13\}$

$2+K=\{2, 8, 14\}$

$3+K=\{3, 9, 15\}$

$4+K=\{4, 10, 16\}$

$5+K=\{5, 11, 17\}$

c.

$\langle 2\rangle$

d.

$\mu(n+K)=2n$



**Exercise 3**

a.

$H+N=\langle 2\rangle$

$H\cap N=\langle 12\rangle$

b.

$0+N=\{0, 6, 12, 18\}$

$2+N=\{2, 8, 14, 20\}$

$4+N=\{4, 10, 16, 22\}$

c.

$0 + H\cap N=\{0, 12\}$

$4 + H\cap N=\{4, 16\}$

$8 + H\cap N=\{8, 20\}$

d.

$\gamma : \mathbb{Z}_{24}\to \mathbb{Z}_6$

$\gamma(x)=x\mod 6$

$\mathrm{Ker}(\gamma)=\langle 6\rangle=N$



$HN/N=\langle2\rangle/N=\{0+N,2+N,4+N\}$

$\gamma[H]=\gamma[HN]=\{0, 2, 4\}$

$H/(H\cap N)=\langle4\rangle/\langle12\rangle=\{0+\langle12\rangle, 4+\langle12\rangle, 8+\langle12\rangle\}$

The isomorphism $\mu_1 : HN/N \to \gamma[H]$ is given by the First Isomorphism Theorem as $\mu_1(x+N)=\gamma(x)$.

$\mu_1(0+N)=0$

$\mu_1(2+N)=2$

$\mu_1(4+N)=4$

Similarly, the theorem gives an isomorphism $\mu_2 : H/(H\cap N)\to \gamma[H]$ by $\mu_2(x+\langle12\rangle)=\gamma(x)$.

$\mu_2(0+\langle12\rangle)=0$

$\mu_2(4+\langle12\rangle)=4$

$\mu_2(8+\langle12\rangle)=2$

$\phi=\mu_2^{-1}\mu_1$ gives an isomorphism $\phi:HN/N\to H(H\cap N)$.

$\phi(0+N)=\mu_2^{-1}(0)=0+\langle12\rangle$

$\phi(2+N)=\mu_2^{-1}(2)=8+\langle12\rangle$

$\phi(4+N)=\mu_2^{-1}(4)=4+\langle12\rangle$



**Exercise 4**

a.

$HN=\langle3\rangle$

$H\cap N=\langle18\rangle$

b.

$0+N=\{0, 9, 18, 27\}$

$3+N=\{3, 12, 21, 30\}$

$6+N=\{6, 15, 24, 33\}$

c.

$0+H\cap N=\{0, 18\}$

$6+H\cap N=\{6, 24\}$

$12+H\cap N=\{12, 30\}$

d.

$\gamma : \mathbb{Z}_{36}\to \mathbb{Z}_9$

$\gamma(x)=x\mod 9$

$\mathrm{Ker}(\gamma)=\langle 9\rangle=N$



$HN/N=\langle3\rangle/N=\{0+N,3+N,6+N\}$

$\gamma[H]=\gamma[HN]=\{0, 3, 6\}$

$H/(H\cap N)=\langle6\rangle/\langle18\rangle=\{0+\langle18\rangle, 6+\langle18\rangle, 12+\langle18\rangle\}$

$\mu_1: HN/N\to \gamma[H]$, $\mu_1(x+N)=\gamma(x)$

$\mu_1(0+N)=0$

$\mu_1(3+N)=3$

$\mu_1(6+N)=6$

$\mu_2: H/(H\cap N)\to \gamma[H]$, $\mu_1(x+\langle18\rangle)=\gamma(x)$

$\mu_2(0+\langle18\rangle)=0$

$\mu_2(6+\langle18\rangle)=6$

$\mu_2(12+\langle18\rangle)=3$

$\phi: HN/N\to H/(H\cap N)$, $\phi=\mu_2^{-1}\mu_1$

$\phi(0+N)=\mu_2^{-1}(0)=0+\langle18\rangle$

$\phi(3+N)=\mu_2^{-1}(3)=12+\langle18\rangle$

$\phi(6+N)=\mu_2^{-1}(6)=6+\langle18\rangle$



**Exercise 5**

a.

$0+H=\{0, 4, 8, 12, 16, 20\}$

$1+H=\{1, 5, 9, 13, 17, 21\}$

$2+H=\{2, 6, 10, 14, 18, 22\}$

$3+H=\{3, 7, 11, 15, 19, 23\}$

b.

$0+K=\{0, 8, 16\}$

$1+K=\{1, 9, 17\}$

$2+K=\{2, 10, 18\}$

$3+K=\{3, 11, 19\}$

$4+K=\{4, 12, 20\}$

$5+K=\{5, 13, 21\}$

$6+K=\{6, 14, 22\}$

$7+K=\{7, 15, 23\}$

c.

$0+K=\{0, 8, 16\}$

$4+K=\{4, 12, 20\}$

d.

$(0+K)+H/K=\{0+K, 4+K\}$

$(1+K)+H/K=\{1+K, 5+K\}$

$(2+K)+H/K=\{2+K, 6+K\}$

$(3+K)+H/K=\{3+K, 7+K\}$

e.

$\phi: G\to (G/K)/(H/K)$, $\phi(x)=(x+K)+H/K$

$\mathrm{Ker}(\phi)=H$

The First Isomorphism Theorem gives an isomorphism $\mu:G/H\to(G/K)/(H/K)$ s.t. $\phi(x)=\mu(\gamma_H(x))$.

$\phi(x)=(x+K)+H/K$

$\gamma_H(x)=x+H$

$\mu(x+H)=(x+K)+H/K$ for all $x\in G$



**Exercise 6**

a.

$0+H=\{0,9,18,27\}$

$1+H=\{1,10,19,28\}$

$2+H=\{2,11,20,29\}$

$3+H=\{3,12,21,30\}$

$4+H=\{4,13,22,31\}$

$5+H=\{5,14,23,32\}$

$6+H=\{6,15,24,33\}$

$7+H=\{7,16,25,34\}$

$8+H=\{8,17,26,35\}$

b.

$0+K=\{0, 18\}$

$1+K=\{1, 19\}$

$2+K=\{2, 20\}$

$3+K=\{3, 21\}$

$4+K=\{4, 22\}$

$5+K=\{5, 23\}$

$6+K=\{6, 24\}$

$7+K=\{7, 25\}$

$8+K=\{8, 26\}$

$9+K=\{9, 27\}$

$10+K=\{10, 28\}$

$11+K=\{11, 29\}$

$12+K=\{12, 30\}$

$13+K=\{13, 31\}$

$14+K=\{14, 32\}$

$15+K=\{15, 33\}$

$16+K=\{16, 34\}$

$17+K=\{17, 35\}$

c.

$0+K=\{0, 18\}$

$9+K=\{9, 27\}$

d.

$(0+K)+H/K=\{0+K, 9+K\}$

$(1+K)+H/K=\{1+K, 10+K\}$

$(2+K)+H/K=\{2+K, 11+K\}$

$(3+K)+H/K=\{3+K, 12+K\}$

$(4+K)+H/K=\{4+K, 13+K\}$

$(5+K)+H/K=\{5+K, 14+K\}$

$(6+K)+H/K=\{6+K, 15+K\}$

$(7+K)+H/K=\{7+K, 16+K\}$

$(8+K)+H/K=\{8+K, 17+K\}$

e.

$\phi: G\to (G/K)/(H/K)$, $\phi(x)=(x+K)+H/K$

$\mathrm{Ker}(\phi)=H$

The First Isomorphism Theorem gives an isomorphism $\mu:G/H\to(G/K)/(H/K)$ s.t. $\phi(x)=\mu(\gamma_H(x))$.

$\phi(x)=(x+K)+H/K$

$\gamma_H(x)=x+H$

$\mu(x+H)=(x+K)+H/K$ for all $x\in G$



**Exercise 7**

$hkh^{-1}\in H$ for all $k\in H\cap N$ and $h\in H$ since $H$ is a subgroup and all three of $h$, $k$, and $h^{-1}$ are in $H$. $hkh^{-1}\in N$ since $H\cap N\subseteq N$ and $h\in G$ and $N$ is normal in $G$. Combining these two, we get $hkh^{-1}\in H\cap N$ for all $h\in H$ and $k\in H\cap N$ showing that $H\cap N$ is normal in $H$, completing the proof.



**Exercise 8**

$H\triangleleft K\triangleleft L \trianglelefteq G$

$A=G/H, B=K/H, C=L/H$

a.

For all $b\in B$ and $a\in A$, $aba^{-1}=(gH)(kH)(g^{-1}H)$ for some $k\in K$ and $g\in G$. Since $H$ is normal in $K$ and $G$, $kH=Hk$ and $gH=Hg$ so $gHkHg^{-1}H=gkg^{-1}H$. Since $K$ is normal in $G$, $gkg^{-1}\in K$, so $gkg^{-1}=k_0$ for some $k_0\in K$, and $gkg^{-1}H=k_0H\in K/H=B$, showing that $aba^{-1}\in B$ and that $B$ is normal in $A$.

The same argument can be made for $C$ and $A$ by swapping $L$ and $K$, likewise for $B$ and $C$.

b.

By the Third Isomorphism Theorem, $(A/C)/(B/C)\simeq A/B$. $A=(G/H)$ and $B=(K/H)$, so $A/B=(G/H)/(K/H)$, and applying the theorem again we get $G/K$.



**Exercise 9**

Let $\phi:G\to L$ be given by $\phi(k)=e$ for all $k\in K$ and $\phi(l)=l$ for all $l\in L$. $\phi$ is defined for all $g\in G$ because since $K\vee L=G$, there must be $k\in K$ and $l\in L$ s.t. $kl=g$. $\phi(g)=\phi(k)\phi(l)$ since $\phi$ is a homomorphism, and $\phi(g)=\phi(k)\phi(l)=l$.

It is readily seen that $\mathrm{Ker}(\phi)=K$, and that $\phi[G]=L$. Applying the First Isomorphism Theorem, we have that $G/K\simeq\phi[G]=L$, so $G/K\simeq L$. $G/L=K$ follows WLOG.

