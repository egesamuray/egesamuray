# Ege Cirakman

I am a PhD researcher at Georgia Tech. I work on efficient generative models,
scientific machine learning, inverse problems, and scalable 3D diffusion.
I study algorithmic efficiency in diffusion models and wavelet- and
transform-domain generative methods. I write the GPU implementations in
PyTorch/CUDA and JAX, and I work with distributed training and heterogeneous
accelerators.

Computational Science and Engineering PhD, SLIM Lab, advised by
Prof. Felix J. Herrmann.

## Current focus

- Algorithmic and computational efficiency of diffusion and generative models.
  This includes conditional wavelet diffusion, patch-based modeling, and
  transform-domain preconditioning.
- Scalable 3D diffusion and generative modeling for scientific volumes, mainly
  memory-efficient local/global representations and high-dimensional
  scientific imaging.
- GPU and AI accelerator systems: PyTorch/CUDA, JAX, ROCm/HIP, and parallel and
  distributed training. I also do performance benchmarking and design models
  with the target accelerator in mind.

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

- **ROCm / Composable Kernel.** Fixed unsafe buffer access in low-level HIP/C++
  utility code without changing the generated AMDGPU device code. Tested with
  ROCm 7.2 and AMD Clang 22 on gfx90a, gfx1030, and gfx1100, with runtime
  validation on an MI210.
  [PR #13146](https://github.com/ROCm/rocm-libraries/pull/13146)

### [JAX / ROCm Systems Lab](https://github.com/egesamuray/jax-rocm-systems-lab)

Reproducible experiments in JAX and ML systems. The experiments include
correctness checks, separate compilation from runtime measurements, and record
backend metadata. I am now extending the harness to ROCm, multi-GPU
communication, HIP/XLA integration, and performance studies on heterogeneous
accelerators.

### [Reproducible Research Workflows](https://github.com/egesamuray/controlled-ai-research-workflows)

A workflow for scientific software that puts verification first. It uses
explicit task scopes and deterministic checks. It also tracks source and
configuration provenance and artifact integrity. The public repository is a
limited offline preview with an integrity check you can run. It does not
include the private cluster execution backend.

## Research interests

Generative model efficiency · 3D diffusion · scientific ML · inverse problems ·
scientific imaging · wavelet and curvelet methods · GPU computing · parallel
computing · AI accelerators · ML systems

## Links

[Google Scholar](https://scholar.google.com/citations?user=ZX7U-TgAAAAJ&hl=en) ·
[LinkedIn](https://www.linkedin.com/in/ege-%C3%A7%C4%B1rakman-527759200/)
