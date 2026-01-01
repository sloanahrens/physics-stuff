# Math Stuff

Mathematical physics notes with embedded LaTeX.

## Documents

### Mathematical Foundations

| Document | Topic |
|----------|-------|
| [Tensor Calculus](tensor-calculus.md) | Indices, metrics, covariant derivatives, curvature |
| [Differential Forms](differential-forms.md) | Exterior calculus, wedge products, Stokes' theorem |
| [Lie Groups & Algebras](lie-groups.md) | Continuous symmetries, representations, structure constants |

### Classical Mechanics

| Document | Topic |
|----------|-------|
| [Lagrangian Mechanics](lagrangian-mechanics.md) | Principle of least action, Euler-Lagrange equations, Noether's theorem |
| [Hamiltonian Mechanics](hamiltonian-mechanics.md) | Phase space, Poisson brackets, symplectic structure |

### General Relativity

| Document | Topic |
|----------|-------|
| [Natural Units](natural-units.md) | Using and converting $G = c = 1$ and $\hbar = 1$ units |
| [Schwarzschild Solution](schwarzschild-solution.md) | Vacuum solution for non-rotating black holes |
| [Kerr Metric](kerr-metric.md) | Rotating black hole spacetime geometry |
| [Gravitational Waves](gravitational-waves.md) | Linearized gravity, polarizations, LIGO detection |

### Electromagnetism

| Document | Topic |
|----------|-------|
| [Maxwell Covariant](maxwell-covariant.md) | Maxwell's equations in relativistic tensor form |

### Quantum Mechanics

| Document | Topic |
|----------|-------|
| [Quantum Mechanics](quantum-mechanics.md) | Wave functions, uncertainty, entanglement, many-worlds (with explanations) |
| [Quantum Math](quantum-math.md) | Concise version with equations only |

## Document Relationships

```
Tensor Calculus ──┬──► Differential Forms ──► Maxwell Covariant
                  │
                  └──► Gravitational Waves ──► Schwarzschild/Kerr

Lagrangian ──► Hamiltonian ──► Quantum Mechanics ◄── Lie Groups
                    │
                    └──► Poisson Brackets ≈ Commutators
```

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
