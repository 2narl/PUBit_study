# BIT151HS – Mathematics-II
## 2024 Question Paper: Worked Solutions

**Purbanchal University | BIT Second Semester**

These solutions follow the questions transcribed in the [2024 question paper](./README.md). Steps are kept concise and exam-oriented. Check the original scan where the transcription is flagged.

---

## Group A

### 1. Evaluate the triple integral

\[
I=\int_0^a\int_0^a\int_0^a(x+y+z)\,dx\,dy\,dz.
\]

Integrating each term over the cube:

\[
I=\frac{a^4}{2}+\frac{a^4}{2}+\frac{a^4}{2}
=\boxed{\frac{3a^4}{2}}.
\]

### 2. Change the order of integration

The supplied expression is
\[
\int_0^\infty\int_y^\infty\frac{e^{-y}}{y}\,dy\,dx.
\]

**The question as transcribed is not mathematically well-formed:** the inner differential is \(dy\), but its lower limit also uses \(y\), and the outer differential is \(dx\) although the outer limit is written in terms of \(y\). Please check the original question-paper image. A reliable solution cannot be given until the variables and limits are confirmed.

### 3. Find the order and degree

\[
\sqrt{\frac{d^3y}{dx^3}}=\frac{dy}{dx}.
\]

Squaring both sides,

\[
\frac{d^3y}{dx^3}=\left(\frac{dy}{dx}\right)^2.
\]

The highest derivative is the third derivative, and its power is one.

\[
\boxed{\text{Order}=3,\qquad\text{Degree}=1.}
\]

### 4. Solve \((x+1)dy=(y-1)dx\)

\[
\frac{dy}{y-1}=\frac{dx}{x+1}
\]

Integrating,

\[
\ln|y-1|=\ln|x+1|+C.
\]

Therefore,

\[
\boxed{y-1=C(x+1).}
\]

### 5. Solve \(y''-4y'+13y=0\)

Auxiliary equation:

\[
m^2-4m+13=0
\]

\[
m=\frac{4\pm\sqrt{-36}}2=2\pm3i.
\]

Hence,

\[
\boxed{y=e^{2x}(C_1\cos3x+C_2\sin3x).}
\]

### 6. Test whether the function is even or odd

\[
f(x)=\log\left|\frac{1-x}{1+x}\right|.
\]

\[
f(-x)=\log\left|\frac{1+x}{1-x}\right|
=-\log\left|\frac{1-x}{1+x}\right|=-f(x).
\]

Thus,

\[
\boxed{f(x)\text{ is an odd function.}}
\]

### 7. Express \(\sin z\) in the form \(u+iv\)

Put \(z=x+iy\).

\[
\sin z=\sin(x+iy)
=\sin x\cosh y+i\cos x\sinh y.
\]

Therefore,

\[
\boxed{u=\sin x\cosh y,\qquad v=\cos x\sinh y.}
\]

### 8. Differentiability implies continuity

If \(f\) is differentiable at \(z_0\), then

\[
\lim_{z\to z_0}\frac{f(z)-f(z_0)}{z-z_0}=f'(z_0).
\]

Now,

\[
f(z)-f(z_0)
=(z-z_0)\frac{f(z)-f(z_0)}{z-z_0}.
\]

Taking the limit as \(z\to z_0\),

\[
\lim_{z\to z_0}[f(z)-f(z_0)]=0.
\]

Hence,

\[
\boxed{\lim_{z\to z_0}f(z)=f(z_0),}
\]

so \(f\) is continuous at \(z_0\).

### 9. Find the zeros

\[
f(z)=\left(\frac{z+2}{z^2+1}\right)^3
=\frac{(z+2)^3}{(z-i)^3(z+i)^3}.
\]

The numerator is zero at \(z=-2\), while the denominator is zero at \(z=\pm i\).

\[
\boxed{\text{Zero: }z=-2\text{ (order 3)}}
\]

