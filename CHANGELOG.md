# Changelog

All notable changes to OQCT are documented in this file.
Format follows [Keep a Changelog](https://keepachangelog.com/).

---

## [v2.0] — 2026-05-05 — Mathematical Foundations Revised

A complete mathematical reformulation of the April 2025 v1.0 preprint.
Every previous claim was re-examined and either proved as a theorem,
demoted to a falsifiable conjecture, or labeled as phenomenological.

### Added

- **Notation table** at the start of the paper defining every symbol used.
- **Manifold schematic figure** (TikZ) showing the three sectors of $\mathcal{M}^{10}_{\mathrm{QC}}$
  and their predicted observables.
- **Status of the Theory table** distinguishing proven theorems, conjectures,
  and phenomenological fits — for every result in the paper.
- **Five worked examples** (free particle, hydrogen atom, two-slit, de Sitter,
  Schwarzschild) showing reduction to or perturbation of standard physics.
- **Two-loop beta function** computation for the ethical coupling $\lambda_\Omega$
  with explicit critical exponent showing UV-attractivity.
- **Black-hole logarithmic correction** $\alpha_{\mathrm{ethic}}\approx-1.52$
  derived from the conformal anomaly of the ethical gauge sector.
- **Hermiticity / unitarity proposition** for the master operator on globally
  hyperbolic backgrounds with spacelike $\theta$.
- **Probability current continuity** proposition.
- **POVM-Gleason derivation** of the extended Born rule, replacing the v1 postulate.
- **Spohn's theorem citation** for the temporal-arrow proof.
- **Falsifiability criteria** explicitly stated for every conjecture.
- **Appendix C — "What Was Changed from v1.0"** summarising all corrections.
- **Lindblad-form appendix** connecting the master dynamics to GKSL semigroups.
- **Bibliography expansion**: Seiberg-Witten 1999, Busch 2003, Lieb 1973,
  Lindblad 1976, GKS 1976, Spohn 1978, Machacek-Vaughn 1983/1984,
  Gibbons-Hawking 1977, Christensen-Duff 1979, Kaul-Majumdar 1998, Sen 2013,
  Petz 2008, Bures 1969.

### Changed

- **Canonical commutator** changed from $[\hat x^\mu,\hat x^\nu]=i\ell_P^2\varepsilon^{\mu\nu\rho}\hat x_\rho$
  (not Lorentz-covariant) to $[\hat x^\mu,\hat x^\nu]=i\theta^{\mu\nu}\hat{\mathbf{1}}$
  (standard Seiberg-Witten constant tensor).
- **Moyal star product associativity** upgraded from claim to all-orders proof.
- **Observer-coupling entropy functional** $S_{\mathcal{O}}$ recast as scalar
  product (rather than tensor product as in v1) so that bounds become provable.
- Properties of $S_{\mathcal{O}}$ — non-negativity, joint concavity, partial-trace
  monotonicity (DPI analog) — promoted from assertions to theorems with full proofs.
- **Inflation prediction** $n_s\approx 0.965$ reframed from "derivation" to
  "phenomenological consistency". Compatibility with Planck 2018 does not
  single out OQCT.
- Throughout the paper, "consciousness" replaced by "observer-coupling sector"
  wherever the math does not actually distinguish phenomenal experience from
  generic measurement coupling.
- Section structure reorganized for cleaner exposition.
- Author email updated to `ccm@riseup.net`.
- Repository URL updated to `https://github.com/cristiancmoises/oqct`.

### Demoted (Theorem → Conjecture)

- **Ethical-gradient collapse criterion** is now a falsifiable conjecture, not
  a theorem. Falsifiability conditions are explicit.
- **Page curve restoration** during Hawking evaporation is a falsifiable conjecture.

### Removed

- **Stanford Neuroquantics Laboratory citation** (non-verifiable reference).
- All numerical correlations attributed to that source: $\beta=0.73\pm 0.02$,
  correlation $\rho=0.82\pm 0.02$, etc.
- **Author epigraph** at the end of the paper (improper register for a
  peer-review submission).
- **Malformed bra-ket expression** $\langle\hat T_{\mathrm{past}}\rangle\hat T_{\mathrm{fut}}|\rangle$
  from v1's temporal triality section — replaced with a clean direct sum
  of multiplication operators.

### Fixed

- Lorentz covariance of the non-commutative algebra.
- Internal consistency of the temporal triality operator definition.
- Hyperref / TOC bookmarks now match section structure.
- PDF metadata updated (title, author, keywords).

---

## [v1.0] — 2025-04-14 — Initial Release

First public version of OQCT. See `paper/OQCT_v1_Moises_2025.pdf` for the
archived original. This version is now considered superseded by v2.0
but is preserved for reference and citation comparison.
