# Supplementary Material: Spatially-Lifted SCvx NMPC for Articulated Loaders

**Authors:** Thanh Binh Do, François Guérin  
**Affiliation:** GREAH Laboratory, Le Havre Normandy University, France  
**Submitted to:** European Control Conference (ECC) 2026

## Overview

This repository contains complete mathematical proofs for the main 
theoretical contributions presented in our ECC 2026 submission:

> *"Spatially-Lifted SCvx NMPC for an Articulated Loader with 
> SIPP-generated Time-Corridor Constraints"*

## Contents

### Main Document
- **[`supplementary_proofs.pdf`](supplementary_proofs.pdf)** (10 pages)
  - Complete derivations for all theorems and lemmas
  - Explicit formulas for all constants
  - Self-contained proofs with detailed steps

### Structure

**Section 1: Proof of Lemma 1 (Well-Posedness)** (Pages 2-4)
- Computation of Lipschitz constants for drift term f_a
- Computation of Lipschitz constants for input matrix G  
- Verification of Carathéodory conditions
- Explicit bound L = L_a + L_G C_w

**Section 2: Proof of Theorem 2 (Recursive Feasibility)** (Pages 5-8)
- Construction of feasible shift-append candidate
- Application of discrete Grönwall inequality
- Derivation of state deviation bound (Eq. 24)
- Derivation of consistency slack bound ε_ν (Eq. 25)
- Derivation of time-corridor slack bound ε_σ (Eq. 26)
- Explicit formulas for C_z, H_ψ, and C_σ

**Section 3: Proof of Theorem 3 (Practical Stability)** (Pages 9-10)
- NMPC Lyapunov function analysis
- Terminal set invariance verification
- Value function decrease outside terminal set
- Ultimate boundedness to O(√ε) neighborhood

## Citation

If you find this work useful, please cite our ECC 2026 paper:
```bibtex
@inproceedings{do2026spatially,
  title={Spatially-Lifted SCvx NMPC for an Articulated Loader with 
         SIPP-generated Time-Corridor Constraints},
  author={Do, Thanh Binh and Gu\'erin, Fran\c{c}ois},
  booktitle={European Control Conference (ECC)},
  year={2026}
}
```

## Contact

For questions or clarifications:
- Thanh Binh Do: thanh-binh.do@univ-lehavre.fr
- François Guérin: francois.guerin@univ-lehavre.fr

## License

The supplementary material is provided for academic research purposes.  
© 2026 GREAH Laboratory, Le Havre Normandy University

## Acknowledgments

This work was supported by the PROMETE Project, GREAH, Le Havre 
Normandy University, France.

---

*Last updated: January 2026*