\[
\boxed{\text{Poles: }z=i,-i\text{ (order 3 each)}}
\]

### 10. Show that \(z=2\) is a simple pole

\[
f(z)=\frac{z^2-2z+5}{z-2}.
\]

At \(z=2\), the numerator is

\[
2^2-2(2)+5=5\ne0.
\]

The denominator has a simple zero at \(z=2\). Therefore,

\[
\boxed{z=2\text{ is a simple pole.}}
\]

---

## Group B

### 11. Evaluate the double integral over the quarter-circle

\[
I=\iint_Rxy\,dx\,dy,
\]

where \(R\) is the first-quadrant region inside \(x^2+y^2=a^2\).

Use polar coordinates:

\[
x=r\cos\theta,\quad y=r\sin\theta,\quad dx\,dy=r\,dr\,d\theta.
\]

Limits: \(0\le r\le a\), \(0\le\theta\le\pi/2\).

\[
I=\int_0^{\pi/2}\int_0^a r^3\cos\theta\sin\theta\,dr\,d\theta
\]

\[
=\left[\frac{r^4}{4}\right]_0^a
\left[\frac{\sin^2\theta}{2}\right]_0^{\pi/2}
=\boxed{\frac{a^4}{8}}.
\]

### 12. Solve \(y'+\frac{y}{x^2}=\frac1{x^2}\)

This is a linear differential equation. Its integrating factor is

\[
IF=e^{\int dx/x^2}=e^{-1/x}.
\]

Multiplying throughout,

\[
e^{-1/x}y'+\frac{e^{-1/x}}{x^2}y
=\frac{e^{-1/x}}{x^2}.
\]

\[
\frac{d}{dx}(ye^{-1/x})=\frac{e^{-1/x}}{x^2}.
\]

Integrating,

\[
ye^{-1/x}=e^{-1/x}+C.
\]

Thus,

\[
\boxed{y=1+Ce^{1/x}.}
\]

### 13. Solve \(y''-y'-2y=6e^x\)

Auxiliary equation:

\[
m^2-m-2=0\Rightarrow(m-2)(m+1)=0.
\]

\[
CF=C_1e^{2x}+C_2e^{-x}.
\]

For the particular integral,

\[
PI=\frac{6e^x}{1-1-2}=-3e^x.
\]

Therefore,

\[
\boxed{y=C_1e^{2x}+C_2e^{-x}-3e^x.}
\]

### 14. Find the Fourier series of \(f(x)=2x\), \(0\le x\le\pi\)

For a function of period \(2\pi\),

\[
f(x)=\frac{a_0}{2}+\sum_{n=1}^{\infty}(a_n\cos nx+b_n\sin nx).
\]

\[
a_0=\frac{1}{\pi}\int_{-\pi}^{\pi}f(x)\,dx
\]

Using the given one-period definition on \([0,\pi]\) and the stated periodic extension requires the function on the full period. **The supplied statement says period \(2\pi\) but only defines the function on \([0,\pi]\); verify whether the intended interval is \((-\pi,\pi)\) or whether an additional definition is missing.** Do not assume an extension that is not stated.

### 15. Fourier cosine series

\[
f(x)=
\begin{cases}
1,&0<x<\pi/2,\\
0,&\pi/2<x<\pi.
\end{cases}
\]

For a half-range cosine series on \((0,\pi)\),

\[
f(x)=\frac{a_0}{2}+\sum_{n=1}^{\infty}a_n\cos nx.
\]

\[
a_0=\frac{2}{\pi}\int_0^{\pi/2}1\,dx=1.
\]

\[
a_n=\frac{2}{\pi}\int_0^{\pi/2}\cos nx\,dx
=\frac{2}{n\pi}\sin\frac{n\pi}{2}.
\]

Hence,

\[
\boxed{f(x)=\frac12+\sum_{n=1}^{\infty}
\frac{2}{n\pi}\sin\frac{n\pi}{2}\cos nx.}
\]

