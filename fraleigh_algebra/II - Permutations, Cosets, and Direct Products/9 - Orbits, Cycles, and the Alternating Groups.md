**Exercises 1-6**
$(1,5,2)(4,6)$
$(1,5,8,7)(2,6,3)$
$(1,2,3,5,4)(7,8)$
$\mathbb{Z}$
$2\mathbb{Z}, 2\mathbb{Z}+1$
$3\mathbb{Z}, 3\mathbb{Z}+1, 3\mathbb{Z}+2$

**Exercises 7-9**
$\begin{pmatrix}1&2&3&4&5&6&7&8 \\ 4&1&3&5&8&6&2&7 \end{pmatrix}$
$\begin{pmatrix}1&2&3&4&5&6&7&8 \\ 3&7&2&8&5&4&1&6 \end{pmatrix}$
$\begin{pmatrix}1&2&3&4&5&6&7&8 \\ 5&4&3&7&8&6&2&1 \end{pmatrix}$

**Exercises 10-12**
$(1,8)(3,6,4)(5,7)$   |   $(1,8)(3,4)(3,6)(5,7)$
$(1,3,4)(2,6)(5,8,7)$   |   $(1,4)(1,3)(2,6)(5,7)(5,8)$
$(1,3,4,7,8,6,5,2)$   |   $(1,2)(1,5)(1,6)(1,8)(1,7)(1,4)(1,3)$

**Exercise 13**
a. 4
b. The order of a cycle in a permutation group is the length of that cycle.
c. 6, 4
d. 6, 6, 8
e. The order of a permutation is the least common multiple of all the lengths of its disjoint cycles.

**Exercises 14-18**
6
6
12
30
105

**Exercise 19**
![[Pasted image 20230912161017.png]]

**Exercise 20-22**
Correct
A cycle is a permutation containing only one orbit _of size greater than 1_.
The alternating group _on $n$ letters is the group of all even permutations _on $n$ letters_.

**Exercise 23**
a. F
b. T
c. T
d. F
e. F
f. F
g. T
h. T
i. T
j. F

**Exercise 24**
$\rho_0, \rho_1, \rho_2$
```
 |012
-+---
0|012
1|120
2|201
```

**Exercise 25**
The determinant of a permutation matrix can only be 1 or -1, corresponding to even and odd permutations respectively.

**Exercise 26**
Applying a transposition to a permutation either splits one of its orbits or merges two of its orbits, changing the number of orbits by one. This means that an even number of transpositions preserves the parity of the number of orbits, while an odd number of transpositions changes it.

**Exercise 27**
a.
We know that it is possible to represent a cycle of length $n$ as the product of $n-1$ transpositions. Let $k$ be the number of orbits of the permutation, and let $n_i$ be the sizes of its orbits. Clearly, because the orbits are disjoint, we need a total of $\sum_{i=1}^k (n_i-1)=(\sum_{i=1}^k n_i)-k=n-k\leq n-1$ transpositions to produce the permutation. 
b.
A permutation that is not a cycle must have at least 2 orbits, making $k\geq 2$ and $n-k \leq n-2$. If it only had one orbit, it would have to be of size $n$ which is greater than one, with no other orbits, satisfying the definition of a cycle.
c.
We can produce the identity permutation with two of the same transposition. Since $\iota\iota=\iota$, we can repeat this product as many times as we want and produce the identity permutation with $2l$ transpositions for any positive $l$.
There is a way to write every odd permutation in $k$ transpositions where $k\leq n-1$ and $k$ is odd. $2n+3$ is obviously odd as well, so $2n+3-k$ must be even. Let $2l=2n+3-k$. ($l$ is obviously positive since $2n+3>k$) We can write the identity permutation with this many transpositions. Multiplying the $k$ transpositions and the $2l$ transpositions, we get the same permutation because $\iota\sigma=\sigma$. We have obtained a way to produce the permutation with $k+2l=2n+3$ transpositions.
There is a way to write every even permutation in $k$ transpositions where $k\leq n-1$ and $k$ is even. $2n+8$ is obviously even as well, so $2n+8-k$ must be even. Let $2l=2n+8-k$. ($l$ is obviously positive since $2n+8>k$) We can write the identity permutation with this many transpositions. Multiplying the $k$ transpositions and the $2l$ transpositions, we get the same permutation because $\iota\sigma=\sigma$. We have obtained a way to produce the permutation with $k+2l=2n+8$ transpositions.

**Exercise 28**
TODO

**Exercise 29**
It is sufficient to show that if there exists an odd permutation in $H$, exactly half of the elements in $H$ are even. Let the odd permutation be $\pi$. Let $E$ be the set of even permutations in $H$, and let $O$ be the set of odd permutations in $H$. Obviously, it is sufficient to show that there is a bijection between $E$ and $O$.
Consider $f(\sigma) = \sigma \pi$ defined only on $E$. Since $\pi$ is odd and $\sigma$ is even, $\sigma \pi$ will obviously be odd, showing that $f(\sigma)$ will always be in $O$.
$f$ is obviously injective, it suffices to show that it is surjective. Consider any element $o$ in $O$. Since $\pi^{-1}$ is odd (obvious to see from $\pi$ being odd and $\iota$ being even and $\pi\pi^{-1}=\iota$), $o\pi^{-1}$ is even and in $E$. $f(o\pi^{-1})=o\pi^{-1}\pi=o$, completing the proof.

