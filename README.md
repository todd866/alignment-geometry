# Alignment Probabilities on Product Statistical Manifolds

**Fisher Information and Coordination Depth**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

For $M$ independent von Mises random variables, the probability that all phases fall within tolerance $\varepsilon$ of each other scales as:

$$P(\text{alignment}) = p_1(\varepsilon, \kappa)^{M-1}$$

**The exponent is $(M-1)$, not $M$.** This arises from quotient geometry: alignment is invariant under global rotation, so one phase serves as reference, leaving $M-1$ independent constraints.

## Key Results

1. **Main Theorem**: The $(M-1)$ exponent equals the codimension of the alignment constraint after quotienting $T^M$ by the diagonal $S^1$ action

2. **Hitting Time Scaling**: Expected waiting time scales as $\tau \propto p_1^{-(M-1)}$, exponential in coordination depth

3. **Weak Coupling Extension**: Inter-module coupling yields effective exponent $\alpha(M-1)$ where $\alpha \in (0,1]$ captures correlation-induced dimension reduction

4. **Fisher Information Connection**: Window probability $p_1(\varepsilon, \kappa)$ characterized via von Mises concentration and Fisher information geometry

## Paper Structure (15 pages)

1. **Introduction** - Alignment problem, main results preview
2. **Von Mises Family** - Fisher information on the circle, explicit $p_1$ computation
3. **Product Manifolds** - $M$-torus, quotient geometry, codimension argument
4. **Main Result** - Theorem (M-1), Corollary (hitting times)
5. **Fisher Information Characterization** - Connection to statistical distinguishability
6. **Beyond Independence** - Weak coupling, Kuramoto model, $\alpha$ parameter
7. **Numerical Validation** - Simulated modular networks
8. **Worked Examples** - Three parameter regimes with explicit calculations
9. **Discussion** - Companion work, limitations, extensions

## Companion Paper

This paper provides the mathematical foundation for:

**[Coherence Time in Neural Oscillator Assemblies](https://github.com/todd866/coherence-time-biosystems)** (under review at BioSystems)

| This Paper (Information Geometry) | Companion (BioSystems) |
|-----------------------------------|------------------------|
| Geometric derivation of $(M-1)$ | Neural applications |
| Exact product-manifold result | Empirical validation |
| $\alpha$ from weak coupling theory | $\alpha$ fitted from data |
| Coordinate-invariant framework | Cognitive predictions |

## Target Journal

**Information Geometry** (Springer)

## Building

```bash
pdflatex alignment_geometry.tex
```

## Files

```
├── alignment_geometry.tex    # Main manuscript (15 pages)
├── alignment_geometry.pdf    # Compiled
├── cover_letter.tex          # Submission cover letter
├── cover_letter.pdf          # Compiled
└── README.md
```

## Citation

```bibtex
@article{todd2025alignment,
  title={Alignment Probabilities on Product Statistical Manifolds:
         Fisher Information and Coordination Depth},
  author={Todd, Ian},
  journal={Information Geometry},
  year={2025},
  note={In preparation}
}
```

## Author

Ian Todd
Sydney Medical School, University of Sydney
itod2305@uni.sydney.edu.au
ORCID: [0009-0002-6994-0917](https://orcid.org/0009-0002-6994-0917)

## License

MIT License
