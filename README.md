# Awesome 3D Human Motion 论文列表

**语言 / Language:** [**简体中文**](README.md) | [English](README.en.md)

> 系统搜集与整理历年 **3D 人体动作(3D Human Motion)** 相关的论文 / 代码 / Project Demo,涵盖动作生成、文本/音乐驱动、人-物/人-场景交互、风格迁移、动作重定向、物理仿真、动作预测、数据集与表征等方向。
>
> 表格字段:**年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 链接**。
>
> 本列表会根据时间**定期更新**,方便查阅参考。欢迎补充与勘误。
>
> 部分近年条目参考自 [Foruck/Awesome-Human-Motion](https://github.com/Foruck/Awesome-Human-Motion),其中新增条目的 `[paper]` / `[project]` / `[code]` 链接均取自该项目。

---

## 目录

- [1. 文本驱动动作生成 (Text-to-Motion)](#1-文本驱动动作生成-text-to-motion)
- [2. 动作扩散与可控生成 (Diffusion & Controllable)](#2-动作扩散与可控生成-diffusion--controllable)
- [3. 音乐/音频驱动动作 (Music/Audio-to-Motion)](#3-音乐音频驱动动作-musicaudio-to-motion)
- [4. 人-物 / 人-场景交互 (Human-Object / Scene Interaction)](#4-人-物--人-场景交互-human-object--scene-interaction)
- [5. 动作风格迁移 (Motion Style Transfer)](#5-动作风格迁移-motion-style-transfer)
- [6. 动作重定向 (Motion Retargeting)](#6-动作重定向-motion-retargeting)
- [7. 物理仿真与角色控制 (Physics-based & Control)](#7-物理仿真与角色控制-physics-based--control)
- [8. 动作预测 (Human Motion Prediction)](#8-动作预测-human-motion-prediction)
- [9. 数据集 (Datasets)](#9-数据集-datasets)
- [10. 人体表征与基础模型 (Representation & Foundation)](#10-人体表征与基础模型-representation--foundation)

---

## 1. 文本驱动动作生成 (Text-to-Motion)

| 年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 链接 |
| --- | --- | --- | --- | --- |
| 2026 | CVPR | Next-Scale AR | 下一尺度自回归预测做文本到动作生成 | [[paper]](https://arxiv.org/abs/2604.03799) |
| 2026 | CVPR | LaMoGen | LLM 引导的符号推理,把语言映射为动作 | [[paper]](https://arxiv.org/abs/2603.11605) |
| 2025 | ICML | Being-M0 | 百万级人体动作数据,探索动作生成模型的规模化 | [[paper]](https://arxiv.org/abs/2410.03311) |
| 2025 | ICCV | GENMO | 统一生成/重建/预测的通才人体动作模型 | [[project]](https://research.nvidia.com/labs/dair/genmo/) |
| 2025 | CVPR | MARDM | 重新思考扩散用于文本驱动动作(掩码自回归扩散) | [[paper]](https://arxiv.org/abs/2411.16575) |
| 2025 | CVPR | ScaMo | 探索自回归动作生成模型中的缩放律 | [[project]](https://shunlinlu.github.io/ScaMo/) |
| 2025 | ICLR | LaMP | 语言-动作预训练,服务生成/检索/描述 | [[paper]](https://openreview.net/forum?id=LYawG8YkPa) |
| 2025 | ICLR | Motion-Agent | 基于 LLM 的对话式动作生成框架 | [[project]](https://knoxzhao.github.io/Motion-Agent/) |
| 2025 | IJCV | Fg-T2M++ | LLM 增强的细粒度文本驱动动作生成 | [[paper]](https://arxiv.org/abs/2502.05534) |
| 2025 | Arxiv | Motion-R1 | 思维链推理 + 强化学习做动作生成 | [[project]](https://motion-r1.github.io/) |
| 2025 | Arxiv | MotionGPT3 | 将人体动作作为"第二模态"的统一模型 | [[code]](https://github.com/OpenMotionLab/MotionGPT3) |
| 2024 | CVPR | MoMask | 残差 VQ + 掩码生成式 Transformer,高质量文本到动作 | [[project]](https://ericguo5513.github.io/momask/) [[code]](https://github.com/EricGuo5513/momask-codes) |
| 2023 | NeurIPS | MotionGPT | 将动作视为一种"外语",用统一 LLM 处理多种动作任务 | [[project]](https://motion-gpt.github.io/) [[code]](https://github.com/OpenMotionLab/MotionGPT) |
| 2023 | CVPR | T2M-GPT | VQ-VAE 离散化 + GPT 自回归生成,简单强基线 | [[project]](https://mael-zys.github.io/T2M-GPT/) [[code]](https://github.com/Mael-zys/T2M-GPT) |
| 2022 | ECCV | MotionCLIP | 将动作对齐到 CLIP 文本-图像隐空间,实现语义可控与解耦编辑 | [[paper]](https://arxiv.org/abs/2203.08063) [[code]](https://github.com/GuyTevet/MotionCLIP) |
| 2022 | ECCV | TM2T | 文本↔动作双向映射,motion token 化 + 神经机器翻译框架 | [[project]](https://ericguo5513.github.io/TM2T/) [[code]](https://github.com/EricGuo5513/TM2T) |
| 2022 | ECCV | TEMOS | 基于 Transformer-VAE 的文本条件动作生成,支持多样化采样 | [[project]](https://mathis.petrovich.fr/temos/) [[code]](https://github.com/Mathux/TEMOS) |
| 2022 | CVPR | Guo et al. (HumanML3D) | 首个大规模文本-动作数据集 + 基于时序 VAE 的文本到动作生成 | [[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_Generating_Diverse_and_Natural_3D_Human_Motions_From_Text_CVPR_2022_paper.pdf) [[code]](https://github.com/EricGuo5513/HumanML3D) |

## 2. 动作扩散与可控生成 (Diffusion & Controllable)

| 年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 链接 |
| --- | --- | --- | --- | --- |
| 2025 | ICCV | MotionLab | 用"动作-条件-动作"范式统一动作生成与编辑 | [[project]](https://diouo.github.io/motionlab.github.io/) |
| 2025 | ICCV | MotionStreamer | 因果隐空间中扩散自回归的流式动作生成 | [[project]](https://zju3dv.github.io/MotionStreamer/) |
| 2025 | ICCV | ControlMM | 可控的掩码动作生成 | [[project]](https://www.ekkasit.com/ControlMM-page/) |
| 2025 | ICCV | Less Is More | 用稀疏关键帧改进动作扩散模型 | [[paper]](https://arxiv.org/abs/2503.13859) |
| 2025 | CVPR | EnergyMoGen | 隐空间能量扩散做组合式动作生成 | [[project]](https://jiro-zhang.github.io/EnergyMoGen/) |
| 2025 | CVPR | SALAD | 骨架感知隐扩散做文本动作生成与编辑 | [[project]](https://seokhyeonhong.github.io/projects/salad/) |
| 2025 | ICLR | DART | 扩散自回归模型做实时文本驱动动作控制 | [[project]](https://zkf1997.github.io/DART/) |
| 2025 | CVPR | MotionReFit | 动态动作混合做通用动作编辑 | [[project]](https://awfuact.github.io/motionrefit/) |
| 2024 | ECCV | MotionLCM | 潜在一致性模型做实时可控动作生成 | [[project]](https://dai-wenxun.github.io/MotionLCM-page/) |
| 2024 | CVPR | FlowMDM | 混合位置编码做无缝长动作合成 | [[project]](https://barquerogerman.github.io/FlowMDM/) |
| 2024 | ECCV | BAMM | 双向自回归动作模型 | [[project]](https://exitudio.github.io/BAMM-page/) |
| 2024 | TPAMI | MotionDiffuse | 首个基于扩散的文本驱动动作框架,概率映射 + 细粒度身体部位控制 | [[project]](https://mingyuan-zhang.github.io/projects/MotionDiffuse.html) [[code]](https://github.com/mingyuan-zhang/MotionDiffuse) |
| 2024 | ICLR | OmniControl | 任意关节的时空控制信号统一注入扩散模型 | [[project]](https://neu-vi.github.io/omnicontrol/) [[code]](https://github.com/neu-vi/OmniControl) |
| 2024 | ICLR | PriorMDM | 将预训练动作扩散当作生成先验,做长序列/双人/控制等下游任务 | [[project]](https://priormdm.github.io/priorMDM-page/) [[code]](https://github.com/priorMDM/priorMDM) |
| 2024 | ICLR | GenMoStyle | 隐空间中的生成式动作风格化 | [[project]](https://yxmu.foo/GenMoStyle/) |
| 2024 | Arxiv | MAS | 用 2D 扩散做多视角祖先采样,合成 3D 动作 | [[project]](https://guytevet.github.io/mas-page/) |
| 2023 | ICLR | MDM: Human Motion Diffusion Model | 首批将 DDPM 用于动作生成,预测样本本体 + 几何损失,支持多任务 | [[paper]](https://arxiv.org/abs/2209.14916) [[project]](https://guytevet.github.io/mdm-page/) [[code]](https://github.com/GuyTevet/motion-diffusion-model) |
| 2023 | CVPR | MLD (Motion Latent Diffusion) | 在动作隐空间做扩散,大幅提速并提升质量 | [[project]](https://chenxin.tech/mld/) [[code]](https://github.com/ChenFengYe/motion-latent-diffusion) |
| 2023 | ICCV | ReMoDiffuse | 检索增强的动作扩散,借助检索样本提升泛化与保真 | [[project]](https://mingyuan-zhang.github.io/projects/ReMoDiffuse.html) [[code]](https://github.com/mingyuan-zhang/ReMoDiffuse) |
| 2023 | ICCV | GMD (Guided Motion Diffusion) | 空间约束引导(轨迹/障碍/关键帧),分类器引导注入条件 | [[project]](https://korrawe.github.io/gmd-project/) [[code]](https://github.com/korrawe/guided-motion-diffusion) |
| 2023 | ICCV | Fg-T2M | 细粒度文本到动作,语言结构解析 + 上下文感知渐进推理 | [[paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_Fg-T2M_Fine-Grained_Text-Driven_Human_Motion_Generation_via_Diffusion_Model_ICCV_2023_paper.pdf) |
| 2023 | ICCV | PhysDiff: Physics-Guided Motion Diffusion | 在扩散去噪中加入物理仿真投影,消除穿模/滑步/漂浮 | [[paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Yuan_PhysDiff_Physics-Guided_Human_Motion_Diffusion_Model_ICCV_2023_paper.pdf) [[project]](https://nvlabs.github.io/PhysDiff/) |
| 2023 | AAAI | FLAME | 自由形式语言驱动的动作合成与编辑,基于扩散的可编辑框架 | [[project]](https://kakaobrain.github.io/flame/) |
| 2023 | NeurIPS | FineMoGen | 时空细粒度可控与可编辑的动作生成 | [[project]](https://mingyuan-zhang.github.io/projects/FineMoGen.html) [[code]](https://github.com/mingyuan-zhang/FineMoGen) |

## 3. 音乐/音频驱动动作 (Music/Audio-to-Motion)

| 年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 链接 |
| --- | --- | --- | --- | --- |
| 2025 | NeurIPS | MEGADance | 专家混合(MoE)架构做风格感知 3D 舞蹈生成 | [[code]](https://github.com/XulongT/MEGADance) |
| 2025 | SIGGRAPH | DuetGen | 音乐驱动双人舞蹈的层次掩码建模 | [[paper]](https://arxiv.org/pdf/2506.18680) |
| 2025 | ICCV | GestureLSM | 潜在捷径 + 时空建模的共语手势生成 | [[project]](https://andypinxinliu.github.io/GestureLSM/) |
| 2025 | ICCV | SemTalk | 帧级语义强调的整体共语动作生成 | [[project]](https://xiangyuezhang.com/SemTalk/) |
| 2025 | ICCV | Align Your Rhythm | 节奏感知特征生成高对齐舞姿 | [[project]](https://danceba.github.io/) |
| 2025 | AAAI | UniMuMo | 统一文本 / 音乐 / 动作的联合生成 | [[project]](https://hanyangclarence.github.io/unimumo_demo/) |
| 2024 | CVPR | EMAGE | 表情掩码音频手势建模的整体共语手势生成 | [[project]](https://pantomatrix.github.io/EMAGE/) |
| 2023 | CVPR | EDGE | 基于扩散的可编辑舞蹈生成,支持关键帧/局部编辑与物理合理性 | [[project]](https://edge-dance.github.io/) [[code]](https://github.com/Stanford-TML/EDGE) |
| 2023 | CVPR | TalkSHOW | 从语音生成全身(脸+手+身)3D 说话人动作 | [[project]](https://talkshow.is.tue.mpg.de/) [[code]](https://github.com/yhw-yhw/TalkSHOW) |
| 2022 | CVPR | Bailando | 动作 VQ-VAE 记忆库 + actor-critic GPT,音乐节拍对齐舞蹈 | [[paper]](https://arxiv.org/abs/2203.13055) [[code]](https://github.com/lisiyao21/Bailando) |
| 2021 | ICCV | AI Choreographer (FACT) | 音乐条件 3D 舞蹈生成 + 发布 AIST++ 数据集 | [[project]](https://google.github.io/aichoreographer/) [[code]](https://github.com/google/aistplusplus_api) |

## 4. 人-物 / 人-场景交互 (Human-Object / Scene Interaction)

| 年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 链接 |
| --- | --- | --- | --- | --- |
| 2026 | CVPR | InterPrior | 物理仿真下可扩展的人-物交互生成控制 | [[project]](https://sirui-xu.github.io/InterPrior/) |
| 2025 | CVPR | InterMimic | 面向物理仿真的全身人-物交互通用控制 | [[project]](https://sirui-xu.github.io/InterMimic/) |
| 2025 | ICCV | TriDi | 人/物/交互三边扩散的联合生成 | [[project]](https://virtualhumans.mpi-inf.mpg.de/tridi/) |
| 2025 | CVPR | ChainHOI | 基于关节运动链建模的人-物交互生成 | [[paper]](https://arxiv.org/abs/2503.13130) |
| 2025 | CVPR | TokenHSI | 任务令牌化统一物理人-场景交互合成 | [[project]](https://liangpan99.github.io/TokenHSI/) |
| 2025 | ICCV | SIMS | 结合真实脚本规划模拟人-场景交互 | [[paper]](https://arxiv.org/abs/2411.19921) |
| 2025 | ICLR | InterMask | 协同掩码建模生成 3D 人-人交互 | [[project]](https://gohar-malik.github.io/intermask) |
| 2025 | CVPR | TIMotion | 高效人-人动作生成的时序交互框架 | [[project]](https://aigc-explorer.github.io/TIMotion-page/) |
| 2024 | SIGGRAPH Asia | LINGO | 文本指令驱动的自主角色-场景交互合成 | [[project]](https://lingomotions.com/) |
| 2024 | IJCV | InterGen | 复杂交互下的扩散式多人体动作生成 | [[project]](https://tr3e.github.io/intergen-page/) |
| 2023 | ICCV | HGHOI | 层次化生成人-物交互(先里程碑再补全),扩散概率模型 | [[paper]](https://zju3dv.github.io/hghoi/files/paper.pdf) [[code]](https://github.com/zju3dv/hghoi) |
| 2023 | SIGGRAPH Asia | OMOMO | 物体运动引导的人体动作合成,条件扩散 + 接触约束 | [[paper]](https://arxiv.org/abs/2309.16237) [[code]](https://github.com/lijiaman/omomo_release) |
| 2022 | NeurIPS | HUMANISE | 语言条件的人-场景交互合成 + 大规模数据集 | [[project]](https://silverster98.github.io/HUMANISE/) [[code]](https://github.com/Silverster98/HUMANISE) |
| 2021 | ICCV | SAMP | 场景感知的动作生成,支持多样化目标物体交互(坐/躺等) | [[project]](https://samp.is.tue.mpg.de/) [[code]](https://github.com/mohamedhassanmus/SAMP) |

## 5. 动作风格迁移 (Motion Style Transfer)

| 年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 链接 |
| --- | --- | --- | --- | --- |
| 2025 | ICCV | StyleMotif | 风格-内容交叉融合的多模态动作风格化 | [[project]](https://stylemotif.github.io/) |
| 2025 | Arxiv | Dance Like a Chicken | 低秩风格化用于人体动作扩散 | [[project]](https://haimsaw.github.io/LoRA-MDM/) |
| 2024 | ECCV | SMooDi | 风格化动作扩散模型 | [[project]](https://neu-vi.github.io/SMooDi/) |
| 2024 | CVPR | MCM-LDM | 多条件潜在扩散做任意动作风格迁移 | [[project]](https://xingliangjin.github.io/MCM-LDM-Web/) |
| 2024 | CVPR | MoST | 跨不同动作内容的风格 Transformer | [[project]](https://boeun-kim.github.io/page-MoST/) |
| 2024 | ICLR | GenMoStyle | 在隐空间中做生成式动作风格化,支持无参考风格采样 | [[project]](https://yxmu.foo/GenMoStyle/) |
| 2022 | TOG | Motion Puzzle | 身体各部位独立的风格迁移,可局部拼接不同风格 | [[paper]](https://arxiv.org/abs/2202.05274) [[code]](https://github.com/DK-Jang/motion_puzzle) |
| 2020 | SIGGRAPH (TOG) | Aberman et al. | 无配对数据的动作风格迁移,内容/风格解耦的时序网络 | [[project]](https://deepmotionediting.github.io/style_transfer) [[code]](https://github.com/DeepMotionEditing/deep-motion-editing) |

## 6. 动作重定向 (Motion Retargeting)

| 年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 链接 |
| --- | --- | --- | --- | --- |
| 2026 | SIGGRAPH | ReActor | 强化学习做物理感知的动作重定向 | [[paper]](https://arxiv.org/abs/2605.06593) |
| 2026 | Arxiv | Skinned Motion Retargeting (SAIG) | 空间自适应交互引导的蒙皮动作重定向 | [[paper]](https://arxiv.org/abs/2605.19355) |
| 2023 | CVPR | R2ET | 残差式神经重定向,兼顾保真与穿模避免 | [[paper]](https://arxiv.org/abs/2303.11951) [[code]](https://github.com/Kebii/R2ET) |
| 2020 | SIGGRAPH (TOG) | Skeleton-Aware Networks | 骨架感知算子实现不同骨架拓扑间的动作重定向 | [[project]](https://deepmotionediting.github.io/retargeting) [[code]](https://github.com/DeepMotionEditing/deep-motion-editing) |
| 2018 | CVPR | NKN (Neural Kinematic Networks) | 无监督循环一致性的跨骨架动作重定向 | [[paper]](https://arxiv.org/abs/1804.05653) [[code]](https://github.com/rubenvillegas/cvpr2018nkn) |

## 7. 物理仿真与角色控制 (Physics-based & Control)

| 年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 链接 |
| --- | --- | --- | --- | --- |
| 2026 | SIGGRAPH | MotionBricks | 模块化潜在生成 + 智能基元的实时动作 | [[paper]](https://arxiv.org/abs/2604.24833) |
| 2025 | ICLR | CLoSD | 仿真与扩散闭环做多任务角色控制 | [[project]](https://guytevet.github.io/CLoSD-page/) |
| 2025 | ICCV | PRIMAL | 物理反应式、可交互的化身运动模型 | [[project]](https://yz-cnsdqz.github.io/eigenmotion/PRIMAL/) |
| 2025 | SIGGRAPH | SkillMimic-v2 | 从稀疏含噪示范学鲁棒可泛化的交互技能 | [[paper]](https://arxiv.org/abs/2505.02094) |
| 2025 | CVPR | SkillMimic | 从示范中学习可复用的篮球技能 | [[project]](https://ingrid789.github.io/SkillMimic/) |
| 2024 | SIGGRAPH | SuperPADL | 渐进监督蒸馏扩展语言指令物理控制 | [[paper]](https://arxiv.org/abs/2407.10481) |
| 2023 | ICCV | PhysDiff | 物理引导的动作扩散,详见第 2 节 | [[project]](https://nvlabs.github.io/PhysDiff/) |
| 2022 | SIGGRAPH (TOG) | ASE | 大规模无监督技能嵌入,学习可复用的物理角色技能库 | [[project]](https://xbpeng.github.io/projects/ASE/) [[code]](https://github.com/nv-tlabs/ASE) |
| 2021 | SIGGRAPH (TOG) | AMP | 对抗式动作先验,用判别器替代人工奖励塑造自然风格 | [[project]](https://xbpeng.github.io/projects/AMP/) [[code]](https://github.com/xbpeng/DeepMimic) |
| 2018 | SIGGRAPH (TOG) | DeepMimic | 强化学习模仿参考动作,学出鲁棒的物理角色控制策略 | [[project]](https://xbpeng.github.io/projects/DeepMimic/) [[code]](https://github.com/xbpeng/DeepMimic) |

## 8. 动作预测 (Human Motion Prediction)

| 年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 链接 |
| --- | --- | --- | --- | --- |
| 2025 | CVPR | GORP | 滚动预测模型做稀疏信号到平滑动作的实时生成 | [[project]](https://shape-move.github.io/) |
| 2024 | NeurIPS | DiMoP3D | 场景响应的多样化人体动作预测 | [[project]](https://sites.google.com/view/dimop3d) |
| 2024 | ECCV | CoMusion | 扩散做一致的随机人体动作预测 | [[code]](https://github.com/jsun57/CoMusion) |
| 2023 | ICCV | HumanMAC | 掩码补全视角下的扩散动作预测,单损失端到端 | [[project]](https://lhchen.top/Human-MAC/) [[code]](https://github.com/LinghaoChan/HumanMAC) |
| 2023 | CVPR | BeLFusion | 隐空间行为解耦的扩散预测,兼顾多样与真实 | [[project]](https://barquerogerman.github.io/BeLFusion/) [[code]](https://github.com/BarqueroGerman/BeLFusion) |
| 2020 | ECCV | DLow | 多样化隐空间采样,提升未来动作预测的多样性 | [[project]](https://www.ye-yuan.com/dlow) [[code]](https://github.com/Khrylx/DLow) |

## 9. 数据集 (Datasets)

| 年份 | 会议/期刊 | 数据集 | 内容与规模 | 链接 |
| --- | --- | --- | --- | --- |
| 2025 | Arxiv | Motion-X++ | 大规模多模态全身人体动作数据集(升级版) | [[paper]](https://arxiv.org/abs/2501.05098) |
| 2025 | CVPR | InterAct | 大规模、多样化的 3D 人-物交互生成数据 | [[code]](https://github.com/wzyabcas/InterAct) |
| 2025 | CVPR | CORE4D | 4D 人-物-人协作重排交互数据集 | [[project]](https://core4d.github.io/) |
| 2025 | ICLR | MotionCritic | 对齐动作生成与人类感知的评测模型 | [[project]](https://motioncritic.github.io/) |
| 2025 | Arxiv | Embody 3D | 大规模多模态动作与行为数据集 | [[paper]](https://arxiv.org/abs/2510.16258) |
| 2024 | ECCV | Nymeria | 大规模多模态第一视角日常动作采集 | [[project]](https://www.projectaria.com/datasets/nymeria) |
| 2024 | CVPR | Inter-X | 多样化人-人交互分析数据集 | [[project]](https://liangxuy.github.io/inter-x/) |
| 2023 | NeurIPS | Motion-X | 大规模全身表情动作 + 文本数据集,15.6M 帧 | [[project]](https://motion-x-dataset.github.io/) [[code]](https://github.com/IDEA-Research/Motion-X) |
| 2022 | CVPR | HumanML3D | 文本-动作配对数据集,14616 动作 / 44970 文本 | [[code]](https://github.com/EricGuo5513/HumanML3D) |
| 2021 | ICCV | AIST++ | 从 AIST 舞蹈重建的 3D 舞蹈动作,配对音乐 | [[project]](https://google.github.io/aistplusplus_dataset/) |
| 2021 | CVPR | BABEL | 为 AMASS 提供逐帧/逐序列语义动作标签 | [[project]](https://babel.is.tue.mpg.de/) [[code]](https://github.com/abhinanda-punnakkal/BABEL) |
| 2019 | ICCV | AMASS | 统一到 SMPL 的大规模 mocap 集合,>40h、300+ 主体 | [[project]](https://amass.is.tue.mpg.de/) [[code]](https://github.com/nghorbani/amass) |

## 10. 人体表征与基础模型 (Representation & Foundation)

| 年份 | 会议/期刊 | 方法名 | 解决的问题与核心方案 | 链接 |
| --- | --- | --- | --- | --- |
| 2025 | ICCV | PUMPS | 骨架无关的点式通用动作预训练 | [[paper]](https://arxiv.org/abs/2507.20170) |
| 2025 | CVPR | UniPose | 统一多模态的人体姿态理解/生成/编辑 | [[project]](https://liyiheng23.github.io/UniPose-Page/) |
| 2025 | Arxiv | SMPLest-X | 表达性人体姿态与形状估计的极致规模化 | [[project]](https://caizhongang.com/projects/SMPLer-X/) |
| 2024 | ECCV | Sapiens | 人体视觉基础模型 | [[project]](https://www.meta.com/emerging-tech/codec-avatars/sapiens/) |
| 2024 | Arxiv | MotionLLM | 从动作与视频联合理解人类行为 | [[project]](https://lhchen.top/MotionLLM/) |
| 2020 | ECCV | VIBE / mocap 系列 | 从视频回归 SMPL 的时序人体重建(参考) | [[code]](https://github.com/mkocabas/VIBE) |
| 2019 | CVPR | SMPL-X | 扩展身体+手+脸的整体表达人体模型 + VPoser 姿态先验 | [[project]](https://smpl-x.is.tue.mpg.de/) [[code]](https://github.com/vchoutas/smplx) |
| 2015 | SIGGRAPH Asia (TOG) | SMPL | 线性蒙皮的参数化人体模型(shape + pose blendshape) | [[project]](https://smpl.is.tue.mpg.de/) |

---

## 更新日志 (Changelog)

- **2026-08-08**:重构为分类表格形式,补充 Text-to-Motion / 扩散 / 音乐驱动 / 交互 / 风格 / 重定向 / 物理 / 预测 / 数据集 / 表征 等方向经典与前沿工作。
- **2026-08-08**:参考 [Foruck/Awesome-Human-Motion](https://github.com/Foruck/Awesome-Human-Motion),精选补充约 67 篇 2024–2026 顶会/里程碑工作。
- **2026-08-08**:依据 [Foruck/Awesome-Human-Motion](https://github.com/Foruck/Awesome-Human-Motion) 的原始链接,将上述新增条目的 arXiv 搜索链全部替换为 paper/project/code 直链。

## 贡献方式 (Contributing)

欢迎通过 PR / Issue 补充新论文,建议按以下格式提供:`年份 | 会议或期刊 | 方法名 | 一句话核心方案 | paper/code/project 链接`。
