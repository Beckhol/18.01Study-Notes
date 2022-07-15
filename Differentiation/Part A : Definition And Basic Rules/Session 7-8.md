# Session 7-8

## Outline



## Derivative of $sin x$ , Algebraic Proof

We'll now compute a specific formula for the derivative of the function $sinx$

​	$\frac{d}{dx} sinx = \lim \Delta x \to 0 \frac{sin(x+\Delta x)-sin(x)}{\Delta x}$

Angle sum formula:

$sin(a+b) = sin(a)cos(b) + sin(b)cos(a)$

This let us untangle the x from the $\Delta x$ as follows:

$\frac{d}{dx} sinx = \lim \Delta x \to 0 \frac{sinxcos \Delta x + cosx sin \Delta x}{\Delta x}$

Simplify this expression:

$\frac{d}{dx} sinx = \lim \Delta x \to 0  sinx(\frac{cos \Delta x -1}{\Delta x})+\lim \Delta x \to 0  cosx(\frac{sin \Delta x}{\Delta x})$

Cause we proved that :

$\lim \Delta x \to 0 \frac{cos \Delta x-1}{\Delta x} = 0$

$\lim \Delta x \to 0 \frac{sin \Delta x}{\Delta x} = 1$

The expression simplifies to $sinx \times 0 + cosx \times1 = cosx$

Conclude that : $\frac{d}{dx} sinx = cosx$

## Derivative of $cosx$ 

similar to $sinx$

$\frac{d}{dx} cosx = -sinx$

## Limits of $sinx$

<img src="/Users/beckhol/Library/Application Support/typora-user-images/image-20220715173336255.png" alt="image-20220715173336255" style="zoom:67%;" />

<img src="/Users/beckhol/Library/Application Support/typora-user-images/image-20220715173346277.png" alt="image-20220715173346277" style="zoom:67%;" />

$\lim x \to 0 \frac{sin(x)}{x} = 1$

When the angle becomes smaller and smaller, the arc length is closer and closer to the straight line.

## Limits of $(1-cos(x)/x)$

<img src="/Users/beckhol/Library/Application Support/typora-user-images/image-20220715173635582.png" alt="image-20220715173635582" style="zoom:67%;" />

<img src="/Users/beckhol/Library/Application Support/typora-user-images/image-20220715173651794.png" alt="image-20220715173651794" style="zoom:67%;" />

$\lim \theta \to 0 \frac{1-cosx}{\theta} = 0$

When the angle becomes smaller and smaller, $\theta$ becomes very small and $1-cosx$ is much smaller than $\theta$ , so the result is 0.