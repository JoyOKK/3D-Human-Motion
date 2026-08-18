# Awesome 3D Human Motion Papers

**语言 / Language:** [简体中文](README.md) | [**English**](README.en.md)

> A curated collection of papers / code / project demos on **3D Human Motion** over the years, covering motion generation, text/music-driven synthesis, human-object/scene interaction, style transfer, retargeting, physics-based simulation, motion prediction, datasets, and representations.
>
> Table fields: **Year | Venue | Method | Problem & Core Idea | Project | GitHub**.
>
> This list is **updated regularly** for easy reference. Contributions and corrections are welcome.
>
> Some recent entries are adapted from [Foruck/Awesome-Human-Motion](https://github.com/Foruck/Awesome-Human-Motion); the `[paper]` / `[project]` / `[code]` links for those entries are taken directly from that project.

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

| Year | Venue | Method | Problem & Core Idea | Project | GitHub |
| --- | --- | --- | --- | --- | --- |
| 2026 | SIGGRAPH (TOG) | ARDY | Autoregressive diffusion for real-time interactive motion generation; hybrid explicit-root + latent-body representation with online text and long-horizon kinematic constraints | [![link](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/sil/projects/ardy/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=nv-tlabs/ardy)](https://github.com/nv-tlabs/ardy) |
| 2026 | CVPR | Next-Scale AR | Next-scale autoregressive prediction for text-to-motion generation |  |  |
| 2026 | CVPR | LaMoGen | LLM-guided symbolic inference mapping language to motion |  |  |
| 2025 | ICML | Being-M0 | Scaling motion generation models with million-level human motions |  |  |
| 2025 | ICCV | GENMO | A generalist model unifying generation, reconstruction and forecasting | [![link](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/dair/genmo/) |  |
| 2025 | CVPR | MARDM | Rethinking diffusion for text-driven motion (masked autoregressive diffusion) |  |  |
| 2025 | CVPR | ScaMo | Exploring the scaling law in autoregressive motion generation | [![link](https://img.shields.io/badge/Website-9cf)](https://shunlinlu.github.io/ScaMo/) |  |
| 2025 | ICLR | LaMP | Language-motion pretraining for generation, retrieval and captioning |  |  |
| 2025 | ICLR | Motion-Agent | A conversational framework for human motion generation with LLMs | [![link](https://img.shields.io/badge/Website-9cf)](https://knoxzhao.github.io/Motion-Agent/) |  |
| 2025 | IJCV | Fg-T2M++ | LLM-augmented fine-grained text-driven motion generation |  |  |
| 2025 | Arxiv | Motion-R1 | Chain-of-thought reasoning + RL for motion generation | [![link](https://img.shields.io/badge/Website-9cf)](https://motion-r1.github.io/) |  |
| 2025 | Arxiv | MotionGPT3 | Treating human motion as a second modality in a unified model |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=OpenMotionLab/MotionGPT3)](https://github.com/OpenMotionLab/MotionGPT3) |
| 2024 | CVPR | MoMask | High-quality text-to-motion via residual VQ + masked generative Transformer | [![link](https://img.shields.io/badge/Website-9cf)](https://ericguo5513.github.io/momask/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=EricGuo5513/momask-codes)](https://github.com/EricGuo5513/momask-codes) |
| 2023 | NeurIPS | MotionGPT | Treats motion as a "foreign language", handling many motion tasks with a unified LLM | [![link](https://img.shields.io/badge/Website-9cf)](https://motion-gpt.github.io/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=OpenMotionLab/MotionGPT)](https://github.com/OpenMotionLab/MotionGPT) |
| 2023 | CVPR | T2M-GPT | VQ-VAE discretization + GPT autoregressive generation; a simple, strong baseline | [![link](https://img.shields.io/badge/Website-9cf)](https://mael-zys.github.io/T2M-GPT/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=Mael-zys/T2M-GPT)](https://github.com/Mael-zys/T2M-GPT) |
| 2022 | ECCV | MotionCLIP | Aligns motion to the CLIP text-image latent space for semantic control and disentangled editing |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=GuyTevet/MotionCLIP)](https://github.com/GuyTevet/MotionCLIP) |
| 2022 | ECCV | TM2T | Bidirectional text↔motion mapping via motion tokenization + neural machine translation | [![link](https://img.shields.io/badge/Website-9cf)](https://ericguo5513.github.io/TM2T/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=EricGuo5513/TM2T)](https://github.com/EricGuo5513/TM2T) |
| 2022 | ECCV | TEMOS | Transformer-VAE for text-conditioned motion generation with diverse sampling | [![link](https://img.shields.io/badge/Website-9cf)](https://mathis.petrovich.fr/temos/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=Mathux/TEMOS)](https://github.com/Mathux/TEMOS) |
| 2022 | CVPR | Guo et al. (HumanML3D) | First large-scale text-motion dataset + temporal VAE for text-to-motion |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=EricGuo5513/HumanML3D)](https://github.com/EricGuo5513/HumanML3D) |

## 2. Diffusion & Controllable Generation

| Year | Venue | Method | Problem & Core Idea | Project | GitHub |
| --- | --- | --- | --- | --- | --- |
| 2025 | ICCV | MotionLab | Unifies motion generation and editing via the Motion-Condition-Motion paradigm | [![link](https://img.shields.io/badge/Website-9cf)](https://diouo.github.io/motionlab.github.io/) |  |
| 2025 | ICCV | MotionStreamer | Streaming motion generation via diffusion-based autoregression in causal latent space | [![link](https://img.shields.io/badge/Website-9cf)](https://zju3dv.github.io/MotionStreamer/) |  |
| 2025 | ICCV | ControlMM | Controllable masked motion generation | [![link](https://img.shields.io/badge/Website-9cf)](https://www.ekkasit.com/ControlMM-page/) |  |
| 2025 | ICCV | Less Is More | Improving motion diffusion models with sparse keyframes |  |  |
| 2025 | CVPR | EnergyMoGen | Compositional motion generation with energy-based diffusion in latent space | [![link](https://img.shields.io/badge/Website-9cf)](https://jiro-zhang.github.io/EnergyMoGen/) |  |
| 2025 | CVPR | SALAD | Skeleton-aware latent diffusion for text-driven motion generation and editing | [![link](https://img.shields.io/badge/Website-9cf)](https://seokhyeonhong.github.io/projects/salad/) |  |
| 2025 | ICLR | DART | Diffusion-based autoregressive model for real-time text-driven motion control | [![link](https://img.shields.io/badge/Website-9cf)](https://zkf1997.github.io/DART/) |  |
| 2025 | CVPR | MotionReFit | Dynamic motion blending for versatile motion editing | [![link](https://img.shields.io/badge/Website-9cf)](https://awfuact.github.io/motionrefit/) |  |
| 2024 | ECCV | MotionLCM | Real-time controllable motion generation via a latent consistency model | [![link](https://img.shields.io/badge/Website-9cf)](https://dai-wenxun.github.io/MotionLCM-page/) |  |
| 2024 | CVPR | FlowMDM | Seamless long-motion composition with blended positional encodings | [![link](https://img.shields.io/badge/Website-9cf)](https://barquerogerman.github.io/FlowMDM/) |  |
| 2024 | ECCV | BAMM | Bidirectional autoregressive motion model | [![link](https://img.shields.io/badge/Website-9cf)](https://exitudio.github.io/BAMM-page/) |  |
| 2024 | TPAMI | MotionDiffuse | First diffusion-based text-driven motion framework; probabilistic mapping + fine-grained body-part control | [![link](https://img.shields.io/badge/Website-9cf)](https://mingyuan-zhang.github.io/projects/MotionDiffuse.html) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=mingyuan-zhang/MotionDiffuse)](https://github.com/mingyuan-zhang/MotionDiffuse) |
| 2024 | ICLR | OmniControl | Unified injection of spatiotemporal control signals over arbitrary joints into a diffusion model | [![link](https://img.shields.io/badge/Website-9cf)](https://neu-vi.github.io/omnicontrol/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=neu-vi/OmniControl)](https://github.com/neu-vi/OmniControl) |
| 2024 | ICLR | PriorMDM | Uses a pretrained motion diffusion model as a generative prior for long-sequence / two-person / control tasks | [![link](https://img.shields.io/badge/Website-9cf)](https://priormdm.github.io/priorMDM-page/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=priorMDM/priorMDM)](https://github.com/priorMDM/priorMDM) |
| 2024 | ICLR | GenMoStyle | Generative motion stylization in latent space | [![link](https://img.shields.io/badge/Website-9cf)](https://yxmu.foo/GenMoStyle/) |  |
| 2024 | arXiv | MAS | Multi-view ancestral sampling with 2D diffusion to synthesize 3D motion | [![link](https://img.shields.io/badge/Website-9cf)](https://guytevet.github.io/mas-page/) |  |
| 2023 | ICLR | MDM: Human Motion Diffusion Model | One of the first DDPM-based motion generators; predicts the sample itself + geometric losses; multi-task | [![link](https://img.shields.io/badge/Website-9cf)](https://guytevet.github.io/mdm-page/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=GuyTevet/motion-diffusion-model)](https://github.com/GuyTevet/motion-diffusion-model) |
| 2023 | CVPR | MLD (Motion Latent Diffusion) | Diffusion in the motion latent space for large speed-ups and better quality | [![link](https://img.shields.io/badge/Website-9cf)](https://chenxin.tech/mld/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=ChenFengYe/motion-latent-diffusion)](https://github.com/ChenFengYe/motion-latent-diffusion) |
| 2023 | ICCV | ReMoDiffuse | Retrieval-augmented motion diffusion; retrieved samples improve generalization and fidelity | [![link](https://img.shields.io/badge/Website-9cf)](https://mingyuan-zhang.github.io/projects/ReMoDiffuse.html) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=mingyuan-zhang/ReMoDiffuse)](https://github.com/mingyuan-zhang/ReMoDiffuse) |
| 2023 | ICCV | GMD (Guided Motion Diffusion) | Spatial-constraint guidance (trajectory/obstacle/keyframe) via classifier guidance | [![link](https://img.shields.io/badge/Website-9cf)](https://korrawe.github.io/gmd-project/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=korrawe/guided-motion-diffusion)](https://github.com/korrawe/guided-motion-diffusion) |
| 2023 | ICCV | Fg-T2M | Fine-grained text-to-motion via linguistic-structure parsing + context-aware progressive reasoning |  |  |
| 2023 | ICCV | PhysDiff: Physics-Guided Motion Diffusion | Injects physics-simulation projection into denoising to remove penetration/foot-sliding/floating | [![link](https://img.shields.io/badge/Website-9cf)](https://nvlabs.github.io/PhysDiff/) |  |
| 2023 | AAAI | FLAME | Free-form language-based motion synthesis and editing; a diffusion-based editable framework | [![link](https://img.shields.io/badge/Website-9cf)](https://kakaobrain.github.io/flame/) |  |
| 2023 | NeurIPS | FineMoGen | Spatio-temporally fine-grained, controllable and editable motion generation | [![link](https://img.shields.io/badge/Website-9cf)](https://mingyuan-zhang.github.io/projects/FineMoGen.html) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=mingyuan-zhang/FineMoGen)](https://github.com/mingyuan-zhang/FineMoGen) |

## 3. Music/Audio-to-Motion

| Year | Venue | Method | Problem & Core Idea | Project | GitHub |
| --- | --- | --- | --- | --- | --- |
| 2025 | NeurIPS | MEGADance | Mixture-of-experts architecture for genre-aware 3D dance generation |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=XulongT/MEGADance)](https://github.com/XulongT/MEGADance) |
| 2025 | SIGGRAPH | DuetGen | Music-driven two-person dance via hierarchical masked modeling |  |  |
| 2025 | ICCV | GestureLSM | Latent-shortcut co-speech gesture generation with spatial-temporal modeling | [![link](https://img.shields.io/badge/Website-9cf)](https://andypinxinliu.github.io/GestureLSM/) |  |
| 2025 | ICCV | SemTalk | Holistic co-speech motion generation with frame-level semantic emphasis | [![link](https://img.shields.io/badge/Website-9cf)](https://xiangyuezhang.com/SemTalk/) |  |
| 2025 | ICCV | Align Your Rhythm | Rhythm-aware features to generate highly aligned dance poses | [![link](https://img.shields.io/badge/Website-9cf)](https://danceba.github.io/) |  |
| 2025 | AAAI | UniMuMo | Unified text, music and motion generation | [![link](https://img.shields.io/badge/Website-9cf)](https://hanyangclarence.github.io/unimumo_demo/) |  |
| 2024 | CVPR | EMAGE | Holistic co-speech gesture via expressive masked audio gesture modeling | [![link](https://img.shields.io/badge/Website-9cf)](https://pantomatrix.github.io/EMAGE/) |  |
| 2023 | CVPR | EDGE | Diffusion-based editable dance generation with keyframe/local editing and physical plausibility | [![link](https://img.shields.io/badge/Website-9cf)](https://edge-dance.github.io/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=Stanford-TML/EDGE)](https://github.com/Stanford-TML/EDGE) |
| 2023 | CVPR | TalkSHOW | Generates full-body (face + hands + body) 3D talking motion from speech | [![link](https://img.shields.io/badge/Website-9cf)](https://talkshow.is.tue.mpg.de/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=yhw-yhw/TalkSHOW)](https://github.com/yhw-yhw/TalkSHOW) |
| 2022 | CVPR | Bailando | Motion VQ-VAE memory bank + actor-critic GPT for beat-aligned dance |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=lisiyao21/Bailando)](https://github.com/lisiyao21/Bailando) |
| 2021 | ICCV | AI Choreographer (FACT) | Music-conditioned 3D dance generation + release of the AIST++ dataset | [![link](https://img.shields.io/badge/Website-9cf)](https://google.github.io/aichoreographer/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=google/aistplusplus_api)](https://github.com/google/aistplusplus_api) |

## 4. Human-Object / Scene Interaction

| Year | Venue | Method | Problem & Core Idea | Project | GitHub |
| --- | --- | --- | --- | --- | --- |
| 2026 | CVPR | InterPrior | Scaling generative control for physics-based human-object interactions | [![link](https://img.shields.io/badge/Website-9cf)](https://sirui-xu.github.io/InterPrior/) |  |
| 2025 | CVPR | InterMimic | Universal whole-body control for physics-based human-object interactions | [![link](https://img.shields.io/badge/Website-9cf)](https://sirui-xu.github.io/InterMimic/) |  |
| 2025 | ICCV | TriDi | Trilateral diffusion jointly generating humans, objects and interactions | [![link](https://img.shields.io/badge/Website-9cf)](https://virtualhumans.mpi-inf.mpg.de/tridi/) |  |
| 2025 | CVPR | ChainHOI | Joint-based kinematic-chain modeling for human-object interaction generation |  |  |
| 2025 | CVPR | TokenHSI | Unified physical human-scene interaction synthesis via task tokenization | [![link](https://img.shields.io/badge/Website-9cf)](https://liangpan99.github.io/TokenHSI/) |  |
| 2025 | ICCV | SIMS | Simulating human-scene interactions with real-world script planning |  |  |
| 2025 | ICLR | InterMask | 3D human-human interaction generation via collaborative masked modeling | [![link](https://img.shields.io/badge/Website-9cf)](https://gohar-malik.github.io/intermask) |  |
| 2025 | CVPR | TIMotion | Temporal and interactive framework for efficient human-human motion generation | [![link](https://img.shields.io/badge/Website-9cf)](https://aigc-explorer.github.io/TIMotion-page/) |  |
| 2024 | SIGGRAPH Asia | LINGO | Autonomous character-scene interaction synthesis from text instructions | [![link](https://img.shields.io/badge/Website-9cf)](https://lingomotions.com/) |  |
| 2024 | IJCV | InterGen | Diffusion-based multi-human motion generation under complex interactions | [![link](https://img.shields.io/badge/Website-9cf)](https://tr3e.github.io/intergen-page/) |  |
| 2023 | ICCV | HGHOI | Hierarchical generation of human-object interactions (milestones then infilling) with a diffusion probabilistic model |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=zju3dv/hghoi)](https://github.com/zju3dv/hghoi) |
| 2023 | SIGGRAPH Asia | OMOMO | Object-motion-guided human motion synthesis via conditional diffusion + contact constraints |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=lijiaman/omomo_release)](https://github.com/lijiaman/omomo_release) |
| 2022 | NeurIPS | HUMANISE | Language-conditioned human-scene interaction synthesis + a large-scale dataset | [![link](https://img.shields.io/badge/Website-9cf)](https://silverster98.github.io/HUMANISE/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=Silverster98/HUMANISE)](https://github.com/Silverster98/HUMANISE) |
| 2021 | ICCV | SAMP | Scene-aware motion generation supporting diverse target-object interactions (sit/lie down, etc.) | [![link](https://img.shields.io/badge/Website-9cf)](https://samp.is.tue.mpg.de/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=mohamedhassanmus/SAMP)](https://github.com/mohamedhassanmus/SAMP) |

## 5. Motion Style Transfer

| Year | Venue | Method | Problem & Core Idea | Project | GitHub |
| --- | --- | --- | --- | --- | --- |
| 2025 | ICCV | StyleMotif | Multi-modal motion stylization via style-content cross fusion | [![link](https://img.shields.io/badge/Website-9cf)](https://stylemotif.github.io/) |  |
| 2025 | Arxiv | Dance Like a Chicken | Low-rank stylization for human motion diffusion | [![link](https://img.shields.io/badge/Website-9cf)](https://haimsaw.github.io/LoRA-MDM/) |  |
| 2024 | ECCV | SMooDi | Stylized motion diffusion model | [![link](https://img.shields.io/badge/Website-9cf)](https://neu-vi.github.io/SMooDi/) |  |
| 2024 | CVPR | MCM-LDM | Arbitrary motion style transfer with multi-condition latent diffusion | [![link](https://img.shields.io/badge/Website-9cf)](https://xingliangjin.github.io/MCM-LDM-Web/) |  |
| 2024 | CVPR | MoST | Motion style transformer across diverse action contents | [![link](https://img.shields.io/badge/Website-9cf)](https://boeun-kim.github.io/page-MoST/) |  |
| 2024 | ICLR | GenMoStyle | Generative motion stylization in latent space with reference-free style sampling | [![link](https://img.shields.io/badge/Website-9cf)](https://yxmu.foo/GenMoStyle/) |  |
| 2022 | TOG | Motion Puzzle | Per-body-part style transfer, enabling local composition of different styles |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=DK-Jang/motion_puzzle)](https://github.com/DK-Jang/motion_puzzle) |
| 2020 | SIGGRAPH (TOG) | Aberman et al. | Unpaired motion style transfer via a temporal network with content/style disentanglement | [![link](https://img.shields.io/badge/Website-9cf)](https://deepmotionediting.github.io/style_transfer) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=DeepMotionEditing/deep-motion-editing)](https://github.com/DeepMotionEditing/deep-motion-editing) |

## 6. Motion Retargeting

| Year | Venue | Method | Problem & Core Idea | Project | GitHub |
| --- | --- | --- | --- | --- | --- |
| 2026 | SIGGRAPH | ReActor | Reinforcement learning for physics-aware motion retargeting |  |  |
| 2026 | Arxiv | Skinned Motion Retargeting (SAIG) | Skinned motion retargeting with spatially adaptive interaction guidance |  |  |
| 2023 | CVPR | R2ET | Residual neural retargeting balancing fidelity and penetration avoidance |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=Kebii/R2ET)](https://github.com/Kebii/R2ET) |
| 2020 | SIGGRAPH (TOG) | Skeleton-Aware Networks | Skeleton-aware operators for retargeting across different skeleton topologies | [![link](https://img.shields.io/badge/Website-9cf)](https://deepmotionediting.github.io/retargeting) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=DeepMotionEditing/deep-motion-editing)](https://github.com/DeepMotionEditing/deep-motion-editing) |
| 2018 | CVPR | NKN (Neural Kinematic Networks) | Unsupervised cross-skeleton retargeting with cycle consistency |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=rubenvillegas/cvpr2018nkn)](https://github.com/rubenvillegas/cvpr2018nkn) |

## 7. Physics-based Simulation & Control

| Year | Venue | Method | Problem & Core Idea | Project | GitHub |
| --- | --- | --- | --- | --- | --- |
| 2026 | SIGGRAPH | MotionBricks | Real-time motions via a modular latent generative model with smart primitives |  |  |
| 2025 | ICLR | CLoSD | Closing the loop between simulation and diffusion for multi-task character control | [![link](https://img.shields.io/badge/Website-9cf)](https://guytevet.github.io/CLoSD-page/) |  |
| 2025 | ICCV | PRIMAL | A physically reactive and interactive motor model for avatar learning | [![link](https://img.shields.io/badge/Website-9cf)](https://yz-cnsdqz.github.io/eigenmotion/PRIMAL/) |  |
| 2025 | SIGGRAPH | SkillMimic-v2 | Robust, generalizable interaction skills from sparse and noisy demonstrations |  |  |
| 2025 | CVPR | SkillMimic | Learning reusable basketball skills from demonstrations | [![link](https://img.shields.io/badge/Website-9cf)](https://ingrid789.github.io/SkillMimic/) |  |
| 2024 | SIGGRAPH | SuperPADL | Scaling language-directed physics-based control via progressive supervised distillation |  |  |
| 2023 | ICCV | PhysDiff | Physics-guided motion diffusion; see Section 2 | [![link](https://img.shields.io/badge/Website-9cf)](https://nvlabs.github.io/PhysDiff/) |  |
| 2022 | SIGGRAPH (TOG) | ASE | Large-scale unsupervised skill embeddings; learns a reusable library of physics-based character skills | [![link](https://img.shields.io/badge/Website-9cf)](https://xbpeng.github.io/projects/ASE/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=nv-tlabs/ASE)](https://github.com/nv-tlabs/ASE) |
| 2021 | SIGGRAPH (TOG) | AMP | Adversarial motion priors; a discriminator replaces hand-crafted rewards to shape natural style | [![link](https://img.shields.io/badge/Website-9cf)](https://xbpeng.github.io/projects/AMP/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=xbpeng/DeepMimic)](https://github.com/xbpeng/DeepMimic) |
| 2018 | SIGGRAPH (TOG) | DeepMimic | RL imitation of reference motion to learn robust physics-based character control | [![link](https://img.shields.io/badge/Website-9cf)](https://xbpeng.github.io/projects/DeepMimic/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=xbpeng/DeepMimic)](https://github.com/xbpeng/DeepMimic) |

## 8. Human Motion Prediction

| Year | Venue | Method | Problem & Core Idea | Project | GitHub |
| --- | --- | --- | --- | --- | --- |
| 2025 | CVPR | GORP | Real-time motion generation from sparse signals via rolling prediction models | [![link](https://img.shields.io/badge/Website-9cf)](https://shape-move.github.io/) |  |
| 2024 | NeurIPS | DiMoP3D | Scene-responsive diverse human motion prediction | [![link](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/dimop3d) |  |
| 2024 | ECCV | CoMusion | Consistent stochastic human motion prediction via motion diffusion |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=jsun57/CoMusion)](https://github.com/jsun57/CoMusion) |
| 2023 | ICCV | HumanMAC | Diffusion-based prediction from a masked-completion perspective; end-to-end with a single loss | [![link](https://img.shields.io/badge/Website-9cf)](https://lhchen.top/Human-MAC/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=LinghaoChan/HumanMAC)](https://github.com/LinghaoChan/HumanMAC) |
| 2023 | CVPR | BeLFusion | Latent behavior-disentangled diffusion prediction balancing diversity and realism | [![link](https://img.shields.io/badge/Website-9cf)](https://barquerogerman.github.io/BeLFusion/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=BarqueroGerman/BeLFusion)](https://github.com/BarqueroGerman/BeLFusion) |
| 2020 | ECCV | DLow | Diverse latent-space sampling to improve diversity of future motion prediction | [![link](https://img.shields.io/badge/Website-9cf)](https://www.ye-yuan.com/dlow) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=Khrylx/DLow)](https://github.com/Khrylx/DLow) |

## 9. Datasets

| Year | Venue | Dataset | Content & Scale | Project | GitHub |
| --- | --- | --- | --- | --- | --- |
| 2025 | Arxiv | Motion-X++ | Large-scale multimodal whole-body human motion dataset (upgraded) |  |  |
| 2025 | CVPR | InterAct | Large-scale, versatile 3D human-object interaction generation data |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=wzyabcas/InterAct)](https://github.com/wzyabcas/InterAct) |
| 2025 | CVPR | CORE4D | 4D human-object-human collaborative rearrangement interaction dataset | [![link](https://img.shields.io/badge/Website-9cf)](https://core4d.github.io/) |  |
| 2025 | ICLR | MotionCritic | Aligning human motion generation with human perceptions | [![link](https://img.shields.io/badge/Website-9cf)](https://motioncritic.github.io/) |  |
| 2025 | Arxiv | Embody 3D | Large-scale multimodal motion and behavior dataset |  |  |
| 2024 | ECCV | Nymeria | Massive multimodal egocentric daily motion in the wild | [![link](https://img.shields.io/badge/Website-9cf)](https://www.projectaria.com/datasets/nymeria) |  |
| 2024 | CVPR | Inter-X | Versatile human-human interaction analysis dataset | [![link](https://img.shields.io/badge/Website-9cf)](https://liangxuy.github.io/inter-x/) |  |
| 2023 | NeurIPS | Motion-X | Large-scale whole-body expressive motion + text dataset, 15.6M frames | [![link](https://img.shields.io/badge/Website-9cf)](https://motion-x-dataset.github.io/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=IDEA-Research/Motion-X)](https://github.com/IDEA-Research/Motion-X) |
| 2022 | CVPR | HumanML3D | Text-motion paired dataset, 14,616 motions / 44,970 texts |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=EricGuo5513/HumanML3D)](https://github.com/EricGuo5513/HumanML3D) |
| 2021 | ICCV | AIST++ | 3D dance motion reconstructed from AIST, paired with music | [![link](https://img.shields.io/badge/Website-9cf)](https://google.github.io/aistplusplus_dataset/) |  |
| 2021 | CVPR | BABEL | Per-frame / per-sequence semantic action labels for AMASS | [![link](https://img.shields.io/badge/Website-9cf)](https://babel.is.tue.mpg.de/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=abhinanda-punnakkal/BABEL)](https://github.com/abhinanda-punnakkal/BABEL) |
| 2019 | ICCV | AMASS | Large-scale mocap collection unified to SMPL, >40h, 300+ subjects | [![link](https://img.shields.io/badge/Website-9cf)](https://amass.is.tue.mpg.de/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=nghorbani/amass)](https://github.com/nghorbani/amass) |

## 10. Representation & Foundation Models

| Year | Venue | Method | Problem & Core Idea | Project | GitHub |
| --- | --- | --- | --- | --- | --- |
| 2025 | ICCV | PUMPS | Skeleton-agnostic point-based universal motion pre-training |  |  |
| 2025 | CVPR | UniPose | Unified multimodal framework for pose comprehension, generation and editing | [![link](https://img.shields.io/badge/Website-9cf)](https://liyiheng23.github.io/UniPose-Page/) |  |
| 2025 | Arxiv | SMPLest-X | Ultimate scaling for expressive human pose and shape estimation | [![link](https://img.shields.io/badge/Website-9cf)](https://caizhongang.com/projects/SMPLer-X/) |  |
| 2024 | ECCV | Sapiens | Foundation models for human vision | [![link](https://img.shields.io/badge/Website-9cf)](https://www.meta.com/emerging-tech/codec-avatars/sapiens/) |  |
| 2024 | Arxiv | MotionLLM | Understanding human behaviors jointly from motions and videos | [![link](https://img.shields.io/badge/Website-9cf)](https://lhchen.top/MotionLLM/) |  |
| 2020 | ECCV | VIBE / mocap family | Temporal human reconstruction regressing SMPL from video (reference) |  | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=mkocabas/VIBE)](https://github.com/mkocabas/VIBE) |
| 2019 | CVPR | SMPL-X | Expressive whole-body model (body + hands + face) + VPoser pose prior | [![link](https://img.shields.io/badge/Website-9cf)](https://smpl-x.is.tue.mpg.de/) | [![GitHub](https://api.infinitescript.com/badgen/github?color=ff8800&repo=vchoutas/smplx)](https://github.com/vchoutas/smplx) |
| 2015 | SIGGRAPH Asia (TOG) | SMPL | Linear blend-skinning parametric human body model (shape + pose blendshapes) | [![link](https://img.shields.io/badge/Website-9cf)](https://smpl.is.tue.mpg.de/) |  |

---

## Changelog

- **2026-08-08**: Restructured into categorized tables; added key and recent works across Text-to-Motion / Diffusion / Music-driven / Interaction / Style / Retargeting / Physics / Prediction / Datasets / Representation.
- **2026-08-08**: Referencing [Foruck/Awesome-Human-Motion](https://github.com/Foruck/Awesome-Human-Motion), added a curated set of ~67 notable 2024–2026 top-venue / landmark works.
- **2026-08-08**: Replaced all title-generated arXiv search links for the newly added entries with direct paper/project/code links, sourced from [Foruck/Awesome-Human-Motion](https://github.com/Foruck/Awesome-Human-Motion).

## Contributing

Contributions of new papers via PR / Issue are welcome. Please follow this format: `Year | Venue | Method | one-line core idea | paper/code/project links`.
