# Session 1-2

## What is a derivative?

- geometric interpretation
- physical interpretation
- Importance of derivatives to **all** measurements

## How to differentiate anything?

$\frac{dy}{dx} e^{xtanx} =?$

## Geometric Interpretation

Finding the **tangent line(切线)** to $y = f(x)$  at $P = (x_0,y_0)$

Tangent line = limit of secant line PQ as Q -> P(P is fixed)

> <img src="image-20220713170138936.png" alt="image-20220713170138936" style="zoom:80%;" />
>
> $y - y_0 = m (x - x_0)$ ; 
>
> Point $y_0= f(x_0)$ 
>
> slope $m = f'(x_0)$  $= \lim_{\Delta x \to 0} \frac{\Delta f}{\Delta x}$, $\Delta x = x - x_0$, $\Delta y = \Delta f = y - y_0$
>
> Definition: $f'(x_0)$ , the derivative of f at $x_0$ , is the **slope(斜率)** of the tangent line to $y = f(x)$ at P.
>
> $f'(x_0) = \lim \Delta x \to 0 \frac{f(x_0+\Delta x)-f(x_0)}{\Delta x}$
>
> [^Tangent Line]: 过圆上一点且垂直与该点半径的直线被称为切线。
> [^Secant Line]: 是指与曲线至少交于两相异点的直线。当这两个点不断靠近，并重合为一个点时，这条直线就变成了这条曲线的切线.

### Example 1

$f(x) = \frac{1}{x}$ 

<img src="image-20220713173034781.png" alt="image-20220713173034781" style="zoom:80%;" />
$$
\begin{align}
\frac{\Delta f}{\Delta x} &= \frac{f(x_0+\Delta x)-f(x_0)}{\Delta x}
                        \\&= \frac {\frac{1}{x_0+\Delta x}-\frac{1}{x_0}}{\Delta x}
                        \\&= \frac {-1}{(x_0 + \Delta x)}
\end{align}
$$
Next, we see what happens to the slopes of the secant lines as $\Delta x$ tends to zero:

$f'(x) = \lim \Delta x \to 0 \frac {\Delta f}{\Delta x} = \lim \Delta x \to 0 \frac{-1}{(x_0)(x_0+\Delta x)} = \frac {-1}{x_0^2} $, so $f'(x) < 0$ means that it is a negative slope

## More Notations

### Example 2

$f(x) = x ^n $ where n = 1,2,3...

What is $\frac{d}{dx} x ^n?$

$Answer = x^n + nx^{n-1} \Delta x + junk$

e.g: $\frac{d}{dx}(x^3+5x^{10}) = 3x^2 + 50x^9 $

