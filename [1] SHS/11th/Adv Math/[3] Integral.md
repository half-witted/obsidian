## Definition
An inverse of derivative
$$\int f'(x)\space dx=f(x)+C$$
- Why C is added? $\to \frac{d}{dx}(x^2+5)=\frac{d}{dx}(x^2-10)=2x\to$ constant is always 0 whatever the value is
- <mark style="background:#40a9ff">Make it in plus-minus form first (without any mult, div), then integrate</mark>
## Rules
| <center>Constant</center>                                  | <center>Power</center>                                                 |
| ---------------------------------------------------------- | ---------------------------------------------------------------------- |
| $\int a\space dx=ax+C$                                     | $\int x^n\space dx=\frac{x^{n+1}}{n+1}+C$                              |
| <center>**Constant multiple**</center>                     | <center>Sum and difference</center>                                    |
| $\int ax^n\space dx=a\left( \frac{x^{n+1}}{n+1} \right)+C$ | $\int[f(x)\pm g(x)]\space dx=\int f(x)\space dx\pm \int g(x)\space dx$ |
## Find C
$\frac{d}{dx}=4x,\space y=\int{4}x\space dx=2x^2+C$
- Substitute coor with $y$ and $x$ in the integration (ex: (2,9)) $\to_{9}=2(2)^2+C$
- Calculate $\to C=1$
- Substitute $\to y=2x^2+1$
## Solid of Revolution
A geometric figure formed when a curve is rotated $360^\circ$ about an axis

| <center>Shape</center>                   | <center>Function</center> | <center>Command</center>                                                  | <center>Info</center>                                                               | <center>Surface</center>      |
| ---------------------------------------- | ------------------------- | ------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- | ----------------------------- |
| Cylinder (flat line)                     | $f(x)=r$                  | ```f(x) = If(x_1 <= x <= x_2, r)```                                       | $x_{1}=$ graph starting point<br>$x_{2}=$ graph ending point<br>$\pm x=$ move graph | ```Surface(f(x), a, xAxis)``` |
| Cone (slash, $r$ and $h$ are changeable) | $g(x)=\frac{r}{h}x$       | ```g(x) = If(x_1 <= x <= x_2, (r/h) * x)```                               | same as above                                                                       | ```Surface(g(x), a, xAxis)``` |
| Sphere (semi-circle)                     | $h(x)=\sqrt{ R^2-x^2 }$   | ```h(x) = If(x_1 <= x <= x_2, sqrt(R^2 - (x - circular center)^2))<br>``` | same as above                                                                       | ```Surface(h(x), a, xAxis)``` |
## Volume of Solid
$V=\pi \int_{x_1}^{x_2}[f(x)]^2\space dx$

| <center>Shape</center> | <center>Function</center> | <center>Command</center>                        | <center>Info</center>                                                                        |
| ---------------------- | ------------------------- | ----------------------------------------------- | -------------------------------------------------------------------------------------------- |
| Cylinder               | $f(x)=r$                  | ```pi * IntegralBetween(f(x)^2, 0, x_1, x_2)``` | $x_{1}=$ graph starting point<br>$x_{2}=$ graph ending point, total height/long if $x_{1}=0$ |
| Cone                   | $g(x)=\frac{r}{h}x$       | ```pi * IntegralBetween(g(x)^2, 0, x_1, x_2)``` | same as above                                                                                |
| Sphere                 | $h(x)=\sqrt{ R^2-x^2 }$   | ```pi * IntegralBetween(h(x)^2, 0, x_1, x_2)``` | same as above                                                                                |
## Exercises