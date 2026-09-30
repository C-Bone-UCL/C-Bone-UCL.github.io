---
title: "Discovery and recovery of crystalline materials with property-conditioned transformers"
date: 2025-11-26
publishDate: 2025-11-26
type: publication
authors: ["**Cyprien Bone**", "Matthew Walker", "Bradley A. A. Martin", "Kuangdai Leng", "Luis M. Antunes", "Ricardo Grau-Crespo", "Amil Aligayev", "Javier Dominguez", "Keith T. Butler"]
publication_types: ["3"]
abstract: "Generative models have recently shown great promise for accelerating the design and discovery of new functional materials. Conditional generation enhances this capacity by allowing inverse design, where specific desired properties can be requested during the generation process. However, conditioning of transformer-based approaches, in particular, is constrained by discrete tokenisation schemes and the risk of catastrophic forgetting during fine-tuning. This work introduces CrystaLLM-π (property injection), a conditional autoregressive framework that integrates continuous property representations directly into the transformer's attention mechanism. Two architectures, Property-Key-Value (PKV) Prefix attention and PKV Residual attention, are presented. These methods bypass inefficient sequence-level tokenisation and preserve foundational knowledge from unsupervised pre-training on Crystallographic Information Files (CIFs) as textual input. We establish the efficacy of these mechanisms through systematic robustness studies and evaluate the framework's versatility across two distinct tasks. First, for structure recovery, the model processes high-dimensional, heterogeneous X-ray diffraction patterns, achieving structural accuracy competitive with specialised models and demonstrating applications to experimental structure recovery and polymorph differentiation. Second, for materials discovery, the model is fine-tuned on a specialised photovoltaic dataset to generate novel, stable candidates validated by Density Functional Theory (DFT). It implicitly learns to target optimal band gap regions for high photovoltaic efficiency, demonstrating a capability to map complex structure-property relationships. CrystaLLM-π provides a unified, flexible, and computationally efficient framework for inverse materials design."
featured: true
publication: "arXiv:2511.21299 (under review)"
image:
  caption: ""
  focal_point: Center
links:
  - {icon_pack: ai, icon: arxiv, name: arXiv, url: 'https://arxiv.org/abs/2511.21299'}
  - {icon_pack: fab, icon: github, name: Code, url: 'https://github.com/C-Bone-UCL/CrystaLLM-pi'}
  - {icon_pack: fas, icon: flask, name: Paper code, url: 'https://github.com/C-Bone-UCL/CrystaLLM-pi-paper'}
---
