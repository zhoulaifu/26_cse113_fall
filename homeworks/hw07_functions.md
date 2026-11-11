# Homework07: Functions

## Exercise 1 (50 points)

For each of the following functions, determine whether it is injective (one-to-one) and whether it is surjective (onto). Justify each answer: provide a proof when a property holds, or a counterexample when it does not.

1. $f: \mathbb{R} \to [-1, 1]$, defined by $f(x) = \sin(x)$.
2. $f: \mathbb{R} \to \mathbb{R}$, defined by $f(x) = \sin(x)$.
3. $f: \mathbb{Z} \to \mathbb{Z}$, defined by $f(n) = 2n + 1$.
4. $f: \mathbb{Z} \to \mathbb{Z} \times \mathbb{Z}$, defined by $f(n) = (2n, n + 3)$.
5. $f: \mathbb{Z} \times \mathbb{Z} \to \mathbb{Z}$, defined by $f(m, n) = 2n - 4m$.
6. $f: \mathbb{Z} \times \mathbb{Z} \to \mathbb{Z}$, defined by $f(m, n) = 3n - 4m$.

## Exercise 2 (20 points)

Consider the function $f: \mathbb{R} \to \mathbb{R}$ defined by $f(x) = 2x^3 + 3$.

Determine whether $f$ has an inverse function. Justify your answer. If an inverse exists, give an explicit formula for $f^{-1}$ and verify that it is the inverse of $f$.

## Exercise 3 (30 points)

1. Consider the function $f: \mathbb{R}^2 \to \mathbb{R}^2$ defined by $f(x, y) = (xy, x^3)$. Find $f \circ f$ explicitly.

   For example, if $f: \mathbb{Z} \to \mathbb{Z}$ is defined by $f(n) = n^3$, then $f \circ f: \mathbb{Z} \to \mathbb{Z}$ is defined by $(f \circ f)(n) = n^9$.

2. Consider the functions $f, g: \mathbb{Z} \times \mathbb{Z} \to \mathbb{Z} \times \mathbb{Z}$ defined by $f(m, n) = (mn, m^2)$ and $g(m, n) = (m + 1, m + n)$. Find $g \circ f$ and $f \circ g$.

**Hint:** By definition, $(f \circ g)(a) = f(g(a))$. Here, $a$ can be an ordered pair, as in this exercise.