**Exercise 30**
$n$

**Exercise 31**
$H$ obviously contains inverses for all elements, it is sufficient to show that $H$ is closed.

Let $\sigma$ and $\pi$ be from $H$, and let $a$ be from $A$. If neither $\sigma$ nor $\pi$ move $a$, then $\sigma\pi$ will not move $a$. So, for $\sigma\pi$ to move $a$, it is necessary for at least one of $\sigma$ and $\pi$ to move $a$. Since there are a finite number of elements that are moved by $\sigma$ and by $\pi$, there are a finite number of elements that satisfy this condition. This means that $\sigma\pi$ moves a finite number of elements, showing that $\sigma\pi\in H$ and completing the proof.

**Exercise 32**
No. Take 100 elements from $A$. Define $\sigma$ to be a cycle on the first 50, and $\pi$ to be a cycle on the last 50. $\sigma\pi$ moves 100 elements, showing that $K$ is not closed

**Exercise 33**
Let $\pi$ be any odd permutation in $S_n$. Since $\sigma^{-1}$ is odd, $\pi\sigma^{-1}$ is even, meaning it is in $A_n$. $(\pi\sigma^{-1})\sigma=\pi$, showing that $\pi$ is the product of $\sigma$ and some element from $A_n$.

**Exercise 34**
Let $\sigma$ be $(a_0, a_1, a_2, \ldots, a_{n-1})$. It is sufficient to show that the orbit of $\sigma^2$ containing $a_0$ is all of the $a_i$. Obviously, if any even-indexed element is in the orbit, all even-indexed elements are in the orbit - and likewise for odd-indexed elements. Since $a_0$ is in the orbit, all even-indexed elements are in the orbit. This means that $a_{n-1}$ is also in the orbit. $\sigma^2(a_{n-1})=a_1$, leading to all odd-indexed elements also being in the orbit, completing the proof.

**Exercise 35**
...$n$ and $r$ are coprime.

**Exercise 36**
It is sufficient to show that $\lambda_a$ is injective. If $\lambda_a(x)=\lambda_a(y)$, $ax=ay$, $x=y$ by simple cancellation, completing the proof.

**Exercise 37**
$H$ is closed:
$(\lambda_a\lambda_b)(x)=\lambda_a(\lambda_b(x))=abx=\lambda_{ab}$
Identity:
$(\lambda_e\lambda_a)(x)=\lambda_e(\lambda_a(x))=eax=ax=\lambda_a(x)$, showing that $\lambda_e$ is an identity
Inverse:
$(\lambda_a\lambda_{a^{-1}})(x)=aa^{-1}x=ex=\lambda_e(x)$, showing that $\lambda_{a^{-1}}$ is an inverse of $\lambda_a$.

**Exercise 38**
It is sufficient to show that for any $a,b\in G$, there exists $c\in G$ s.t. $\lambda_c(a)=b$.
$\lambda_{ba^{-1}}(a)=ba^{-1}a=b$, showing that $ba^{-1}$ is a sufficient $c$.

**Exercise 39**
Let's say that a transposition $(i,j)$ is of distance $|i-j|$.

Label $(1, 2, 3, \ldots, n)$ as $\sigma$.
We will first show that for any $1\leq k < n$ $\sigma^{k-1}(1, 2)\sigma^{-k+1}=(k, k+1)$.
$\sigma^{k-1}(1, 2)\sigma^{-k+1}(k)=\sigma^{k-1}(1, 2)(1)=\sigma^{k-1}(2)=k+1$
$\sigma^{k-1}(1, 2)\sigma^{-k+1}(k+1)=\sigma^{k-1}(1, 2)(2)=\sigma^{k-1}(1)=k$
showing that the permutation transposes $k$ and $k+1$.
Let $1\leq x < k$.
$\sigma^{k-1}(1, 2)\sigma^{-k+1}(x)=\sigma^{k-1}(1, 2)(x+n-k+1)$
$x+n-k+1$ cannot be $1$ or $2$ as $x+n-k>1$ because both $x$ and $n-k$ are $>1$, so $\sigma^{k-1}(1, 2)\sigma^{-k+1}(x)=\sigma^{k-1}(x+n-k+1)=x$, showing that $x$ is untouched.
Let $k+1 < x \leq n$.
$\sigma^{k-1}(1, 2)\sigma^{-k+1}(x)=\sigma^{k-1}(1, 2)(x-k+1)$
$x-k+1$ cannot be $1$ or $2$ as $x-k>1$ because $x>k+1$, so $\sigma^{k-1}(1, 2)\sigma^{-k+1}(x)=\sigma^{k-1}(x+k+1)=x$, showing that $x$ is untouched.

This shows that all transpositions of distance 1 are generated. We will show that transpositions of all distances are generated. For the sake of induction, assume that all transpositions of distance $k$ are generated. We will show that all transpositions of distance $k+1$ are generated. Let $1\leq m \leq n-(k+1)$. A simple computation shows that $(m,m+k)(m+k,m+k+1)(m,m+k)=(m,m+k+1)$, showing that we can obtain any transposition of distance $k+1$, closing the induction.

Since we can generate any transposition, by Corollary 9.12, we can generate any permutation, completing the proof.