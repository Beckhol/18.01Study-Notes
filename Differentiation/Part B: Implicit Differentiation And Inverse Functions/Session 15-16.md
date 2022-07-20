# Session 15-16

## Derivative of the Inverse of a function

One important application of implicit differentiation is to finding derivatives of inverse functions.

A simple example: 

Simply the equation $y = \sqrt{x} (x>0)$ by squaring both sides to gey $y^2 = x$ . We could use function notation here to say that $y = f(x) = \sqrt{x}$ and $ x = g(y) = y^2$ 

In general, we look for functions $y = f(x)$ and $g(y) = x$ for which $g(f(x)) = x$ . If this is the case, then g is the inverse of $f$ (we write $g = f^{-1}$) and $f$ is the inverse of g(we write $f = g^{-1}$) 

## Derivative of $arctan(x)$

$$
\begin{align}
y & = tan^{-1}(x)
\\ tan y &= tan(tan^{-1}x)
\\ tan y &= x
\end{align}
$$

$$
\begin{align}
tany &= x \\
\frac{d}{dx}(tan(y)) &= \frac{d}{dx}(x) \\
(Chain Rule) \frac{d}{dy}(tan(y)) \frac{dy}{dx} &= 1 \\
\frac{1}{cos^2(y)} \frac{dy}{dx} &= 1 \\
\frac{dy}{dx} &= cos^2(y)

\end{align}
$$

<img src="/Users/beckhol/Library/Application Support/typora-user-images/image-20220720143103444.png" alt="image-20220720143103444" style="zoom:67%;" />

In this triangle, $tan(y) = x$ so $y = arctan(x)$ , $h = \sqrt{1+x^2}$

we can compute :  $cos(y) = \frac {1}{\sqrt{1+x^2}}$

From this , we get : $cos^2(y) = (\frac{1}{\sqrt{1+x^2}}) = \frac{1}{1+x^2}$

So: $\frac {dy}{dx} = \frac{1}{1+x^2} $

In other words:  $\frac{d}{dx} arctan(x) = \frac{1}{1+x^2}$

##  Working with exponents

$a^{x_1+x_2} = a^{x_1}a^{x_2}$

$(a^{x_1})^{x_2} = a^{x_1}a^{x_2}$ 

$a^{\frac{p}{q}} = \sqrt[q]{p}$  (p,q are integers)