## Yujie Chen

Computer vision researcher working on **low-light image enhancement** — recovering usable detail from
under-exposed scenes without blowing out the highlights that are already there.

My current work is on **exposure-aware loss design**: instead of enhancing an image uniformly, supervise
dark regions and bright regions under different objectives, so that lifting the shadows does not cost you
the highlights.

- **Research interests** — low-light enhancement, zero-reference / unsupervised supervision, Retinex-based methods, no-reference image quality assessment
- **Toolchain** — PyTorch · OpenCV · NumPy · CUDA
- **Links** — [Homepage](https://chenyujiedev.github.io) · [LinkedIn](https://www.linkedin.com/in/yujie-chen-342467190/)

---

### Research

**[paper-Experiment](https://github.com/chenyujiedev/paper-Experiment)** — code for my paper on low-light enhancement.

- Two loss functions of my own design, built on the Zero-DCE framework: `DarkRegionExposureLoss`
  (region-specific exposure supervision) and `HighlightPreservationLoss` (guards against over-enhancement)
- Benchmarked against **Retinexformer** and **RUAS** on their published datasets
- Evaluated both no-reference (**NIQE**, **BRISQUE**, **LOE**) and full-reference (**PSNR**, **SSIM**, **LPIPS**) metrics

Ongoing: extending exposure-aware supervision from enhancement to **downstream detection under low light** —
whether enhancement that looks better actually detects better.

---

### Coursework

Graduate coursework and assignments, kept public for reference:

[Adaptive CLAHE + Gamma](https://github.com/chenyujiedev/Adaptive-CLAHE-Gamma) — classical illumination correction ·
[Advanced Algorithm Design & Analysis](https://github.com/chenyujiedev/Advanced-Algorithm-Design-and-Analysis-50070) ·
[Advanced Distributed Systems](https://github.com/chenyujiedev/Advanced-Distributed-Systems) ·
[Machine Learning](https://github.com/chenyujiedev/homeWorkOfML)

---

<sub>This repository also hosts the Hexo source for <a href="https://chenyujiedev.github.io">chenyujiedev.github.io</a>.</sub>
