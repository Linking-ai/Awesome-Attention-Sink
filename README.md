<h1 align="center">🚀 Attention Sink in Transformers: <br> A Survey on Utilization, Interpretation, and Mitigation</h1>

<div align="center">

[![PDF](https://img.shields.io/badge/PDF-Download-red?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://github.com/ZunhaiSu/Awesome-Attention-Sink/releases)
[![Status](https://img.shields.io/badge/STATUS-Active-brightgreen?style=for-the-badge)]()
[![arXiv](https://img.shields.io/badge/arXiv-XXXX.XXXXX-b31b1b?style=for-the-badge)](https://arxiv.org/abs/XXXX.XXXXX)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/ZunhaiSu/Awesome-Attention-Sink?style=social)](https://github.com/ZunhaiSu/Awesome-Attention-Sink/stargazers)

</div>

<div align="center">
  ⭐ If you find this repository helpful, please consider giving it a star.
</div>

---

## 📚 Table of Contents

- [Latest News](#-latest-news)
- [Overview](#-overview)
- [Paper List](#-paper-list)
  - [Classical Language Models](#classical-language-models)
  - [Large Language Models](#large-language-models)
  - [Mixture-of-Experts Large Language Models](#mixture-of-experts-large-language-models)
  - [Multi-Modal Large Language Models](#multi-modal-large-language-models)
  - [Vision Transformers](#vision-transformers)
  - [Diffusion Transformers](#diffusion-transformers)
  - [Diffusion Language Models](#diffusion-language-models)
  - [Linear Attention Models](#linear-attention-models)
  - [Vision-Language-Action Models](#vision-language-action-models)
  - [General Transformers](#general-transformers)
- [Citation](#-citation)
- [Contact](#-contact)

---

## 🔥 Latest News

- **[2026-04-11]** Repository launched to track the latest progress in Attention Sink research.

---

## 📖 Overview

This repository organizes papers on **Attention Sink (AS)** — where Transformers disproportionately focus on uninformative tokens, causing interpretability issues, training/inference inefficiencies, and hallucinations.

<div align="center">
  <img src="Figures/paper_overview.png" alt="Survey Framework" width="80%">
  <br>
  <em>Figure 1: Overview of the survey structure.</em>
</div>

<br>

**We have systematically reviewed the development of AS research**, identifying a clear trajectory across three stages. Our survey further grounds this framework by examining how each stage manifests across different Transformer architectures.

<div align="center">
  <img src="Figures/num_research.png" alt="Research Trends" width="80%">
  <br>
  <em>Figure 2: Cumulative publication count and temporal trends in AS research (2023–2026).</em>
</div>

<br>

### Three Research Stages

**① Fundamental Utilization** (2023–present)
> Empirical exploitation of AS and management of its immediate effects.
> *Approaches include:* Sink Token Preservation, Attention Redistribution, Learnable Prefix Tokens, Sink Token Repurposing.

**② Mechanistic Interpretation** (2024–present)
> Investigation of underlying causes and architectural factors.
> *Theories include:* Softmax Limitations & No-Op Theory, Outlier Circuits, Implicit Attention Bias, Geometric Anchoring and others.

**③ Strategic Mitigation** (2025–present)
> Direct structural mitigation for training stability and deployment robustness.
> *Strategies include:* Gated Attention Mechanisms, Modified Softmax Functions, Learnable Attention Bias, Pre-training Interventions and others.

---

## 📑 Paper List

> Each paper is annotated with tags corresponding to the three AS dimensions. A dash `—` indicates that a particular dimension is not addressed in the work.

### Classical Language Models

### Large Language Models

### Mixture-of-Experts Large Language Models

### Multi-Modal Large Language Models

### Vision Transformers

### Diffusion Transformers

### Diffusion Language Models

### Linear Attention Models

### Vision-Language-Action Models

### General Transformers

---

## 🌟 Citation

If you find this survey or repository useful for your research, please cite:

```bibtex
@article{su2026attentionsink,
  title={Attention Sink in Transformers: A Survey on Utilization, Interpretation, and Mitigation},
  author={Su, Zunhai and ...},
  journal={arXiv preprint arXiv:XXXX.XXXXX},
  year={2026}
}
```

## 📧 Contact

Feel free to open an issue or contact us if you have any questions or want to include your work in this list.

Corresponding Author: Zunhai Su (zh-su23@mails.tsinghua.edu.cn)
