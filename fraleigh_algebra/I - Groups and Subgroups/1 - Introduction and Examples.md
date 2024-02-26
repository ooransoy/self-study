**Exercise 1-8**
$0-1i$
$1+0i$
$0-1i$
$0+1i$
$23+7i$
$26-2i$
$17-15i$
$1+3i+3i^2+i^3 = 1+3i-3-i = -2+2i$

**Exercise 9**
$1+5(-i)+10(-i)^2+10(-i)^3+5(-i)^4+(-i)^5 =$
$1-5i-10+10i+5-i = -4+4i$

**Exercise 10-11**
$5$
$2\sqrt{13}$

**Exercise 12-15**
$5(\frac{3}{5} + \frac{-4}{5}i)$
$\sqrt{2}(\frac{-1}{\sqrt{2}} + \frac{1}{\sqrt{2}}i)$
$13(\frac{12}{13} + \frac{5}{13}i)$
$\sqrt{34}(\frac{-3}{\sqrt{34}} + \frac{5}{\sqrt{34}}i)$

**Exercise 16-21**
$1$, $i$, $-1$, $-i$
$\frac{1+i}{\sqrt{2}}$, $\frac{1-i}{\sqrt{2}}$, $\frac{-1+i}{\sqrt{2}}$, $\frac{-1-i}{\sqrt{2}}$
$1+\sqrt{3}i$, $-2$, $1-\sqrt{3}i$
$\frac{-3(\sqrt{3}+i)}{2}$, $\frac{-3(-\sqrt{3}+i)}{2}$, $3i$
$1$, $\frac{1+\sqrt{3}i}{2}$, $\frac{1-\sqrt{3}i}{2}$, $-i$, $\frac{-1-\sqrt{3}i}{2}$, $\frac{-1+\sqrt{3}i}{2}$
$\sqrt{3}+i$, $2i$, $-\sqrt{3}+i$, $-\sqrt{3}-i$, $-2i$, $\sqrt{3}-i$

**Exercise 22-27**
$9$
$4$
$14.8$
$\frac{3}{8}$
$\frac{\pi}{4}$
$\sqrt{2}$

**Exercise 28**
$8$ does not satisfy $0 \leq x \lt 6$, and is not in $\mathbb{R}_6$.

**Exercise 29-34**
$11$
$\frac{5\pi}{4}$
$5$
$4$
$1$, $7$
$0$, $1$, $2$, $3$

**Exercise 35**
0, 5, 2, 7, 4, 1, 6, 3

**Exercise 36**
0, 4, 1, 5, 2, 6, 3

**Exercise 37**
Consider the fourth power of $\zeta$, and the fourth multiple of $4$. In $U_6$, $\zeta^4 = e^{i(4\pi/3)}$, so $\zeta^4 \neq \zeta$. In $\mathbb{Z}_6$, $4 +_6 4 +_6 4 +_6 4 = 4$, so the fourth multiple of $4$ is equal to itself, meaning that our isomorphism would have two map two distinct elements in $U_6$ to the same element in $\mathbb{Z}_6$. Such an isomorphism obviously cannot exist.

**Exercise 38**
$e^{ia}e^{ib} = e^{i(a+b)}$
$(\cos(a) + i\sin(a))(\cos(b) + i\sin(b))= \cos(a+b) + i\sin(a+b)$
$(\cos(a)\cos(b) - \sin(a)\sin(b)) + (\sin(a)\cos(b) + \cos(a)\sin(b))i= \cos(a+b) + i\sin(a+b)$
Extracting the real part:
$\cos(a)\cos(b) - \sin(a)\sin(b) = \cos(a+b)$
Extracting the imaginary part:
$\sin(a)\cos(b) - \cos(a)\sin(b) = \sin(a+b)$

