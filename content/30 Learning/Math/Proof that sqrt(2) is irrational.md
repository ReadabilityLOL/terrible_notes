#math #proof


This is a [[proof by contradiction]], so we'll assume first that $\sqrt{2}$ is rational, and then move on from there.

If $\sqrt{2}$ is irrational, it can be expressed as a fraction, with an integer numerator and denominator. Let's call this $\frac{a}{b}$, where $\frac{a}{b}$ is in lowest terms (This will be important later).

Now, since $\frac{a}{b} = \sqrt{2}$, 

$\frac{a^2}{b^2} = 2$, and 

$a^2 = 2b^2$

Since both $a$ and $b$ are integers, $a^2$ must be an even number, and [[Proof that if a prime number divides x^2, it must divide x|thus a must be even too]].

Because $a$ is even, it can be written as $2c$ instead, where $c = \frac{a}{2}$.

Substituting it back into $a^2 = 2b^2$, we get 

$(2c)^2 = 2b^2$, or

$4c^2 = 2b^2$, which can be simplified into 

$2c^2 = b^2$.

As $c$ and $b$ are integers, $b^2$ is even, and thus $b$ must also be even.

This means $b$ and $a$ are both even, which means they are both divisible by 2. 

As they share a common factor, this contradicts the previously stated fact that they were in lowest terms, causing a contradiction.

Thus, $\sqrt{2} \ne \frac{a}{b}$, where $a,b \in \mathbb{R}$.

$\sqrt{2}$ is thus irrational $\blacksquare$


