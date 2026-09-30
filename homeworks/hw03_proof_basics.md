# Homework03: Proof Basics

## Exercise 1 (5 points)

An integer is a perfect square if it can be expressed as the square of another integer. For example, $81$ is a perfect square, while $80$ is not.

Prove that there exists a perfect square that can be written as the sum of two other perfect squares.

## Exercise 2 (30 points)

For each statement below, determine whether it is true or false. If you believe the statement is true, provide a formal proof. If you believe the statement is false, negate the statement and prove that the negated version is true.

1. For any rational number $r$ and irrational number $ir$, $\frac{r}{ir}$ is irrational.
2. For any two irrational numbers $ir_1$ and $ir_2$, their product $ir_1 \times ir_2$ is irrational.
3. The sum of any two positive irrational numbers is irrational.
4. The square root of any rational number is irrational.

Example: Consider the statement “For any two odd numbers $m_1$ and $m_2$, $\frac{m_1 + m_2}{2}$ is odd.” This is false. The negated statement would be: “There exist two odd numbers $m_1$ and $m_2$ such that $\frac{m_1 + m_2}{2}$ is even.” To prove this negated statement, you could write:

> **Proof.** Let $m_1 = 7$ and $m_2 = 9$; both are odd. Then $\frac{7+9}{2} = 8$, which is even. **QED.**

## Exercise 3 (5 points)

Below is a proof of a mathematical statement. For each numbered line, indicate whether it is a proof target, an assumption, or a fact.

**Proof.**

1. We want to prove: for any even number $m$ and integer $n$, $m \times n$ is even.
2. Assume $m$ is even and $n$ is an integer.
3. $m = 2 \times k$ for some integer $k$.
4. $m \times n = 2 \times k \times n$.
5. Therefore, $m \times n$ is even.

**QED.**

## Exercise 4 (10 points)

Suppose $x$ is a real number.

1. Use direct proof to prove that if $x^3 - x > 0$, then $x > -1$.
2. Use proof by contraposition to prove the same statement.

## Exercise 5 (15 points)

Prove that if $n$ is odd, then $8 \mid (n^2 - 1)$.

**Hint:** Use direct proof.

## Exercise 6 (15 points)

Prove the following using the proof by contradiction strategy:

There is no smallest integer.

## Exercise 7 (20 points)

The [quotient-remainder theorem](https://www.khanacademy.org/computing/computer-science/cryptography/modarithmetic/a/the-quotient-remainder-theorem) says:

> Given any integer $A$ and a positive integer $B$, there exist unique integers $Q$ and $R$ such that $A = B \times Q + R$, where $0 \le R < B$.

Examples:

- $A = 7$, $B = 2$: $7 = 2 \times 3 + 1$
- $A = 8$, $B = 4$: $8 = 4 \times 2 + 0$
- $A = 13$, $B = 5$: $13 = 5 \times 2 + 3$
- $A = -16$, $B = 26$: $-16 = 26 \times (-1) + 10$

From the quotient-remainder theorem, we know that any integer divided by a positive integer will have a fixed number of possible remainders and thus a fixed number of representations. For example, any integer divided by $4$ will produce a remainder between $0$ and $3$, inclusive. Therefore, every integer $n$ can be represented in one of the four forms $4q$, $4q + 1$, $4q + 2$, or $4q + 3$, where $q$ is an integer. Similarly, any integer divided by $3$ will produce a remainder between $0$ and $2$, inclusive.

Now prove the following proposition:

- The product of any four consecutive integers is a multiple of $8$.

**Hint:** Perhaps you can use the quotient-remainder theorem when applying a proof by cases. You can also prove the proposition without it.
