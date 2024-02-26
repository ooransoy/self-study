**Exercise 1-6**

0 1 2 3 4 5 6 7 8 9 10 11

0 2 4 6 8 10

0 2 4 6 8 10 12 14 16

0 6 12 18 24 30

$6\mathbb{Z}$

$3\mathbb{Z}$



**Exercise 7**

$a^3b$

$a^2$

$a^2$



**Exercise 8-10**

```

*|eabc

-+----

e|eabc

a|aecb

b|bcea

c|cbae



*|eabcdf

-+------

e|eabcdf

a|aecbfd

b|bdefac

c|cfadeb

d|dbfeca

f|fcdabe



*|eabcdf

-+------

e|eabcdf

a|acfebd

b|bdefac

c|cedafb

d|dfcbea

f|fbadce

```



**Exercise 11**

If for every sequence of arc types that go $u\to v$, there is another path $u\to v$ with the sequence of arc types reversed.



**Exercise 12**

The group is not commutative.



**Exercise 13**

No.

(subjective?)



**Exercise 14**

No. There is no identity element, it cannot be a subgroup.



**Exercise 15**

![[Pasted image 20220723154508.png]]



**Exercise 16**

![[Pasted image 20220723153407.png]]



**Exercise 17**

a.

	Every path from $e$ back to itself is a relation.

b.

	$aba^{-1}b=e$

	$a^4=e$

	$b^2=e$



**Exercise 18**

![[Pasted image 20220723155446.png]]



**Exercise 19**

Consider the group $\{a_0,b_0,a_1,b_1,a_2,b_2,...,a_n,b_n\}$ where 

$a_xa_y=a_{x+y \mod n}$

$a_xb_y=b_{x+y\mod n}$

$b_xa_y=b_{x-y\mod n}$

$b_xb_y=a_{x-y \mod n}$



Associativity:

$a_{x+y+z}=a_{x+y+z}$

$a_{(x+y)+z}=a_{x+(y+z)}$

$a_{x+y}a_z=a_xa_{y+z}$

$(a_xa_y)a_z=a_x(a_ya_z)$



$b_{x+y+z}=b_{x+y+z}$

$b_{(x+y)+z}=b_{x+(y+z)}$

$a_{x+y}b_z=a_xb_{y+z}$

$(a_xa_y)b_z=a_x(a_yb_z)$



$b_{x+y-z}=b_{x+y-z}$

$b_{(x+y)-z}=b_{x+(y-z)}$

$b_{x+y}a_z=a_xb_{y-z}$

$(a_xb_y)a_z=a_x(b_ya_z)$



$a_{x+y-z}=a_{x+y-z}$

$a_{(x+y)-z}=a_{x+(y-z)}$

$b_{x+y}b_z=a_xa_{y-z}$

$(a_xb_y)b_z=a_x(b_yb_z)$



$b_{x-y-z}=b_{x-y-z}$

$b_{(x-y)-z}=b_{x-(y+z)}$

$b_{x-y}a_z=b_xa_{y+z}$

$(b_xa_y)a_z=b_x(a_ya_z)$



$a_{x-y-z}=a_{x-y-z}$

$a_{(x-y)-z}=a_{x-(y+z)}$

$b_{x-y}b_z=b_xb_{y+z}$

$(b_xa_y)b_z=b_x(a_yb_z)$



$a_{x-y+z}=a_{x-y+z}$

$a_{(x-y)+z}=a_{x-(y-z)}$

$a_{x-y}a_z=b_xb_{y-z}$

$(b_xb_y)a_z=b_x(b_ya_z)$



$b_{x-y+z}=b_{x-y+z}$

$b_{(x-y)+z}=b_{x-(y-z)}$

$a_{x-y}b_z=b_xa_{y-z}$

$(b_xb_y)b_z=b_x(b_yb_z)$



Identity:

$e=a_0$

$a_xa_0=a_{x+0}=a_x$

$a_0a_x=a_{0+x}=a_x$

$b_xa_0=b_{x-0}=b_x$

$a_0b_x=b_{0+x}=b_x$



Inverse:

$a_xa_{-x}=a_0$

$b_xb_x=a_0$



Nonabelian:

$a_1b_2=b_3\neq b_1=b_2a_1$

($b_3 \neq b_1$ holds because $n\geq 3$)

