# Ege Cirakman

PhD researcher at Georgia Tech working on scientific machine learning,
computationally efficient generative models, inverse problems, and scalable 3D
generation. My current work also explores GPU-aware ML systems and performance
engineering across PyTorch, JAX, and heterogeneous accelerators.

Computational Science and Engineering PhD, SLIM Lab, advised by
Prof. Felix J. Herrmann.

## Current focus

- Efficient diffusion and generative models for scientific imaging and inverse
  problems.
- Scalable 3D generation with global/local, patch-based, and transform-domain
  representations.
- GPU and ML systems work on distributed training, reproducible benchmarking,
  JAX, and ROCm/HIP.

## Selected work

| Work | Venue / context | Links |
|---|---|---|
| Ghost Mechanism: An Analytical Model of Abrupt Learning in Recurrent Networks | Physical Review X, 2026; principal author | [Paper](https://doi.org/10.1103/mjcl-lb4x) · [Code](https://github.com/fatihdinc/ghost-mechanism) |
| Dynamical phases of short-term memory mechanisms in RNNs | ICML 2025 | [Paper](https://proceedings.mlr.press/v267/kurtkaya25a.html) · [Code](https://github.com/fatihdinc/dynamical-phases-stm) |
| Wavelet whitened patch-based diffusion prior for velocity models | IMAGE 2026; oral, first author | [Project](https://slim.gatech.edu/content/wavelet-whitened-patch-based-diffusion-prior-velocity-models) |
| Efficient and scalable posterior surrogate for seismic inversion via wavelet score-based generative models | IMAGE 2025; oral, first author | [Project](https://slim.gatech.edu/content/efficient-and-scalable-posterior-surrogate-seismic-inversion-wavelet-score-based-generative) · [Code](https://github.com/egesamuray/cirakman2025IMAGE) |
| Trustworthy SR: Resolving ambiguity in image super-resolution via diffusion models and human feedback | IEEE ICIP 2024 | [Paper](https://arxiv.org/abs/2402.07597) |

## Engineering

### [JAX / ROCm Systems Lab](https://github.com/egesamuray/jax-rocm-systems-lab)

Small, reproducible JAX systems experiments. It currently has a CPU matmul
benchmark harness with correctness checks, synchronized timing samples, and
backend/runtime metadata. Accelerator work on ROCm, RCCL, and HIP/XLA FFI is
ongoing, and no ROCm performance result is claimed before it is measured on AMD
hardware.

### [Reproducible Research Workflows](https://github.com/egesamuray/controlled-ai-research-workflows)

A verification-first workflow for scientific software: explicit task scope,
deterministic checks, source and configuration provenance, and artifact
integrity. The public repository is a bounded offline preview with a runnable
integrity check; it does not include the private cluster execution backend.

## Research interests

Scientific ML · generative modeling · diffusion models · inverse problems ·
scientific imaging · scalable 3D · wavelet and curvelet methods · GPU systems

## Links

[Google Scholar](https://scholar.google.com/citations?user=ZX7U-TgAAAAJ&hl=en) ·
[LinkedIn](https://www.linkedin.com/in/ege-%C3%A7%C4%B1rakman-527759200/)
