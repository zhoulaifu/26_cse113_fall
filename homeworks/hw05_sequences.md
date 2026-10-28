# Homework05: Sequences and Mathematical Induction

## Exercise 1 (10 points)

Use mathematical induction to prove that for every integer $n \ge 1$, the expression

$$
3^{2n+2} - 8n - 9
$$

is divisible by $64$.

## Exercise 2 (10 points)

Suppose $p$ is a real number satisfying $p > -1$. Use mathematical induction to prove that for every integer $n \ge 1$,

$$
(1+p)^n \ge 1 + np.
$$

## Exercise 3 (10 points)

The triangle inequality states that for all real numbers $a$ and $b$, $|a+b| \le |a| + |b|$.

Use the triangle inequality and mathematical induction to prove that for every integer $n \ge 1$ and all real numbers $a_1, a_2, \ldots, a_n$,

$$
\left|\sum_{i=1}^{n} a_i\right| \le \sum_{i=1}^{n} |a_i|.
$$

## Exercise 4 (15 points)

Use mathematical induction to prove that for every integer $n \ge 1$,

$$
\sum_{k=1}^{n} k^2 2^k = (n^2 - 2n + 3)2^{n+1} - 6.
$$

## Exercise 5 (10 points)

Use mathematical induction to prove that for every integer $n \ge 4$,

$$
2^n \ge n^2.
$$

## Exercise 6 (10 points)

Consider the recursively defined sequence

$$
a_0 = 2, \qquad a_k = \frac{a_{k-1}}{1 + 2a_{k-1}} \quad \text{for every integer } k \ge 1.
$$

Find an explicit formula for $a_n$ for every integer $n \ge 0$, and prove your formula using mathematical induction.

## Exercise 7 (10 points)

Consider the recursively defined sequence

$$
b_0 = 1, \qquad b_k = 3b_{k-1} + 2 \quad \text{for every integer } k \ge 1.
$$

Find an explicit formula for $b_n$ for every integer $n \ge 0$, and prove your formula using mathematical induction.

## Exercise 8 (25 points)

Consider a $2^n \times 2^n$ board made of unit squares, where $n \ge 1$ is an integer. Exactly one unit square has been removed, and its position may be anywhere on the board.

An L-shaped tile covers three unit squares arranged as a $2 \times 2$ block with one square missing. Tiles may be rotated. A tiling must cover every remaining square exactly once, with no overlaps and no part of a tile outside the board or over the removed square.

The following illustration shows an example board for $n = 2$ and one L-shaped tile. The removed square is marked `X`.

```text
Example 4 x 4 board               One L-shaped tile

+---+---+---+---+                 +---+
| X |   |   |   |                 |   |
+---+---+---+---+                 +---+---+
|   |   |   |   |                 |   |   |
+---+---+---+---+                 +---+---+
|   |   |   |   |
+---+---+---+---+
|   |   |   |   |
+---+---+---+---+
```

1. Describe a recursive procedure that tiles any such board.
2. Use mathematical induction on $n$ to prove that your procedure works for every possible position of the removed square.
3. Let $T(n)$ be the number of tiles used by your procedure. Give a base case and a recurrence for $T(n)$, then find an explicit formula and prove it by induction.

**Hint:** Divide the board into four equal square regions. Consider how placing one tile near the center could let you apply the recursive procedure to all four regions.
