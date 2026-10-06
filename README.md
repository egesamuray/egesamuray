# Ege Cirakman

PhD researcher at Georgia Tech working on computationally efficient generative
models, scientific machine learning, inverse problems, and scalable 3D diffusion.
My research spans algorithmic efficiency in diffusion models, wavelet- and
transform-domain generative methods, and GPU-aware implementations using
PyTorch/CUDA, distributed training, JAX, and heterogeneous accelerators.

Computational Science and Engineering PhD, SLIM Lab, advised by
Prof. Felix J. Herrmann.

## Current focus

- Algorithmic and computational efficiency for diffusion and generative models,
  including conditional wavelet diffusion, patch-based modeling, and
  transform-domain preconditioning.
- Scalable 3D diffusion and generative modeling for scientific volumes, with
  emphasis on memory-efficient local/global representations and high-dimensional
  scientific imaging.
- GPU and AI accelerator systems, including PyTorch/CUDA, parallel and
  distributed training, JAX, ROCm/HIP, performance benchmarking, and
  accelerator-aware model design.

## Selected work

| Work | Venue / context | Links |
|---|---|---|
| Ghost Mechanism: An Analytical Model of Abrupt Learning in Recurrent Networks | Physical Review X, 2026; principal author | [Paper](https://doi.org/10.1103/mjcl-lb4x) · [Code](https://github.com/fatihdinc/ghost-mechanism) |
| Dynamical phases of short-term memory mechanisms in RNNs | ICML 2025 | [Paper](https://proceedings.mlr.press/v267/kurtkaya25a.html) · [Code](https://github.com/fatihdinc/dynamical-phases-stm) |
| Wavelet whitened patch-based diffusion prior for velocity models | IMAGE 2026; oral, first author | [Project](https://slim.gatech.edu/content/wavelet-whitened-patch-based-diffusion-prior-velocity-models) |
| Efficient and scalable posterior surrogate for seismic inversion via wavelet score-based generative models | IMAGE 2025; oral, first author | [Project](https://slim.gatech.edu/content/efficient-and-scalable-posterior-surrogate-seismic-inversion-wavelet-score-based-generative) · [Code](https://github.com/egesamuray/cirakman2025IMAGE) |
| Trustworthy SR: Resolving ambiguity in image super-resolution via diffusion models and human feedback | IEEE ICIP 2024 | [Paper](https://arxiv.org/abs/2402.07597) |

## Engineering

### Selected Open-Source Contributions

- **ROCm / Composable Kernel** — Fixed unsafe buffer access patterns in
  low-level HIP/C++ utility code while preserving generated AMDGPU device code.
  Verified with ROCm 7.2 / AMD Clang 22 across gfx90a, gfx1030, and gfx1100,
  including MI210 runtime validation.
  [PR #13146](https://github.com/ROCm/rocm-libraries/pull/13146)

### [JAX / ROCm Systems Lab](https://github.com/egesamuray/jax-rocm-systems-lab)

Reproducible experiments in JAX and accelerator-aware ML systems, with explicit
correctness checks, compilation/runtime separation, and backend metadata.
Current work is extending the harness toward ROCm, multi-GPU communication,
HIP/XLA integration, and performance studies on heterogeneous accelerators.

### [Reproducible Research Workflows](https://github.com/egesamuray/controlled-ai-research-workflows)

A verification-first workflow for scientific software: explicit task scope,
deterministic checks, source and configuration provenance, and artifact
integrity. The public repository is a bounded offline preview with a runnable
integrity check; it does not include the private cluster execution backend.

## Research interests

Generative model efficiency · 3D diffusion · scientific ML · inverse problems ·
scientific imaging · wavelet and curvelet methods · GPU computing · parallel
computing · AI accelerators · ML systems

## Links

[Google Scholar](https://scholar.google.com/citations?user=ZX7U-TgAAAAJ&hl=en) ·
[LinkedIn](https://www.linkedin.com/in/ege-%C3%A7%C4%B1rakman-527759200/)
