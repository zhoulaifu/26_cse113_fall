# Homework01: Validity of Logic Arguments

## Exercise 1 (30 points)

Use truth tables to determine whether the following arguments are valid. Provide an explanation based on the truth table.

1. **Premises:** $p \to q$ and $\neg p \to \neg q$.

   **Conclusion:** $p \vee q$.

2. **Premises:** $p \vee q$, $p \to \neg q$, and $\neg r \to \neg p$.

   **Conclusion:** $r$.

3. **Premises:** $p$, $\neg q \to \neg p$, and $\neg q \vee r$.

   **Conclusion:** $r$.

4. **Premises:** $p \land q \to \neg r$, $p \vee \neg q$, and $\neg q \to p$.

   **Conclusion:** $\neg r$.

5. **Premises:** $p \to r$ and $q \to r$.

   **Conclusion:** $(p \vee q) \to r$.

6. **Premises:** $p \to (q \vee r)$ and $\neg q \vee \neg r$.

   **Conclusion:** $\neg p \vee \neg r$.

## Exercise 2 (50 points)

For each argument below, determine whether it is valid. If it is valid, write *Valid* and name the inference rule. If it is invalid, write *Invalid*; no explanation is required.

### A

1. If Jane has a cat, then Jane has a pet.
2. Jane has a cat.
3. Therefore, Jane has a pet.

### B

1. If Jane has a cat, then Jane has a pet.
2. Jane has a pet.
3. Therefore, Jane has a cat.

### C

1. If Jane has a cat, then Jane has a pet.
2. It is not the case that Jane has a pet.
3. Therefore, it is not the case that Jane has a cat.

### D

1. If Jane has a cat, then Jane has a pet.
2. It is not the case that Jane has a cat.
3. Therefore, it is not the case that Jane has a pet.

### E

1. If pigs fly, then hell has frozen over.
2. Pigs fly.
3. Therefore, hell has frozen over.

### F

1. I like chocolates.
2. Therefore, we like chocolates.

### G

1. If the professor is sick, the class will be canceled.
2. If the class is canceled, the students will be happy.
3. Therefore, if the professor is sick, the students will be happy.

### H

1. If Rufus is a human being, then Rufus has a right to life.
2. It is not the case that Rufus is a human being.
3. Therefore, it is not the case that Rufus has a right to life.

### I

1. Amy joins the Army, or Mary joins the Marines.
2. It is not the case that Mary joins the Marines.
3. Therefore, Amy joins the Army.

### J

1. I like Bulgogi.
2. Therefore, I like Bibimbap and Bulgogi.

## Exercise 3 (20 points)

Use inference rules to show that the following argument is valid. You may provide a list of statements in the following form: From “...,” we have “...” by the inference rule “...”.

For example: From premises $p$ and $p \to q$, we have $q$ by the inference rule Modus Ponens.

**Premises**

- $p \vee q$
- $q \to r$
- $p \land s \to t$
- $\neg r$
- $\neg q \to (u \land s)$

**Conclusion**

- $t$
