# Dichotomy Method (Interval Halving)

This method finds the minimum by repeatedly reducing the interval.

---

## Theoretical Breakdown

- Choose two points near midpoint:

\[
x_1 = \frac{a+b}{2} - \varepsilon, \quad
x_2 = \frac{a+b}{2} + \varepsilon
\]

- If:
  - \( f(x_1) < f(x_2) \) → new interval \([a, x_2]\)
  - else → \([x_1, b]\)

- Repeat until:
\[
|b - a| < \delta
\]
