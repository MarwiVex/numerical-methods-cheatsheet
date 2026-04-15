# Formulario de Métodos Numéricos

Este directorio contiene la versión en español del formulario, diseñado en LaTeX. Es un material de referencia ideal para estudiantes, ingenieros e investigadores en el área del cálculo científico. El documento abarca desde la aritmética computacional fundamental hasta técnicas avanzadas para la resolución de Ecuaciones Diferenciales Ordinarias y Parciales.

---

## Contenido Principal

* **Fundamentos:** Aritmética computacional (IEEE 754), épsilon de máquina, tipos de error (absoluto, relativo, truncamiento, redondeo) y condicionamiento de matrices.
* **Búsqueda de Raíces y Optimización:** Métodos cerrados (Bisección, Regula Falsi), métodos abiertos (Newton-Raphson, Secante) y el estándar industrial del método de Brent.
* **Álgebra Matricial y Sistemas Lineales:** Factorizaciones directas (LU, Cholesky, SVD) y métodos iterativos como Jacobi, Gauss-Seidel y Gradiente Conjugado.
* **Cuadratura e Interpolación:** Polinomios de Lagrange y Newton, trazadores cúbicos (splines), diferenciación numérica (extrapolación de Richardson) y reglas de integración (Trapezoidal, Simpson, Cuadratura Gaussiana).
* **Ecuaciones Diferenciales:** Problemas de valor inicial en EDOs (Euler, RK4), análisis de estabilidad y esquemas de diferencias finitas para EDPs elípticas, parabólicas e hiperbólicas.

---

## Uso y Compilación

Si deseas compilar el documento PDF directamente desde el código fuente (`metodos_numericos_formulario.tex`), puedes utilizar tu entorno LaTeX preferido o ejecutar el siguiente comando en la terminal usando `pdflatex`:

```bash
`pdflatex metodos_numericos_formulario.tex`
```

*Note: Dependiendo de tu configuración, es posible que necesites compilar el documento un par de veces para que las referencias internas y el formato se ajusten correctamente.*

---

## Créditos

Material compilado y diseñado por **Roberto León Landeros**.

## Licencia

This work is distributed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0).
