# Awesome 3D Human Motion Papers

**语言 / Language:** [简体中文](README.md) | [**English**](README.en.md)

> A curated collection of papers / code / project demos on **3D Human Motion** over the years, covering motion generation, text/music-driven synthesis, human-object/scene interaction, style transfer, retargeting, physics-based simulation, motion prediction, datasets, and representations.
>
> Table fields: **Year | Venue | Method | Problem & Core Idea | Links**.
>
> This list is **updated regularly** for easy reference. Contributions and corrections are welcome.

---

## Table of Contents

- [1. Text-to-Motion](#1-text-to-motion)
- [2. Diffusion & Controllable Generation](#2-diffusion--controllable-generation)
- [3. Music/Audio-to-Motion](#3-musicaudio-to-motion)
- [4. Human-Object / Scene Interaction](#4-human-object--scene-interaction)
- [5. Motion Style Transfer](#5-motion-style-transfer)
- [6. Motion Retargeting](#6-motion-retargeting)
- [7. Physics-based Simulation & Control](#7-physics-based-simulation--control)
- [8. Human Motion Prediction](#8-human-motion-prediction)
- [9. Datasets](#9-datasets)
- [10. Representation & Foundation Models](#10-representation--foundation-models)

---

## 1. Text-to-Motion

| Year | Venue | Method | Problem & Core Idea | Links |
| --- | --- | --- | --- | --- |
| 2024 | CVPR | MoMask | High-quality text-to-motion via residual VQ + masked generative Transformer | [[project]](https://ericguo5513.github.io/momask/) [[code]](https://github.com/EricGuo5513/momask-codes) |
| 2023 | NeurIPS | MotionGPT | Treats motion as a "foreign language", handling many motion tasks with a unified LLM | [[project]](https://motion-gpt.github.io/) [[code]](https://github.com/OpenMotionLab/MotionGPT) |
| 2023 | CVPR | T2M-GPT | VQ-VAE discretization + GPT autoregressive generation; a simple, strong baseline | [[project]](https://mael-zys.github.io/T2M-GPT/) [[code]](https://github.com/Mael-zys/T2M-GPT) |
| 2022 | ECCV | MotionCLIP | Aligns motion to the CLIP text-image latent space for semantic control and disentangled editing | [[paper]](https://arxiv.org/abs/2203.08063) [[code]](https://github.com/GuyTevet/MotionCLIP) |
| 2022 | ECCV | TM2T | Bidirectional text↔motion mapping via motion tokenization + neural machine translation | [[project]](https://ericguo5513.github.io/TM2T/) [[code]](https://github.com/EricGuo5513/TM2T) |
| 2022 | ECCV | TEMOS | Transformer-VAE for text-conditioned motion generation with diverse sampling | [[project]](https://mathis.petrovich.fr/temos/) [[code]](https://github.com/Mathux/TEMOS) |
| 2022 | CVPR | Guo et al. (HumanML3D) | First large-scale text-motion dataset + temporal VAE for text-to-motion | [[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_Generating_Diverse_and_Natural_3D_Human_Motions_From_Text_CVPR_2022_paper.pdf) [[code]](https://github.com/EricGuo5513/HumanML3D) |

## 2. Diffusion & Controllable Generation

| Year | Venue | Method | Problem & Core Idea | Links |
| --- | --- | --- | --- | --- |
| 2024 | TPAMI | MotionDiffuse | First diffusion-based text-driven motion framework; probabilistic mapping + fine-grained body-part control | [[project]](https://mingyuan-zhang.github.io/projects/MotionDiffuse.html) [[code]](https://github.com/mingyuan-zhang/MotionDiffuse) |
| 2024 | ICLR | OmniControl | Unified injection of spatiotemporal control signals over arbitrary joints into a diffusion model | [[project]](https://neu-vi.github.io/omnicontrol/) [[code]](https://github.com/neu-vi/OmniControl) |
| 2024 | ICLR | PriorMDM | Uses a pretrained motion diffusion model as a generative prior for long-sequence / two-person / control tasks | [[project]](https://priormdm.github.io/priorMDM-page/) [[code]](https://github.com/priorMDM/priorMDM) |
| 2024 | ICLR | GenMoStyle | Generative motion stylization in latent space | [[project]](https://yxmu.foo/GenMoStyle/) |
| 2024 | arXiv | MAS | Multi-view ancestral sampling with 2D diffusion to synthesize 3D motion | [[project]](https://guytevet.github.io/mas-page/) |
| 2023 | ICLR | MDM: Human Motion Diffusion Model | One of the first DDPM-based motion generators; predicts the sample itself + geometric losses; multi-task | [[paper]](https://arxiv.org/abs/2209.14916) [[project]](https://guytevet.github.io/mdm-page/) [[code]](https://github.com/GuyTevet/motion-diffusion-model) |
| 2023 | CVPR | MLD (Motion Latent Diffusion) | Diffusion in the motion latent space for large speed-ups and better quality | [[project]](https://chenxin.tech/mld/) [[code]](https://github.com/ChenFengYe/motion-latent-diffusion) |
| 2023 | ICCV | ReMoDiffuse | Retrieval-augmented motion diffusion; retrieved samples improve generalization and fidelity | [[project]](https://mingyuan-zhang.github.io/projects/ReMoDiffuse.html) [[code]](https://github.com/mingyuan-zhang/ReMoDiffuse) |
| 2023 | ICCV | GMD (Guided Motion Diffusion) | Spatial-constraint guidance (trajectory/obstacle/keyframe) via classifier guidance | [[project]](https://korrawe.github.io/gmd-project/) [[code]](https://github.com/korrawe/guided-motion-diffusion) |
| 2023 | ICCV | Fg-T2M | Fine-grained text-to-motion via linguistic-structure parsing + context-aware progressive reasoning | [[paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_Fg-T2M_Fine-Grained_Text-Driven_Human_Motion_Generation_via_Diffusion_Model_ICCV_2023_paper.pdf) |
| 2023 | ICCV | PhysDiff: Physics-Guided Motion Diffusion | Injects physics-simulation projection into denoising to remove penetration/foot-sliding/floating | [[paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Yuan_PhysDiff_Physics-Guided_Human_Motion_Diffusion_Model_ICCV_2023_paper.pdf) [[project]](https://nvlabs.github.io/PhysDiff/) |
| 2023 | AAAI | FLAME | Free-form language-based motion synthesis and editing; a diffusion-based editable framework | [[project]](https://kakaobrain.github.io/flame/) |
| 2023 | NeurIPS | FineMoGen | Spatio-temporally fine-grained, controllable and editable motion generation | [[project]](https://mingyuan-zhang.github.io/projects/FineMoGen.html) [[code]](https://github.com/mingyuan-zhang/FineMoGen) |

## 3. Music/Audio-to-Motion

| Year | Venue | Method | Problem & Core Idea | Links |
| --- | --- | --- | --- | --- |
| 2023 | CVPR | EDGE | Diffusion-based editable dance generation with keyframe/local editing and physical plausibility | [[project]](https://edge-dance.github.io/) [[code]](https://github.com/Stanford-TML/EDGE) |
| 2023 | CVPR | TalkSHOW | Generates full-body (face + hands + body) 3D talking motion from speech | [[project]](https://talkshow.is.tue.mpg.de/) [[code]](https://github.com/yhw-yhw/TalkSHOW) |
| 2022 | CVPR | Bailando | Motion VQ-VAE memory bank + actor-critic GPT for beat-aligned dance | [[paper]](https://arxiv.org/abs/2203.13055) [[code]](https://github.com/lisiyao21/Bailando) |
| 2021 | ICCV | AI Choreographer (FACT) | Music-conditioned 3D dance generation + release of the AIST++ dataset | [[project]](https://google.github.io/aichoreographer/) [[code]](https://github.com/google/aistplusplus_api) |

## 4. Human-Object / Scene Interaction

| Year | Venue | Method | Problem & Core Idea | Links |
| --- | --- | --- | --- | --- |
| 2023 | ICCV | HGHOI | Hierarchical generation of human-object interactions (milestones then infilling) with a diffusion probabilistic model | [[paper]](https://zju3dv.github.io/hghoi/files/paper.pdf) [[code]](https://github.com/zju3dv/hghoi) |
| 2023 | SIGGRAPH Asia | OMOMO | Object-motion-guided human motion synthesis via conditional diffusion + contact constraints | [[paper]](https://arxiv.org/abs/2309.16237) [[code]](https://github.com/lijiaman/omomo_release) |
| 2022 | NeurIPS | HUMANISE | Language-conditioned human-scene interaction synthesis + a large-scale dataset | [[project]](https://silverster98.github.io/HUMANISE/) [[code]](https://github.com/Silverster98/HUMANISE) |
| 2021 | ICCV | SAMP | Scene-aware motion generation supporting diverse target-object interactions (sit/lie down, etc.) | [[project]](https://samp.is.tue.mpg.de/) [[code]](https://github.com/mohamedhassanmus/SAMP) |

## 5. Motion Style Transfer

| Year | Venue | Method | Problem & Core Idea | Links |
| --- | --- | --- | --- | --- |
| 2024 | ICLR | GenMoStyle | Generative motion stylization in latent space with reference-free style sampling | [[project]](https://yxmu.foo/GenMoStyle/) |
| 2022 | TOG | Motion Puzzle | Per-body-part style transfer, enabling local composition of different styles | [[paper]](https://arxiv.org/abs/2202.05274) [[code]](https://github.com/DK-Jang/motion_puzzle) |
| 2020 | SIGGRAPH (TOG) | Aberman et al. | Unpaired motion style transfer via a temporal network with content/style disentanglement | [[project]](https://deepmotionediting.github.io/style_transfer) [[code]](https://github.com/DeepMotionEditing/deep-motion-editing) |

## 6. Motion Retargeting

| Year | Venue | Method | Problem & Core Idea | Links |
| --- | --- | --- | --- | --- |
| 2023 | CVPR | R2ET | Residual neural retargeting balancing fidelity and penetration avoidance | [[paper]](https://arxiv.org/abs/2303.11951) [[code]](https://github.com/Kebii/R2ET) |
| 2020 | SIGGRAPH (TOG) | Skeleton-Aware Networks | Skeleton-aware operators for retargeting across different skeleton topologies | [[project]](https://deepmotionediting.github.io/retargeting) [[code]](https://github.com/DeepMotionEditing/deep-motion-editing) |
| 2018 | CVPR | NKN (Neural Kinematic Networks) | Unsupervised cross-skeleton retargeting with cycle consistency | [[paper]](https://arxiv.org/abs/1804.05653) [[code]](https://github.com/rubenvillegas/cvpr2018nkn) |

## 7. Physics-based Simulation & Control

| Year | Venue | Method | Problem & Core Idea | Links |
| --- | --- | --- | --- | --- |
| 2023 | ICCV | PhysDiff | Physics-guided motion diffusion; see Section 2 | [[project]](https://nvlabs.github.io/PhysDiff/) |
| 2022 | SIGGRAPH (TOG) | ASE | Large-scale unsupervised skill embeddings; learns a reusable library of physics-based character skills | [[project]](https://xbpeng.github.io/projects/ASE/) [[code]](https://github.com/nv-tlabs/ASE) |
| 2021 | SIGGRAPH (TOG) | AMP | Adversarial motion priors; a discriminator replaces hand-crafted rewards to shape natural style | [[project]](https://xbpeng.github.io/projects/AMP/) [[code]](https://github.com/xbpeng/DeepMimic) |
| 2018 | SIGGRAPH (TOG) | DeepMimic | RL imitation of reference motion to learn robust physics-based character control | [[project]](https://xbpeng.github.io/projects/DeepMimic/) [[code]](https://github.com/xbpeng/DeepMimic) |

## 8. Human Motion Prediction

| Year | Venue | Method | Problem & Core Idea | Links |
| --- | --- | --- | --- | --- |
| 2023 | ICCV | HumanMAC | Diffusion-based prediction from a masked-completion perspective; end-to-end with a single loss | [[project]](https://lhchen.top/Human-MAC/) [[code]](https://github.com/LinghaoChan/HumanMAC) |
| 2023 | CVPR | BeLFusion | Latent behavior-disentangled diffusion prediction balancing diversity and realism | [[project]](https://barquerogerman.github.io/BeLFusion/) [[code]](https://github.com/BarqueroGerman/BeLFusion) |
| 2020 | ECCV | DLow | Diverse latent-space sampling to improve diversity of future motion prediction | [[project]](https://www.ye-yuan.com/dlow) [[code]](https://github.com/Khrylx/DLow) |

## 9. Datasets

| Year | Venue | Dataset | Content & Scale | Links |
| --- | --- | --- | --- | --- |
| 2023 | NeurIPS | Motion-X | Large-scale whole-body expressive motion + text dataset, 15.6M frames | [[project]](https://motion-x-dataset.github.io/) [[code]](https://github.com/IDEA-Research/Motion-X) |
| 2022 | CVPR | HumanML3D | Text-motion paired dataset, 14,616 motions / 44,970 texts | [[code]](https://github.com/EricGuo5513/HumanML3D) |
| 2021 | ICCV | AIST++ | 3D dance motion reconstructed from AIST, paired with music | [[project]](https://google.github.io/aistplusplus_dataset/) |
| 2021 | CVPR | BABEL | Per-frame / per-sequence semantic action labels for AMASS | [[project]](https://babel.is.tue.mpg.de/) [[code]](https://github.com/abhinanda-punnakkal/BABEL) |
| 2019 | ICCV | AMASS | Large-scale mocap collection unified to SMPL, >40h, 300+ subjects | [[project]](https://amass.is.tue.mpg.de/) [[code]](https://github.com/nghorbani/amass) |

## 10. Representation & Foundation Models

| Year | Venue | Method | Problem & Core Idea | Links |
| --- | --- | --- | --- | --- |
| 2020 | ECCV | VIBE / mocap family | Temporal human reconstruction regressing SMPL from video (reference) | [[code]](https://github.com/mkocabas/VIBE) |
| 2019 | CVPR | SMPL-X | Expressive whole-body model (body + hands + face) + VPoser pose prior | [[project]](https://smpl-x.is.tue.mpg.de/) [[code]](https://github.com/vchoutas/smplx) |
| 2015 | SIGGRAPH Asia (TOG) | SMPL | Linear blend-skinning parametric human body model (shape + pose blendshapes) | [[project]](https://smpl.is.tue.mpg.de/) |

---

## Changelog

- **2026-08-08**: Restructured into categorized tables; added key and recent works across Text-to-Motion / Diffusion / Music-driven / Interaction / Style / Retargeting / Physics / Prediction / Datasets / Representation.

## Contributing

Contributions of new papers via PR / Issue are welcome. Please follow this format: `Year | Venue | Method | one-line core idea | paper/code/project links`.
