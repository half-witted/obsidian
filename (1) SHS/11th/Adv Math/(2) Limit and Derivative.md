## Limit
### Definition
- A value that a function approaches to
- Focuses on behaviour near the point, not at the point
- $\lim_{ x \to a }f(x)=L\to$ when $x$ gets closer to $a$, the function's value gets closer to $L$
### Rules
| <center>Constant</center>                           | <center>Identity</center>                                                             | <center>Constant multiple</center>                                          | <center>Sum and difference</center>                                          |
| --------------------------------------------------- | ------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| $\lim_{ x \to a }c=c$                               | $\lim_{ x \to a }x=a$                                                                 | $\lim_{ x \to a }[c*f(x)]=c*\lim_{ x \to a }f(x)$                           | $\lim_{ x \to a }[f(x)\pm g(x)]=\lim_{ x \to a }f(x)\pm\lim_{ x \to a }g(x)$ |
| <center>**Power**</center>                          | <center>**Quotient**</center>                                                         | <center>**Product**</center>                                                |                                                                              |
| $\lim_{ x \to a }[f(x)]^n=[\lim_{ x \to a }f(x)]^n$ | $\lim_{ x \to a }\frac{f(x)}{g(x)}=\frac{\lim_{ x \to a }f(x)}{\lim_{ x \to a }g(x)}$ | $\lim_{ x \to a }[f(x)*g(x)]=[\lim_{ a \to x }f(x)]*[\lim_{ x \to a }g(x)]$ |                                                                              |
### Value
#### Steps
- Substitute the value of $x$
- Calculate using algebraic operations
- Determine the value
#### Results
1. Determinate
   If the value is a real number (ex: $2, \frac{3}{6}, 0.67$)
2. Indeterminate
	- If the value is either $\frac{0}{0}$ or $\frac{\infty}{\infty}$, [[#L'Hopital Rule]]
	- If the value is $\frac{a}{0}$, limit doesn't exist (DNE)
### L'Hopital Rule
Used if the value is either $\frac{0}{0}$ or $\frac{\infty}{\infty}$

| <center>Function</center> | <center>L'Hopital</center> |
| ------------------------- | -------------------------- |
| Constant                  | 0                          |
| $x^n$                     | $nx^{n-1}$                 |
| $ax^n$                    | $anx^{n-1}$                |
### Continuous Function (Strictly Continuous)
A function is considered continuous only if (all must be fulfilled):
- Function must be defined $\to f(a)$
- Left limit and right must be the same ($-:$ from left, otherwise) $\to \lim_{ x \to a^- }f(x)=\lim_{ x \to a^+ }f(x)$
- Limit's value must be the same with function's $\to \lim_{ x \to a }f(x)=f(a)$
### Dots
- Function value
	- Solid dot (floating or attached to a line)
	- Continuous line (no hollow dot)
- Limit value
	- Hollow dot (floating or attached to a line)
	- Solid dot (attached to a line)
	- Continuous line (with or without solid dot attached)
## Derivative
### Definition
Shows rate of changes of a function
$$f'(x), \frac{dy}{dx}$$
### Rules
| <center>Constant</center>             | <center>Power</center>                 | <center>Product</center>                     | <center>Quotient</center>                                                             |
| ------------------------------------- | -------------------------------------- | -------------------------------------------- | ------------------------------------------------------------------------------------- |
| $\frac{d}{dx}[c]=0$                   | $\frac{d}{dx}x^n=nx^{n-1}$             | $\frac{d}{dx}[f(x)g(x)]=f'(x)g(x)+f(x)g'(x)$ | $\frac{d}{dx}\left[ \frac{f(x)}{g(x)} \right]=\frac{{f'(x)g(x)-f(x)g'(x)}}{[g(x)]^2}$ |
| <center>**Chain**</center>            | <center>**Constant multiple**</center> | <center>**Sum and Difference**</center>      |                                                                                       |
| $\frac{d}{dx}[f(g(x))]=f'(g(x))g'(x)$ | $\frac{d}{dx}[f(x)*c]=f'(x)*c$         | $\frac{d}{dx}[f(x)\pm g(x)]=f'(x)\pm g'(x)$  |                                                                                       |
## Exercises