Equivalently,

\[
\boxed{f(x)=\frac12+\frac{2}{\pi}
\left(\cos x-\frac{\cos3x}{3}+\frac{\cos5x}{5}-\cdots\right).}
\]

### 16. Verify the Cauchy–Riemann equations

\[
f(z)=\frac{x-iy}{x^2+y^2}=u+iv.
\]

Thus,

\[
u=\frac{x}{x^2+y^2},\qquad
v=-\frac{y}{x^2+y^2}.
\]

For \((x,y)\ne(0,0)\),

\[
u_x=\frac{y^2-x^2}{(x^2+y^2)^2},
\quad
v_y=\frac{y^2-x^2}{(x^2+y^2)^2},
\]

\[
u_y=\frac{-2xy}{(x^2+y^2)^2},
\quad
v_x=\frac{2xy}{(x^2+y^2)^2}.
\]

Therefore \(u_x=v_y\) and \(u_y=-v_x\). The Cauchy–Riemann equations are satisfied wherever \(z\ne0\).

### 17. Taylor series of \(1/z\) about \(z=1\)

\[
\frac1z=\frac1{1+(z-1)}.
\]

Using \(1/(1+w)=1-w+w^2-w^3+\cdots\),

\[
\boxed{\frac1z=1-(z-1)+(z-1)^2-(z-1)^3+\cdots}
\]

The region of convergence is \(\boxed{|z-1|<1}\).

### 18. Solve \(xy'=y+x^2\log x\)

\[
\frac{dy}{dx}-\frac{y}{x}=x\log x.
\]

The integrating factor is

\[
IF=e^{\int-1/x\,dx}=\frac1x.
\]

Therefore,

\[
\frac{d}{dx}\left(\frac yx\right)=\log x.
\]

Integrating,

\[
\frac yx=x\log x-x+C.
\]

Hence,

\[
\boxed{y=x^2\log x-x^2+Cx.}
\]

### 19. State and prove the Cauchy–Riemann equations

Let

\[
f(z)=u(x,y)+iv(x,y)
\]

be differentiable at \(z=x+iy\). The derivative is

\[
f'(z)=\lim_{\Delta z\to0}\frac{\Delta u+i\Delta v}{\Delta x+i\Delta y}.
\]

Taking the limit along the real direction (\(\Delta y=0\)) gives

\[
f'(z)=u_x+iv_x.
\]

Taking the limit along the imaginary direction (\(\Delta x=0\)) gives

\[
f'(z)=v_y-iu_y.
\]

Equating real and imaginary parts,

\[
\boxed{u_x=v_y,\qquad u_y=-v_x.}
\]

These are the Cauchy–Riemann equations. They are necessary for complex differentiability when the relevant partial derivatives exist.

### 20. Fourier integral representation

\[
f(x)=
\begin{cases}
1,&-1\le x\le1,\\
0,&\text{otherwise}.
\end{cases}
\]

The function is even, so its Fourier integral contains only cosine terms:

\[
f(x)=\frac{2}{\pi}\int_0^\infty
\left[\int_0^1\cos(st)\,dt\right]\cos(sx)\,ds.
\]

Since

\[
\int_0^1\cos(st)\,dt=\frac{\sin s}{s},
\]

we get

\[
\boxed{f(x)=\frac{2}{\pi}\int_0^\infty
\frac{\sin s}{s}\cos(sx)\,ds.}
\]

At the jump points \(x=\pm1\), the Fourier integral takes the midpoint value \(1/2\).

---

## Group C

### 21. Solve the first-order differential equation

\[
\frac{dy}{dx}=\frac{2x-y+1}{6x-5y+4}.
\]

Shift the origin to the intersection of \(2x-y+1=0\) and \(6x-5y+4=0\):

\[
X=x+\frac14,\qquad Y=y-\frac12.
\]

Then

