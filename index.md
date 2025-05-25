---
layout: default
title: Welcome
---

# Charlie Cameron


I’m a PhD student in the SAMBa CDT at the University of Bath. My work blends stochastic and deterministic modelling to better understand complex biological systems. I focus on **reaction–diffusion processes**—like the Fisher-KPP model—where randomness plays an important role in early dynamics. Since fully stochastic simulations can be computationally expensive, I use a hybrid approach that combines them with faster PDE-based methods in regions where randomness has less impact.

## Research: Spatial Regime Conversion Method (SRCM)

I’m developing a **hybrid method** that combines:
- 🟦 **Stochastic Simulation Algorithms (SSA)** in low-density regions  
- 🟩 **Partial Differential Equations (PDEs)** in high-density regions  

This method improves computational efficiency while preserving key stochastic features.

I’m currently extending this method into **1D reaction–diffusion systems**, building on [Kynaston, Yates et al. (2023)](https://doi.org/10.3389/fams.2023.1107441), which proposed a non-spatial regime conversion technique.  
🧪 You can explore the working code for the SRCM applied to the Fisher-KPP model on [GitHub](https://github.com/Cgyc20/SRCM_KPP).

![SRCM output plot](assets/img/fisher_7.png)  
*Hybrid SRCM output: cyan = stochastic, dashed black = hybrid (dark blue stochastic + green PDE), solid green = pure PDE.*

---

## Supervision

- **Prof Kit Yates** — Department of Mathematical Sciences, University of Bath  
- **Dr Cameron Smith** — Department of Mathematical Sciences, University of Bath

---

## Contact

- 📧 [cgyc20@bath.ac.uk](mailto:cgyc20@bath.ac.uk)  
- 🐙 [GitHub](https://github.com/cgyc20)