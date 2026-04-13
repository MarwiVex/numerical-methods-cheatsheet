# Numerical Methods Cheatsheet

This directory contains the English version of the cheatsheet, designed in LaTeX. It serves as an ideal reference material for students, engineers, and researchers in scientific computing. The document covers everything from fundamental computer arithmetic to advanced techniques for solving Ordinary and Partial Differential Equations.

---

## Core Content

* **Fundamentals:** Computer arithmetic (IEEE 754), machine epsilon, error types (absolute, relative, truncation, round-off), and matrix conditioning.
* **Root Finding & Optimization:** Bracketing methods (Bisection, Regula Falsi), open methods (Newton-Raphson, Secant), and the industry-standard Brent's method.
* **Matrix Algebra & Linear Systems:** Direct factorizations (LU, Cholesky, SVD) and iterative methods such as Jacobi, Gauss-Seidel, and Conjugate Gradient.
* **Quadrature & Interpolation:** Lagrange and Newton polynomials, cubic splines, numerical differentiation (Richardson extrapolation), and integration rules (Trapezoidal, Simpson's, Gaussian Quadrature).
* **Differential Equations:** ODE Initial Value Problems (Euler, RK4), stability analysis, and finite difference schemes for Elliptic, Parabolic, and Hyperbolic PDEs.

---

## Usage and Compilation

If you wish to build the PDF document directly from the source code (`numerical_methods_cheatsheet.tex`), you can use your preferred LaTeX environment or run the following command in your terminal using `pdflatex`:

```bash
pdflatex numerical_methods_cheatsheet.tex
```

*Note: Depending on your setup, you may need to compile the document twice to ensure all cross-references and formatting are generated correctly.*

---

## Credits

Material compiled and designed by **Roberto León Landeros**.

## License

This work is distributed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.
