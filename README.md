# Math Stuff

Mathematical physics notes with embedded LaTeX.

## Documents

| Document | Topic |
|----------|-------|
| [Schwarzschild Solution](schwarzschild-solution.md) | Vacuum solution for non-rotating black holes |
| [Kerr Metric](kerr-metric.md) | Rotating black hole spacetime geometry |
| [Maxwell Covariant](maxwell-covariant.md) | Maxwell's equations in relativistic tensor form |
| [Natural Units](natural-units.md) | Using and converting $G = c = 1$ units |
| [Quantum Mechanics](quantum-mechanics.md) | Wave functions, uncertainty, entanglement, many-worlds |
| [Quantum Mechanics (Extended)](quantum-mechanics-extended.md) | Same content with physical explanations for each equation |

## LaTeX Rendering

These documents use LaTeX for mathematical notation. To view rendered equations:

- **VS Code**: Use Markdown preview (`Cmd+Shift+V`) with a math-supporting extension
- **GitHub**: Renders LaTeX natively in markdown files

### Examples

Inline math: $E = mc^2$

Block math (Schwarzschild metric):

$$
ds^2 = -\left(1 - \frac{2M}{r}\right) dt^2 + \left(1 - \frac{2M}{r}\right)^{-1} dr^2 + r^2 d\Omega^2
$$

Matrix (Minkowski metric):

```math
g_{\mu\nu} = \begin{pmatrix} -1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & r^2 & 0 \\ 0 & 0 & 0 & r^2\sin^2\theta \end{pmatrix}
```
