# Session 17-18

## Definition of $e$

$\frac{d}{dx}e^x = e^x$

## Natural Log(inverse function of $e^x$)

If $y = e^x$ then, $ln(y) = x$

or if $w = ln(x)$ , then $e^w = x$

Properties of this function:

$ln(x_1x_2) = lnx_1 + lnx_2$

$ln1 = 0$

$lne = 1$

## Implicit Differentiation of $lnx$

$w = ln(x)$

$\frac{dw}{dx} = \frac{d}{dx}ln x $

cause we know,  If $y = e^x$ then, $ln(y) = x$

We now use implicit differentiation to take the derivative of both sides of this equation:

$\frac{d}{dx}(e^w) = \frac{d}{dx} x$

$\frac{d}{dw}(e^w)\frac{dw}{dx} = 1$

$(e^w)\frac{dw}{dx} = 1$

$\frac{dw}{dx} = \frac{1}{e^w} = \frac{1}{x} $

## $\frac{d}{dx}a^x,part 2$

**Logarithmic differentiation**

$u = a^x$

$ln u = ln(a^x)$

$lnu = xlna$

This is easy to differentiate because $lna$ is a constant

$ln(u)' = lna$

Since $(lnu)' = u'/u$, $u' = u(lnu)'$ . So $\frac{d}{dx}a^x = a^xlna = (lna)a^x$

## Another example of logarithmic differentiation

Recall to the rule $(lnu)' = u'/u$

Example : $v = x^x$ , find v'

$lnv = ln(x^x) = xlnx$

Use the product rule at the right side : $(lnv)' = lnx + 1$

Cause we know $(lnu)' = u'/u$ , so $v'/v = lnx + 1$

Plugin $x^x = v$ :

$\frac{v'}{x^x} = lnx + 1$

$v' = x^x(1+lnx)$

So, $\frac{d}{dx}x^x = x^x(x+lnx)$

