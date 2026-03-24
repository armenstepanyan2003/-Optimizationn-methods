# Golden Section Method

An efficient optimization method using the golden ratio.

---

## Theoretical Breakdown

Golden ratio:

\[
\varphi = 1.618
\]

Points:

\[
x_1 = b - \frac{b-a}{\varphi}, \quad
x_2 = a + \frac{b-a}{\varphi}
\]

Update:

- If \( f(x_1) < f(x_2) \) → \( b = x_2 \)
- Else → \( a = x_1 \)