\[
\frac{dY}{dX}=\frac{2X-Y}{6X-5Y}.
\]

Put \(Y=vX\). Then \(dY/dX=v+X(dv/dX)\), so

\[
X\frac{dv}{dX}=\frac{(5v-2)(v-1)}{6-5v}.
\]

Separating and integrating,

\[
\int\frac{6-5v}{(5v-2)(v-1)}\,dv=\int\frac{dX}{X}.
\]

\[
-\frac43\ln|5v-2|+\frac13\ln|v-1|
=\ln|X|+C.
\]

Thus the implicit solution is

\[
\boxed{\frac{v-1}{(5v-2)^4}=CX^3,\quad
v=\frac{Y}{X},\quad X=x+\frac14,\quad Y=y-\frac12.}
\]

The straight-line solutions lost during separation are \(v=1\) and \(v=2/5\), i.e. \(Y=X\) and \(5Y=2X\).

### 22. Solve \(y''+2y'+y=2x+x^2\)

Auxiliary equation:

\[
m^2+2m+1=0\Rightarrow(m+1)^2=0.
\]

\[
CF=(C_1+C_2x)e^{-x}.
\]

For a polynomial particular solution, take \(y_p=ax^2+bx+c\). Substitution gives

\[
a x^2+(4a+b)x+(2a+2b+c)=x^2+2x.
\]

Comparing coefficients: \(a=1\), \(b=-2\), \(c=2\).

Therefore,

\[
\boxed{y=(C_1+C_2x)e^{-x}+x^2-2x+2.}
\]

### 23. Fourier sine series of \(x^2\) on \((0,3)\)

For \(0<x<L\), where \(L=3\),

\[
x^2=\sum_{n=1}^{\infty}b_n\sin\frac{n\pi x}{3},
\]

where

\[
b_n=\frac{2}{3}\int_0^3x^2\sin\frac{n\pi x}{3}\,dx.
\]

Integrating by parts twice,

\[
b_n=\frac{18(-1)^{n+1}}{n\pi}
+\frac{36\big((-1)^n-1\big)}{n^3\pi^3}.
\]

Hence,

\[
\boxed{x^2=\sum_{n=1}^{\infty}
\left[\frac{18(-1)^{n+1}}{n\pi}
+\frac{36\big((-1)^n-1\big)}{n^3\pi^3}\right]
\sin\frac{n\pi x}{3},\quad 0<x<3.}
\]

### 24. Find the analytic function

Given the real part

\[
u=e^x(x\cos y-y\sin y).
\]

Notice that

\[
ze^z=(x+iy)e^{x+iy}.
\]

Expanding,

\[
ze^z=e^x(x+iy)(\cos y+i\sin y).
\]

Its real part is exactly

\[
e^x(x\cos y-y\sin y).
\]

Therefore,

\[
\boxed{f(z)=ze^z+iC,\quad C\in\mathbb R.}
\]

### 25. Find the residues

\[
f(z)=\frac{z}{(z-1)(z-2)^2}.
\]

At the simple pole \(z=1\),

\[
\operatorname{Res}(f,1)
=\lim_{z\to1}(z-1)f(z)
=\left.\frac{z}{(z-2)^2}\right|_{z=1}
=\boxed{1}.
\]

At the double pole \(z=2\),

\[
\operatorname{Res}(f,2)
=\left.\frac{d}{dz}\left[(z-2)^2f(z)\right]\right|_{z=2}
=\left.\frac{d}{dz}\left(\frac{z}{z-1}\right)\right|_{z=2}
=\boxed{-1}.
\]

---

## Important transcription checks

Before relying on the solutions, compare these items with the original 2024 paper:

- **Group A, Q2:** The supplied integral has inconsistent variables and limits.
- **Group B, Q14:** The function's definition on the full period is incomplete or ambiguous.
- **Group A marks:** The supplied question text lists 10 questions, but only questions 1–10 are present here; confirm the original scan and numbering.

