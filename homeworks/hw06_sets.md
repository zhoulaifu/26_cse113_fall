# Homework06: Sets

## Exercise 1 (30 points)

1. How many elements are there in the power set of $\lbrace 1, 2, 3, 42 \rbrace$? Your answer must be an integer.

2. Let $A = \lbrace 1, 2, 3 \rbrace$, $B = \lbrace x, y \rbrace$, and $C = \lbrace \text{hello}, \text{world} \rbrace$. How many elements are there in $A \times B \times C$? Your answer must be an integer.

3. Which of the following statements is correct? **Choose a single correct answer.** Here, $\mathbb{Z}$ denotes the set of integers.

   - (a) $\lbrace 0 \rbrace = \emptyset$.
   - (b) $\lbrace 1 \rbrace \subseteq \mathbb{Z}$.
   - (c) $\lbrace 2n - 2 \mid n \in \mathbb{Z} \rbrace = \mathbb{Z}$.
   - (d) $\lbrace 5n + 6m \mid n, m \in \mathbb{Z} \rbrace \ne \mathbb{Z}$.

4. Let $\mathbb{N} = \lbrace 1, 2, \ldots \rbrace$ denote the set of positive integers. For each $n \in \mathbb{N}$, let $A_n = \lbrace -2n, 0, 2n \rbrace$. Determine the following sets:

   - (a) $\displaystyle \bigcup_{i \in \mathbb{N}} A_i$
   - (b) $\displaystyle \bigcap_{i \in \mathbb{N}} A_i$

## Exercise 2 (30 points)

Use set identities to prove the following properties, clearly stating which law you apply at each step. All complements are taken relative to a fixed universal set $U$, with $A, B \subseteq U$.

You may use the following format:

```text
LHS = ...  (by the name of a set identity)
    = ...  (by the name of a set identity)
    = RHS
```

1. $B \cup (\emptyset \cap A) = B$
2. $(A \cap B) \cup (A \cap B^c) = A$
3. $(A \cap B) \cup (A \cup B^c)^c = B$
4. $A \cap (A \cup B) = A$

## Exercise 3 (20 points)

Let $A$, $B$, and $C$ be sets. Use an element argument to prove that

$$
A - (B \cap C) = (A - B) \cup (A - C).
$$

Show that each side is a subset of the other by considering an arbitrary element.

## Exercise 4 (20 points)

Let $A$, $B$, and $C$ be sets such that

$$
A \cup B = A \cup C \qquad \text{and} \qquad A \cap B = A \cap C.
$$

Use an element argument to prove that $B = C$.
