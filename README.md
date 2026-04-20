<div align="center">

## 🎬→🗣️ Hierarchical Codec Diffusion for Video-to-Speech Generation

[![Paper](https://img.shields.io/badge/arXiv-Paper-b31b1b.svg)](https://arxiv.org/abs/2604.15923)
[![Demo](https://img.shields.io/badge/Project-Demo%20Page-red?logo=youtube&logoColor=white)](https://youtu.be/2GIXF2toO_Q)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

</div>

### 📖 Abstract

Video-to-Speech (VTS) generation aims to synthesize speech from a silent video without auditory signals. However, existing VTS methods disregard the hierarchical nature of speech, which spans coarse speaker-aware semantics to fine-grained prosodic details. This oversight hinders direct alignment between visual and speech features at specific hierarchical levels. In this paper, we propose **HiCoDiT**, a novel Hierarchical Codec Diffusion Transformer. Leveraging the Residual Vector Quantization (RVQ)-based codec, HiCoDiT explicitly exploits the hierarchy of discrete speech tokens:
- **Low-level blocks:** Condition on lip-synchronized motion and facial identity to capture coarse speaker-aware content.
- **High-level blocks:** Modulate fine-grained prosodic dynamics using facial expressions.

Furthermore, we introduce a **Dual-scale Adaptive Instance Layer Normalization** to jointly capture global vocal style (channel-wise) and local prosody dynamics (temporal-wise). Extensive experiments demonstrate that HiCoDiT outperforms baselines in both fidelity and expressiveness.

### 🚀 News & TODO

We are currently organizing the codebase to ensure a clean and reproducible open-source release. Stay tuned!

- [ ] **[Coming Soon]** Release inference code and pre-trained models.
- [ ] **[Coming Soon]** Release the training scripts and dataset preparation guidelines.
- [x] **[2026-02]** Paper is accepted by CVPR 2026.


### 🔗 Citation

If you find our work helpful for your research, please consider citing our paper:

```bibtex
@inproceedings{hicodit:conf/cvpr/Ye,
  author       = {Jiaxin Ye and
                 Gaoxiang Cong and
                  Chenhui Wang and
                  Xin-Cheng Wen and
                    Zhaoyang Li and
                    Boyuan Cao and
                    Hongming Shan},
  title        = {Hierarchical Codec Diffusion for Video-to-Speech Generation},
  booktitle    = {{IEEE Conf. Comput. Vis. Pattern Recog.}},
  pages        = {},
  year         = {2026}
}

@inproceedings{demoface:conf/icml/Ye,
  author       = {Jiaxin Ye and
                  Boyuan Cao and
                  Hongming Shan},
  title        = {Emotional Face-to-Speech},
  booktitle    = {{Int. Conf. on Mach. Learn.}},
  volume       = {267},
  year         = {2025},
}
