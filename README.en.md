# Awesome 3D Human Motion Papers

**语言 / Language:** [简体中文](README.md) | [**English**](README.en.md)

> A curated collection of papers / code / project demos on **3D Human Motion** over the years, covering motion generation, text/music-driven synthesis, human-object/scene interaction, style transfer, retargeting, physics-based simulation, motion prediction, datasets, and representations.
>
> Table fields: **Year | Venue | Method | Problem & Core Idea | Links**.
>
> This list is **updated regularly** for easy reference. Contributions and corrections are welcome.
>
> Some recent entries are adapted from [Foruck/Awesome-Human-Motion](https://github.com/Foruck/Awesome-Human-Motion). Links marked `[arxiv]` are **arXiv search links generated from the title** (they take you to the paper on arXiv) and have not yet been replaced with direct links.

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
| 2026 | CVPR | Next-Scale AR | Next-scale autoregressive prediction for text-to-motion generation | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=Next-Scale+Autoregressive+Text-to-Motion+Generation) |
| 2026 | CVPR | LaMoGen | LLM-guided symbolic inference mapping language to motion | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=LaMoGen+Language+Motion+LLM+Symbolic+Inference) |
| 2025 | ICML | Being-M0 | Scaling motion generation models with million-level human motions | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=Being-M0+Scaling+Motion+Generation+Million-Level) |
| 2025 | ICCV | GENMO | A generalist model unifying generation, reconstruction and forecasting | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=GENMO+Generalist+Model+Human+Motion) |
| 2025 | CVPR | MARDM | Rethinking diffusion for text-driven motion (masked autoregressive diffusion) | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=MARDM+Rethinking+Diffusion+Text-Driven+Human+Motion) |
| 2025 | CVPR | ScaMo | Exploring the scaling law in autoregressive motion generation | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=ScaMo+Scaling+Law+Autoregressive+Motion+Generation) |
| 2025 | ICLR | LaMP | Language-motion pretraining for generation, retrieval and captioning | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=LaMP+Language-Motion+Pretraining) |
| 2025 | ICLR | Motion-Agent | A conversational framework for human motion generation with LLMs | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=Motion-Agent+Conversational+Framework+LLM+Motion) |
| 2025 | IJCV | Fg-T2M++ | LLM-augmented fine-grained text-driven motion generation | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=Fg-T2M+++LLMs+Fine-Grained+Text+Motion+Generation) |
| 2025 | Arxiv | Motion-R1 | Chain-of-thought reasoning + RL for motion generation | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=Motion-R1+Chain-of-Thought+Reinforcement+Learning+Motion) |
| 2025 | Arxiv | MotionGPT3 | Treating human motion as a second modality in a unified model | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=MotionGPT3+Human+Motion+Second+Modality) |
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
| 2025 | ICCV | MotionLab | Unifies motion generation and editing via the Motion-Condition-Motion paradigm | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=MotionLab+Motion-Condition-Motion+Generation+Editing) |
| 2025 | ICCV | MotionStreamer | Streaming motion generation via diffusion-based autoregression in causal latent space | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=MotionStreamer+Streaming+Diffusion+Autoregressive+Causal+Latent) |
| 2025 | ICCV | ControlMM | Controllable masked motion generation | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=ControlMM+Controllable+Masked+Motion+Generation) |
| 2025 | ICCV | Less Is More | Improving motion diffusion models with sparse keyframes | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=Less+Is+More+Sparse+Keyframes+Motion+Diffusion) |
| 2025 | CVPR | EnergyMoGen | Compositional motion generation with energy-based diffusion in latent space | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=EnergyMoGen+Compositional+Energy-Based+Diffusion+Motion) |
| 2025 | CVPR | SALAD | Skeleton-aware latent diffusion for text-driven motion generation and editing | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=SALAD+Skeleton-aware+Latent+Diffusion+Motion+Editing) |
| 2025 | ICLR | DART | Diffusion-based autoregressive model for real-time text-driven motion control | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=DART+Diffusion+Autoregressive+Real-Time+Text-Driven+Motion) |
| 2025 | CVPR | MotionReFit | Dynamic motion blending for versatile motion editing | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=MotionReFit+Dynamic+Motion+Blending+Editing) |
| 2024 | ECCV | MotionLCM | Real-time controllable motion generation via a latent consistency model | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=MotionLCM+Real-time+Controllable+Latent+Consistency+Motion) |
| 2024 | CVPR | FlowMDM | Seamless long-motion composition with blended positional encodings | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=FlowMDM+Seamless+Human+Motion+Composition+Positional) |
| 2024 | ECCV | BAMM | Bidirectional autoregressive motion model | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=BAMM+Bidirectional+Autoregressive+Motion+Model) |
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
| 2025 | NeurIPS | MEGADance | Mixture-of-experts architecture for genre-aware 3D dance generation | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=MEGADance+Mixture-of-experts+genre+dance+generation) |
| 2025 | SIGGRAPH | DuetGen | Music-driven two-person dance via hierarchical masked modeling | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=DuetGen+Music+Two-Person+Dance+Masked+Modeling) |
| 2025 | ICCV | GestureLSM | Latent-shortcut co-speech gesture generation with spatial-temporal modeling | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=GestureLSM+Co-Speech+Gesture+Spatial-Temporal+Shortcut) |
| 2025 | ICCV | SemTalk | Holistic co-speech motion generation with frame-level semantic emphasis | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=SemTalk+Holistic+Co-speech+Motion+Semantic+Emphasis) |
| 2025 | ICCV | Align Your Rhythm | Rhythm-aware features to generate highly aligned dance poses | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=Align+Your+Rhythm+Dance+Rhythm-Aware+Feature) |
| 2025 | AAAI | UniMuMo | Unified text, music and motion generation | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=UniMuMo+Unified+Text+Music+Motion+Generation) |
| 2024 | CVPR | EMAGE | Holistic co-speech gesture via expressive masked audio gesture modeling | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=EMAGE+Holistic+Co-Speech+Gesture+Masked+Audio) |
| 2023 | CVPR | EDGE | Diffusion-based editable dance generation with keyframe/local editing and physical plausibility | [[project]](https://edge-dance.github.io/) [[code]](https://github.com/Stanford-TML/EDGE) |
| 2023 | CVPR | TalkSHOW | Generates full-body (face + hands + body) 3D talking motion from speech | [[project]](https://talkshow.is.tue.mpg.de/) [[code]](https://github.com/yhw-yhw/TalkSHOW) |
| 2022 | CVPR | Bailando | Motion VQ-VAE memory bank + actor-critic GPT for beat-aligned dance | [[paper]](https://arxiv.org/abs/2203.13055) [[code]](https://github.com/lisiyao21/Bailando) |
| 2021 | ICCV | AI Choreographer (FACT) | Music-conditioned 3D dance generation + release of the AIST++ dataset | [[project]](https://google.github.io/aichoreographer/) [[code]](https://github.com/google/aistplusplus_api) |

## 4. Human-Object / Scene Interaction

| Year | Venue | Method | Problem & Core Idea | Links |
| --- | --- | --- | --- | --- |
| 2026 | CVPR | InterPrior | Scaling generative control for physics-based human-object interactions | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=InterPrior+Physics-Based+Human-Object+Interactions+Generative) |
| 2025 | CVPR | InterMimic | Universal whole-body control for physics-based human-object interactions | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=InterMimic+Whole-Body+Physics-Based+Human-Object+Interactions) |
| 2025 | ICCV | TriDi | Trilateral diffusion jointly generating humans, objects and interactions | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=TriDi+Trilateral+Diffusion+Humans+Objects+Interactions) |
| 2025 | CVPR | ChainHOI | Joint-based kinematic-chain modeling for human-object interaction generation | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=ChainHOI+Kinematic+Chain+Human-Object+Interaction) |
| 2025 | CVPR | TokenHSI | Unified physical human-scene interaction synthesis via task tokenization | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=TokenHSI+Physical+Human-Scene+Interactions+Task+Tokenization) |
| 2025 | ICCV | SIMS | Simulating human-scene interactions with real-world script planning | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=SIMS+Simulating+Human-Scene+Interactions+Script+Planning) |
| 2025 | ICLR | InterMask | 3D human-human interaction generation via collaborative masked modeling | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=InterMask+3D+Human+Interaction+Collaborative+Masked) |
| 2025 | CVPR | TIMotion | Temporal and interactive framework for efficient human-human motion generation | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=TIMotion+Temporal+Interactive+Human-Human+Motion) |
| 2024 | SIGGRAPH Asia | LINGO | Autonomous character-scene interaction synthesis from text instructions | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=LINGO+Character-Scene+Interaction+Synthesis+Text+Instruction) |
| 2024 | IJCV | InterGen | Diffusion-based multi-human motion generation under complex interactions | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=InterGen+Diffusion+Multi-human+Motion+Interactions) |
| 2023 | ICCV | HGHOI | Hierarchical generation of human-object interactions (milestones then infilling) with a diffusion probabilistic model | [[paper]](https://zju3dv.github.io/hghoi/files/paper.pdf) [[code]](https://github.com/zju3dv/hghoi) |
| 2023 | SIGGRAPH Asia | OMOMO | Object-motion-guided human motion synthesis via conditional diffusion + contact constraints | [[paper]](https://arxiv.org/abs/2309.16237) [[code]](https://github.com/lijiaman/omomo_release) |
| 2022 | NeurIPS | HUMANISE | Language-conditioned human-scene interaction synthesis + a large-scale dataset | [[project]](https://silverster98.github.io/HUMANISE/) [[code]](https://github.com/Silverster98/HUMANISE) |
| 2021 | ICCV | SAMP | Scene-aware motion generation supporting diverse target-object interactions (sit/lie down, etc.) | [[project]](https://samp.is.tue.mpg.de/) [[code]](https://github.com/mohamedhassanmus/SAMP) |

## 5. Motion Style Transfer

| Year | Venue | Method | Problem & Core Idea | Links |
| --- | --- | --- | --- | --- |
| 2025 | ICCV | StyleMotif | Multi-modal motion stylization via style-content cross fusion | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=StyleMotif+Multi-Modal+Motion+Stylization+Style-Content) |
| 2025 | Arxiv | Dance Like a Chicken | Low-rank stylization for human motion diffusion | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=Dance+Like+a+Chicken+Low-Rank+Stylization+Motion+Diffusion) |
| 2024 | ECCV | SMooDi | Stylized motion diffusion model | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=SMooDi+Stylized+Motion+Diffusion+Model) |
| 2024 | CVPR | MCM-LDM | Arbitrary motion style transfer with multi-condition latent diffusion | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=MCM-LDM+Arbitrary+Motion+Style+Transfer+Latent+Diffusion) |
| 2024 | CVPR | MoST | Motion style transformer across diverse action contents | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=MoST+Motion+Style+Transformer+Diverse+Action) |
| 2024 | ICLR | GenMoStyle | Generative motion stylization in latent space with reference-free style sampling | [[project]](https://yxmu.foo/GenMoStyle/) |
| 2022 | TOG | Motion Puzzle | Per-body-part style transfer, enabling local composition of different styles | [[paper]](https://arxiv.org/abs/2202.05274) [[code]](https://github.com/DK-Jang/motion_puzzle) |
| 2020 | SIGGRAPH (TOG) | Aberman et al. | Unpaired motion style transfer via a temporal network with content/style disentanglement | [[project]](https://deepmotionediting.github.io/style_transfer) [[code]](https://github.com/DeepMotionEditing/deep-motion-editing) |

## 6. Motion Retargeting

| Year | Venue | Method | Problem & Core Idea | Links |
| --- | --- | --- | --- | --- |
| 2026 | SIGGRAPH | ReActor | Reinforcement learning for physics-aware motion retargeting | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=ReActor+Reinforcement+Learning+Physics-Aware+Motion+Retargeting) |
| 2026 | Arxiv | Skinned Motion Retargeting (SAIG) | Skinned motion retargeting with spatially adaptive interaction guidance | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=Skinned+Motion+Retargeting+Spatially+Adaptive+Interaction+Guidance) |
| 2023 | CVPR | R2ET | Residual neural retargeting balancing fidelity and penetration avoidance | [[paper]](https://arxiv.org/abs/2303.11951) [[code]](https://github.com/Kebii/R2ET) |
| 2020 | SIGGRAPH (TOG) | Skeleton-Aware Networks | Skeleton-aware operators for retargeting across different skeleton topologies | [[project]](https://deepmotionediting.github.io/retargeting) [[code]](https://github.com/DeepMotionEditing/deep-motion-editing) |
| 2018 | CVPR | NKN (Neural Kinematic Networks) | Unsupervised cross-skeleton retargeting with cycle consistency | [[paper]](https://arxiv.org/abs/1804.05653) [[code]](https://github.com/rubenvillegas/cvpr2018nkn) |

## 7. Physics-based Simulation & Control

| Year | Venue | Method | Problem & Core Idea | Links |
| --- | --- | --- | --- | --- |
| 2026 | SIGGRAPH | MotionBricks | Real-time motions via a modular latent generative model with smart primitives | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=MotionBricks+Real-Time+Modular+Latent+Generative+Model) |
| 2025 | ICLR | CLoSD | Closing the loop between simulation and diffusion for multi-task character control | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=CLoSD+Closing+Loop+Simulation+Diffusion+Character+Control) |
| 2025 | ICCV | PRIMAL | A physically reactive and interactive motor model for avatar learning | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=PRIMAL+Physically+Reactive+Interactive+Motor+Avatar) |
| 2025 | SIGGRAPH | SkillMimic-v2 | Robust, generalizable interaction skills from sparse and noisy demonstrations | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=SkillMimic-v2+Robust+Generalizable+Interaction+Skills+Demonstrations) |
| 2025 | CVPR | SkillMimic | Learning reusable basketball skills from demonstrations | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=SkillMimic+Reusable+Basketball+Skills+Demonstrations) |
| 2024 | SIGGRAPH | SuperPADL | Scaling language-directed physics-based control via progressive supervised distillation | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=SuperPADL+Language-Directed+Physics-Based+Control+Distillation) |
| 2023 | ICCV | PhysDiff | Physics-guided motion diffusion; see Section 2 | [[project]](https://nvlabs.github.io/PhysDiff/) |
| 2022 | SIGGRAPH (TOG) | ASE | Large-scale unsupervised skill embeddings; learns a reusable library of physics-based character skills | [[project]](https://xbpeng.github.io/projects/ASE/) [[code]](https://github.com/nv-tlabs/ASE) |
| 2021 | SIGGRAPH (TOG) | AMP | Adversarial motion priors; a discriminator replaces hand-crafted rewards to shape natural style | [[project]](https://xbpeng.github.io/projects/AMP/) [[code]](https://github.com/xbpeng/DeepMimic) |
| 2018 | SIGGRAPH (TOG) | DeepMimic | RL imitation of reference motion to learn robust physics-based character control | [[project]](https://xbpeng.github.io/projects/DeepMimic/) [[code]](https://github.com/xbpeng/DeepMimic) |

## 8. Human Motion Prediction

| Year | Venue | Method | Problem & Core Idea | Links |
| --- | --- | --- | --- | --- |
| 2025 | CVPR | GORP | Real-time motion generation from sparse signals via rolling prediction models | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=Rolling+Prediction+Models+Real-Time+Motion+Sparse+Signal) |
| 2024 | NeurIPS | DiMoP3D | Scene-responsive diverse human motion prediction | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=DiMoP3D+Scene-responsive+Diverse+Human+Motion+Prediction) |
| 2024 | ECCV | CoMusion | Consistent stochastic human motion prediction via motion diffusion | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=CoMusion+Consistent+Stochastic+Human+Motion+Prediction+Diffusion) |
| 2023 | ICCV | HumanMAC | Diffusion-based prediction from a masked-completion perspective; end-to-end with a single loss | [[project]](https://lhchen.top/Human-MAC/) [[code]](https://github.com/LinghaoChan/HumanMAC) |
| 2023 | CVPR | BeLFusion | Latent behavior-disentangled diffusion prediction balancing diversity and realism | [[project]](https://barquerogerman.github.io/BeLFusion/) [[code]](https://github.com/BarqueroGerman/BeLFusion) |
| 2020 | ECCV | DLow | Diverse latent-space sampling to improve diversity of future motion prediction | [[project]](https://www.ye-yuan.com/dlow) [[code]](https://github.com/Khrylx/DLow) |

## 9. Datasets

| Year | Venue | Dataset | Content & Scale | Links |
| --- | --- | --- | --- | --- |
| 2025 | Arxiv | Motion-X++ | Large-scale multimodal whole-body human motion dataset (upgraded) | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=Motion-X+++Large-Scale+Multimodal+Whole-body+Motion+Dataset) |
| 2025 | CVPR | InterAct | Large-scale, versatile 3D human-object interaction generation data | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=InterAct+Large-Scale+Versatile+3D+Human-Object+Interaction) |
| 2025 | CVPR | CORE4D | 4D human-object-human collaborative rearrangement interaction dataset | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=CORE4D+4D+Human-Object-Human+Interaction+Collaborative+Rearrangement) |
| 2025 | ICLR | MotionCritic | Aligning human motion generation with human perceptions | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=MotionCritic+Aligning+Human+Motion+Generation+Perceptions) |
| 2025 | Arxiv | Embody 3D | Large-scale multimodal motion and behavior dataset | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=Embody+3D+Large-scale+Multimodal+Motion+Behavior+Dataset) |
| 2024 | ECCV | Nymeria | Massive multimodal egocentric daily motion in the wild | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=Nymeria+multimodal+egocentric+daily+motion+wild) |
| 2024 | CVPR | Inter-X | Versatile human-human interaction analysis dataset | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=Inter-X+Versatile+Human-Human+Interaction+Analysis) |
| 2023 | NeurIPS | Motion-X | Large-scale whole-body expressive motion + text dataset, 15.6M frames | [[project]](https://motion-x-dataset.github.io/) [[code]](https://github.com/IDEA-Research/Motion-X) |
| 2022 | CVPR | HumanML3D | Text-motion paired dataset, 14,616 motions / 44,970 texts | [[code]](https://github.com/EricGuo5513/HumanML3D) |
| 2021 | ICCV | AIST++ | 3D dance motion reconstructed from AIST, paired with music | [[project]](https://google.github.io/aistplusplus_dataset/) |
| 2021 | CVPR | BABEL | Per-frame / per-sequence semantic action labels for AMASS | [[project]](https://babel.is.tue.mpg.de/) [[code]](https://github.com/abhinanda-punnakkal/BABEL) |
| 2019 | ICCV | AMASS | Large-scale mocap collection unified to SMPL, >40h, 300+ subjects | [[project]](https://amass.is.tue.mpg.de/) [[code]](https://github.com/nghorbani/amass) |

## 10. Representation & Foundation Models

| Year | Venue | Method | Problem & Core Idea | Links |
| --- | --- | --- | --- | --- |
| 2025 | ICCV | PUMPS | Skeleton-agnostic point-based universal motion pre-training | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=PUMPS+Skeleton-Agnostic+Point-based+Universal+Motion+Pre-Training) |
| 2025 | CVPR | UniPose | Unified multimodal framework for pose comprehension, generation and editing | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=UniPose+Unified+Multimodal+Pose+Comprehension+Generation+Editing) |
| 2025 | Arxiv | SMPLest-X | Ultimate scaling for expressive human pose and shape estimation | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=SMPLest-X+Scaling+Expressive+Human+Pose+Shape+Estimation) |
| 2024 | ECCV | Sapiens | Foundation models for human vision | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=Sapiens+Foundation+Human+Vision+Models) |
| 2024 | Arxiv | MotionLLM | Understanding human behaviors jointly from motions and videos | [[arxiv]](https://arxiv.org/search/?searchtype=all&query=MotionLLM+Understanding+Human+Behaviors+Motions+Videos) |
| 2020 | ECCV | VIBE / mocap family | Temporal human reconstruction regressing SMPL from video (reference) | [[code]](https://github.com/mkocabas/VIBE) |
| 2019 | CVPR | SMPL-X | Expressive whole-body model (body + hands + face) + VPoser pose prior | [[project]](https://smpl-x.is.tue.mpg.de/) [[code]](https://github.com/vchoutas/smplx) |
| 2015 | SIGGRAPH Asia (TOG) | SMPL | Linear blend-skinning parametric human body model (shape + pose blendshapes) | [[project]](https://smpl.is.tue.mpg.de/) |

---

## Changelog

- **2026-08-08**: Restructured into categorized tables; added key and recent works across Text-to-Motion / Diffusion / Music-driven / Interaction / Style / Retargeting / Physics / Prediction / Datasets / Representation.
- **2026-08-08**: Referencing [Foruck/Awesome-Human-Motion](https://github.com/Foruck/Awesome-Human-Motion), added a curated set of ~67 notable 2024–2026 top-venue / landmark works (links currently use title-generated arXiv search links, to be replaced with direct links over time).

## Contributing

Contributions of new papers via PR / Issue are welcome. Please follow this format: `Year | Venue | Method | one-line core idea | paper/code/project links`.
