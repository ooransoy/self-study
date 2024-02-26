**Exercises 1-3**
$\langle 3\rangle=\{3, 2, 6, 4, 5, 1\}$
$\langle 2\rangle=\{2, 4, 8, 5, 10, 9, 7, 3, 6, 1\}$
$\langle 6\rangle=\{6, 2, 12, 4, 7, 8, 14, 16, 11, 15, 5, 13, 10, 9, 3, 1\}$

**Exercise 4**
$3^{47}=(3^{22})^23^3\equiv3^3=4\mod 23$

**Exercise 5**
$37^{49}=(37^6)^837\equiv 37\equiv 2\mod 37$

**Exercise 6**
$2^{17}\equiv 14\mod 18$
$2^{(2^{17})}+1=2^{18q+14}+1\equiv2^{14}+1\mod 19$
$2^{14}\equiv2^{-4}\equiv16^{-1}\equiv6\mod 19$
7

**Exercise 7**
```
 1  2  3  4  5  6  7  8  9 10
 1  1  2  2  4  2  6  4  6  4
 
11 12 13 14 15 16 17 18 19 20
10  4 12  6  8  8 16  6 18  8
 
21 22 23 24 25 26 27 28 29 30
12 10 22  8 20 12 18 12 28  8
```

**Exercise 8**
$p(p-1)$

**Exercise 9**
$(p-1)(q-1)$

**Exercise 10**
$\varphi(24)=8$
$8|1000$ and $\gcd(7,24)=1$
so $7^{1000}=(7^8)^{125}\equiv1^125=1\mod 24$

**Exercises 11-18**
$x\equiv1\mod 2$, $\{1, 3\}$
$\{5\}$
$\varnothing$
$7x\equiv5\mod 8$, $\{3, 11, 19\}$
$\varnothing$
$\{9\}$
$5x\equiv2\mod 13$, $\{3, 16, 29, 42, 55\}$
$3x\equiv4\mod 10$, $\{8, 18, 28, 38, 48, 58, 68, 78, 88, 98, 108, 118, 128\}$

**Exercise 19**
$(p-2)!\equiv(p-1)!(p-1)^{-1}\equiv-(p-1)^{-1}\mod p$
Since $(p-1)^2=p^2-2p+1$, it is obviously $1$ modulo $p$, showing that $p-1$ is its own inverse.
$\equiv -(p-1)\equiv1\mod p$

**Exercises 20-22**
$34!\equiv35!35^{-1}\equiv35^{-1}\equiv18\mod 37$
$49!\equiv51!51^{-1}50^{-1}\equiv26(35)\equiv9\mod 53$
$24!\equiv27!27^{-1}26^{-1}25^{-1}\equiv14(19)7\equiv6\mod29$

**Exercise 23**
a. F
b. T
c. T
d. F ($n=1$)
e. T
f. T
g. F
h. T
i. F ($p|a$ and $p\nmid b$)
j. T 

**Exercise 24**
```
   |  1  5  7 11
---+------------
 1 |  1  5  7 11
 5 |  5  1 11  7
 7 |  7 11  1  5
11 | 11  7  5  1
```
$G_{12}$ is isomorphic to the Klein 4-group.

**Exercise 25**
The nonzero elements of $\mathbb{Z}_p$ form a group under multiplication, and the order of its cyclic groups must divide the order of the group, $p-1$.

**Exercise 26**
The nonzero elements coprime to $n$ in $\mathbb{Z}_n$ form a group under multiplication, and the order of its cyclic groups must divide the order of the group, $\varphi(n)$.

**Exercise 27**
If $x$ is its own multiplicative inverse that must mean that $x^2-1\equiv0\equiv(x-1)(x+1)\mod p$. Since $\mathbb{Z}_p$ has no divisors of zero, $x$ must be either $-1$ (i.e. $p-1$) or $1$.

**Exercise 28**
The statement is obvious for $p=2$. For $p\geq 3$, $p$ is odd therefore $p-1$ - the order of $\mathbb{Z}_p^*$ - is even. $(p-1)!$ is the product of all elements in $\mathbb{Z}_p^*$. Pairing up all the elements with their inverses, by Exercise 27, only $1$ and $p-1$ get paired with themselves, and since there are an even number of elements remaining, all of those $p-3$ elements are grouped into $\frac{p-3}{2}$ pairs. The product of the pairs are all $1$, since they were inverses, so the entire product is equal to $1(p-1)$ which is congruent to $-1$, completing the proof.

**Exercise 29**
We will show that $n^{37}-n$ is divisible by all $p$ s.t. $p-1|36$.
If $p|n$, it is obvious. If not, for $k$ s.t. $(p-1)k=36$, $n^{37}-n\equiv (n^{p-1})^kn-n\equiv1^kn-n\equiv0\mod p$, giving us the result.
As a corollary, we can see that $37$, $19$, $13$, $7$, $5$, $3$ and $2$ all divide $n^{37}-n$. This means that $(37)(19)(13)(7)(3)(2)=383838$ also divides $n^{37}-n$, completing the proof.

**Exercise 30**
In the previous exercise, 5 was not included in the product, so we can include it as a factor and still have it be a divisor.
$383838\times5=1919190$