**Exercise 39**
$z_1z_2=|z_1||z_2|(\cos(\theta_1)+i\sin(\theta_1))(\cos(\theta_2)+i\sin(\theta_2))$
$(\cos(\theta_1)+i\sin(\theta_1))(\cos(\theta_2)+i\sin(\theta_2)) = (\cos(\theta_1)\cos(\theta_2)-\sin(\theta_1)\sin(\theta_2))+i(\sin(\theta_1)\cos(\theta_2)+\cos(\theta_1)\sin(\theta_2))$
Substituting the first identity the right hand side becomes:
$\cos(\theta_1+\theta_2)+i(\sin(\theta_1)\cos(\theta_2)+\cos(\theta_1)\sin(\theta_2))$
Substituting the second identity:
$\cos(\theta_1+\theta_2)+i\sin(\theta_1+\theta_2)$

Substituting this in the equation we started with:
$z_1z_2=|z_1||z_2|(\cos(\theta_1+\theta_2)+i\sin(\theta_1+\theta_2))$

**Exercise 40**

a.
	$z^3 = |z|^3(\cos(3\theta)+i\sin(3\theta)) = |z|^3(\cos(\theta)+i\sin(\theta))^3$
	By the binomial theorem:
	$(\cos(\theta)+i\sin(\theta))^3 = \cos(\theta)^3+3\cos(\theta)^2(i\sin(\theta))+3\cos(\theta)(i\sin(\theta))^2+(i\sin(\theta))^3$
	$\cos(3\theta)+i\sin(3\theta)=\cos(\theta)^3+3i\cos(\theta)^2\sin(\theta)-3\cos(\theta)\sin(\theta)^2-i\sin(\theta)^3$
	Extracting the real part:
	
	$\cos(3\theta)=\cos(\theta)^3-3\cos(\theta)\sin(\theta)^2$
b.
	$\cos(3\theta)=\cos(\theta)^3-3\cos(\theta)\sin(\theta)^2$
	$\sin(\theta)^2+\cos(\theta)^2=1$
	$\sin(\theta)^2=1-\cos(\theta)^2$
	Substituting this into the first equation:
	$\cos(3\theta)=\cos(\theta)^3-3\cos(\theta)(1-\cos(\theta)^2)$
	Expanding:
	$\cos(3\theta)=\cos(\theta)^3-3\cos(\theta)+3\cos(\theta)\cos(\theta)^2)$
	$\cos(3\theta)=4\cos(\theta)^3-3\cos(\theta)$

**Exercise 41**

$$e^x=\sum_{n=0}^\infty \frac{x^n}{n!}$$
$$\sin(x)=\sum_{n=0}^\infty (-1)^{n}\frac{x^{2n+1}}{(2n+1)!}$$
$$\cos(x)=\sum_{n=0}^\infty (-1)^{n}\frac{x^{2n}}{(2n)!}$$
$$e^{i\theta}=\sum_{n=0}^\infty \frac{(i\theta)^n}{n!}=\sum_{n=0}^\infty \frac{i^n\theta^n}{n!}$$
$$e^{i\theta}=\sum_{n=0}^\infty \frac{i^{2n}\theta^{2n}}{(2n)!}+\sum_{n=0}^\infty \frac{i^{2n+1}\theta^{2n+1}}{(2n+1)!}$$
because $\{2n | n\in\mathbb{Z}^+\}\cup\{2n+1 | n\in\mathbb{Z}^+\}=\mathbb{Z}^+$
$$e^{i\theta}=\sum_{n=0}^\infty i^{2n}\frac{\theta^{2n}}{(2n)!}+\sum_{n=0}^\infty i^{2n+1}\frac{\theta^{2n+1}}{(2n+1)!}$$
$$e^{i\theta}=\sum_{n=0}^\infty (i^2)^n\frac{\theta^{2n}}{(2n)!}+\sum_{n=0}^\infty (i^2)^ni\frac{\theta^{2n+1}}{(2n+1)!}$$
$$e^{i\theta}=\sum_{n=0}^\infty (-1)^n\frac{\theta^{2n}}{(2n)!}+i\sum_{n=0}^\infty (-1)^n\frac{\theta^{2n+1}}{(2n+1)!}$$
substituting:
$$e^{i\theta}=\cos(\theta)+i\sin(\theta)$$
