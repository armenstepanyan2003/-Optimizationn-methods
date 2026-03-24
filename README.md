Method of Alternatives (Uniform Search)

This implementation demonstrates the Uniform Search Method for finding the minimum of a unimodal function.

---

Theoretical Breakdown

The method divides the interval \([a, b]\) into equal segments and evaluates the function at each point.

- **Objective:** Find the minimum of \( f(x) \)
- **Grid Construction:** Divide interval into \( n \) parts
- **Step size:**
  \[
  h = \frac{b - a}{n}
  \]
- **Points:**
  \[
  x_k = a + k \cdot h
  \]
- **Selection:**
  \[
  f(x^*) = \min f(x_k)
  \]

- **Error:**
  \[
  \varepsilon = \frac{b - a}{n}
  \]

