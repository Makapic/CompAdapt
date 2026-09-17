# CompAdapt: Adaptable Composite Motion Modeling for Physics-Consistent Text-to-Video Generation

[![project page](https://img.shields.io/badge/Project%20Page-CompAdapt-3776AB?logo=githubpages)](https://makapic.github.io/CompAdapt/)
[![arXiv](https://img.shields.io/badge/arXiv-coming%20soon-B31B1B?logo=arxiv)]()

**[Project Page](https://makapic.github.io/CompAdapt/)** | **Paper** (arXiv, coming soon) | **Code** (this repository)

[Haoran Qin](https://github.com/Makapic)<sup>1</sup>, Renlong Wu<sup>1</sup>, Tianyu Huang<sup>1</sup>, Yukang Ding<sup>2</sup>, Hui Li<sup>1</sup>, Wangmeng Zuo<sup>1</sup>

<sup>1</sup> Harbin Institute of Technology, China &nbsp;&middot;&nbsp; <sup>2</sup> Taobao, Alibaba Group, China

**CompAdapt** is a physics-consistent text-to-video (T2V) framework for adaptable generation across complex real-world scenarios. It extends neural dynamics modeling beyond single-type motions to *composite* physical behaviors (coupled motions, multi-stage transitions, and multi-object collisions), translates natural-language prompts into structured physical semantics, and introduces dynamics-aware prior matching for **one-shot adaptation** to unseen physical laws without retraining the core dynamics module, together with a physics-aware latent feature fusion module for high-fidelity video. Experiments show improved physical consistency over general T2V models and physics-constrained baselines while preserving visual quality.

## News
- **2026-09** Project page is live; arXiv preprint submitted. Inference/training code, datasets, and checkpoints will be released here.

## Release plan
- [ ] Inference code and pretrained checkpoints
- [ ] Training code (dual-LLM parser, collision module, physics-aware generator, one-shot adaptation)
- [ ] Datasets: Text2Phys, CollidePhys, CompoPhys, and the expanded OODPhys benchmark
- [ ] Evaluation scripts (Physical Invariance Score) and state-extraction pipeline
- [ ] Generated videos

## Installation
```bash
git clone https://github.com/Makapic/CompAdapt.git
cd CompAdapt
# Environment setup and pretrained-model download instructions will be added with the code release.
```

## Quick start
Coming soon with the inference release.

## Project page
The project website (teaser, qualitative/ablation comparisons, and one-shot-adaptation demos with videos) lives in the [`docs/`](docs) folder of this repository and is published via GitHub Pages at
**https://makapic.github.io/CompAdapt/**.

## Citation
```bibtex
@article{compadapt2026,
  title={CompAdapt: Adaptable Composite Motion Modeling for Physics-Consistent Text-to-Video Generation},
  author={Haoran Qin and Renlong Wu and Tianyu Huang and Yukang Ding and Hui Li and Wangmeng Zuo},
  journal={arXiv preprint},
  year={2026},
  url={https://makapic.github.io/CompAdapt/}
}
```

## Acknowledgements
This work builds on prior physics-constrained T2V research and open-source video-generation models; detailed acknowledgements will follow with the code release. The code license will be specified upon release.