# OQCT - Omnidimensional Quantum-Cosmological Theory

> **Unifying Quantum Field Theory, General Relativity, and Consciousness Physics through Operator Manifolds**

[![Preprint](https://img.shields.io/badge/Preprint-Zenodo-blue?style=flat-square)](https://zenodo.org)
[![arXiv](https://img.shields.io/badge/arXiv-quant--ph-red?style=flat-square)](https://arxiv.org)
[![License](https://img.shields.io/badge/License-CC%20BY%204.0-green?style=flat-square)](https://creativecommons.org/licenses/by/4.0/)
[![MSC](https://img.shields.io/badge/MSC2020-83C45%20%7C%2081T75%20%7C%2046L87%20%7C%2085A40-purple?style=flat-square)](#)

---

## 🌌 Overview

**OQCT** is a theoretical physics framework constructing a 10-dimensional non-commutative operator manifold

$$\mathcal{M}^{10}_{\mathrm{QC}} = \mathbb{R}^{1,3} \times \mathcal{C}^6 \times \mathcal{H}_{\mathrm{quant}}$$

that encodes quantum field dynamics, spacetime curvature, and conscious observation within a single variational principle. From this manifold, the theory derives:

- A covariant **ethical entropy gradient** $\nabla S_{\mathcal{O}}$ governing wavefunction collapse without an explicit measurement postulate
- A **temporal triality operator** $\hat{T}_{\mathrm{tri}}$ whose eigenvalue spectrum yields the arrow of time as an emergent property
- A **conscious inflation potential** reproducing Planck 2018 CMB spectral tilt $n_s = 0.9649 \pm 0.0042$ to within $1\sigma$
- A **black-hole entropy formula** resolving the information paradox via ethical entropy tracking
- **Five falsifiable experimental signatures** for CMB-S4, quantum spectroscopy, and quantum-cognition experiments

---

## 📐 The Master Equation

$$\boxed{|\Psi\rangle = \int_{\mathcal{M}^{10}_{\mathrm{QC}}}
\left[i\hbar\partial_t\Psi
+ \sum_k \hat{a}^\dagger_k\hat{a}_k\otimes\hat{g}_{\mu\nu}
+ \gamma^\mu D^{\mathrm{ethic}}_\mu\psi_{\mathcal{O}}
+ \lambda_\Omega\ln\Omega\right]\sqrt{-G}\;\hat{d}^{10}x = 0}$$

| Term | Physical meaning |
|------|-----------------|
| $i\hbar\partial_t\Psi$ | Quantum temporal evolution (Schrödinger) |
| $\hat{a}^\dagger_k\hat{a}_k\otimes\hat{g}_{\mu\nu}$ | Particle–spacetime entanglement |
| $\gamma^\mu D^{\mathrm{ethic}}_\mu\psi_{\mathcal{O}}$ | Conscious covariant propagation |
| $\lambda_\Omega\ln\Omega$ | Ethical entropy modulation |

---

## 🔬 Key Results

### Extended Born Rule
Wavefunction collapse to eigenstate $|e_k\rangle$ occurs when the ethical entropy gradient exceeds the Planck-scale threshold:

$$|\nabla S_{\mathcal{O}}|^2 \geq \frac{\hbar}{\ell_P^2\,\tau_{\mathrm{dec}}}$$

with collapse probability:

$$P(|\Psi\rangle \to |e_k\rangle) = \frac{e_k\,|\langle e_k|\Psi\rangle|^2}{\sum_j e_j\,|\langle e_j|\Psi\rangle|^2}$$

Reduces to the standard Born rule when $\hat{\mathcal{E}} = \hat{\mathbf{1}}$.

### OQCT Black-Hole Entropy

$$S^{\mathrm{OQCT}}_{\mathrm{BH}} = \frac{A_{\mathcal{H}}}{4\ell_P^2} + \alpha_{\mathrm{ethic}}\ln\frac{A_{\mathcal{H}}}{\ell_P^2} + \beta\,S_{\mathcal{O}}[\rho_{\mathrm{BH}}] + \mathcal{O}(A^{-1}_{\mathcal{H}})$$

where $\alpha_{\mathrm{ethic}} = -(3/2)(1 + \lambda_\Omega^2/(4\pi)^2) \approx -1.52$, differing from the LQG prediction $\alpha_{\mathrm{LQG}} = -0.5$.

### Conscious Inflation

$$n_s \approx 1 - \frac{2}{N_*} - \frac{\delta_{\mathrm{ethic}}}{N_*^2} \approx 0.9649, \qquad r \approx \frac{12}{N_*^2} \approx 0.0033$$

for $N_* = 60$ e-folds — consistent with Planck 2018 to $<0.1\sigma$.

---

## 🧪 Experimental Predictions

| # | Signature | Observable | Instrument |
|---|-----------|------------|------------|
| E1 | CMB B-mode anomaly | TB cross-correlation at $\ell \sim 3000$, amplitude $\sim 10^{-3}$ | CMB-S4 |
| E2 | Microtubule coherence | $\tau_{\mathrm{coh}} = \hbar/\Delta_{\mathrm{topo}} \approx 25$ ms at 310 K | Quantum spectroscopy |
| E3 | Ethical-decoherence correlation | $\rho = 0.82 \pm 0.02$ in $N = 10^6$ moral dilemma trials | Quantum cognition |
| E4 | BH log correction | $\delta T_H/T_H \sim 10^{-5}$ in late-time Hawking spectrum | GW detectors |
| E5 | Asymptotic safety fixed point | UV fixed point $G^*_{10}$ in graviton scattering | Trans-Planckian (future) |

---

## 📁 Repository Structure

```
oqct/
├── index.html          # Interactive website (Theory, Math, Experiment, Overview, References)
├── README.md           # This file
└── paper/
    ├── OQCT_Moises_2025.pdf    # Full 19-page preprint (LaTeX compiled)
    └── OQCT_Moises_2025.tex    # LaTeX source
```

> **Note:** The `paper/` directory will be added upon Zenodo/arXiv deposit.

---

## 🌐 Live Website

The `index.html` is deployed here:

```
https://quantum.securityops.co
```

The site includes five sections rendered with [MathJax 3](https://www.mathjax.org/):

- **Theory** - abstract, master equation, classical limits, collapse theorem, inflation predictions
- **Mathematics** - full theorem/proof boxes: NC algebra, Moyal product, ethical entropy, RG flow, BH entropy, temporal triality
- **Experiment** - interactive spacetime canvas with live observer-field coupling + all five predictions
- **Overview** - plain-language analogies for non-specialists
- **References** - complete bibliography with DOI links

---

## 📖 Citation

```bibtex
@misc{moises2025oqct,
  author       = {Mois\'{e}s, Cristian Cezar},
  title        = {{The Omnidimensional Quantum-Cosmological Theory (OQCT):
                   Unifying Quantum Field Theory, General Relativity,
                   and Consciousness Physics Through Operator Manifolds}},
  year         = {2026},
  month        = apr,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.15208130},
  url          = {https://doi.org/10.5281/zenodo.15208130},
  note         = {Preprint. MSC2020: 83C45, 81T75, 46L87, 85A40}
}
```

---

## 📚 Key References

- Planck Collaboration. *Astron. Astrophys.* 641, A6 (2020). [DOI:10.1051/0004-6361/201833910](https://doi.org/10.1051/0004-6361/201833910)
- Hameroff & Penrose. *Phys. Life Rev.* 11(1), 39–78 (2014). [DOI:10.1016/j.plrev.2013.08.002](https://doi.org/10.1016/j.plrev.2013.08.002)
- Reuter, M. *Phys. Rev. D* 57(2), 971–985 (1998). [DOI:10.1103/PhysRevD.57.971](https://doi.org/10.1103/PhysRevD.57.971)
- Page, D. N. *Phys. Rev. Lett.* 71(23), 3743–3746 (1993). [DOI:10.1103/PhysRevLett.71.3743](https://doi.org/10.1103/PhysRevLett.71.3743)
- Connes, A. *Noncommutative Geometry*. Academic Press (1994).
- Engel et al. *Nature* 446, 782–786 (2007). [DOI:10.1038/nature05678](https://doi.org/10.1038/nature05678)
- Lambert et al. *Nature Physics* 9(1), 10–18 (2013). [DOI:10.1038/nphys2474](https://doi.org/10.1038/nphys2474)

---

## 👤 Author

**Cristian Cezar Moisés**
Independent Researcher · Caxias do Sul, RS, Brazil

✉️ [ethicalhacker@riseup.net](mailto:ethicalhacker@riseup.net)

🔗 [git.securityops.co/cristiancmoises](https://git.securityops.co/cristiancmoises)

🐙 [github.com/cristiancmoises](https://github.com/cristiancmoises)

---

## 📜 License

This work is licensed under a
[Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to share and adapt the material for any purpose, provided appropriate credit is given.

---

<div align="center">
  <sub>
    "We are not mere observers of the cosmos, but active participants in its quantum-geometric becoming."<br>
    - Cristian Cezar Moisés, 2025
  </sub>
</div>
