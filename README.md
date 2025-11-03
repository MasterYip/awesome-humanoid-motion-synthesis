# awesome-humanoid-motion-synthesis
A curated list of works for legged robot(humanoid) motion synthesis.

> [!NOTE]
> This repo is still under construction. Links may not be correct.

## 1. Data-Driven Motion Synthesis

### 1.1 Text-to-Motion Diffusion Models
- **[MDM (Motion Diffusion Model)](https://arxiv.org/abs/2209.14916)** - Tevet et al., 2023
  - Pioneering work applying diffusion models to text-conditioned motion generation using DDPM framework with HumanML3D representation
  
- **[MotionCLIP](https://arxiv.org/abs/2203.08063)** - Tevet et al., 2022
  - Exposes human motion generation to CLIP latent space for text-driven synthesis

- **[MoFusion](https://arxiv.org/abs/2212.04495)** - Dabral et al., 2023
  - Framework for denoising-diffusion-based motion synthesis with multi-modal control

- **[MotionBERT](https://arxiv.org/abs/2210.06551)** - Zhu et al., 2023
  - Unified perspective on learning human motion representations using transformer architecture

### 1.2 Generalization and Few-Shot Methods
- **[MoMo](https://arxiv.org/abs/2406.06508)** - Raab et al., 2024a
  - Zero-shot motion transfer using self-attention in motion diffusion ("Monkey see, monkey do")

FIXME
- **[MAS (Multi-view Ancestral Sampling)](https://arxiv.org/abs/2312.14435)** - Kapon et al., 2024
  - Multi-view approach for 3D motion generation using 2D diffusion

- **[SinMDM (Single Motion Diffusion)](https://openreview.net/pdf?id=DrhZneqz4n)** - Raab et al., 2024b
  - Training diffusion models on single motion examples for generalization

### 1.3 Auto-Regressive Diffusion Models
FIXME
- **[A-MDM](https://arxiv.org/abs/2306.14990)** - Shi et al., 2024
  - Interactive character control with auto-regressive motion diffusion models
FIXME
- **[CAMDM (Taming Diffusion)](https://arxiv.org/abs/2404.15462)** - Chen et al., 2024
  - Taming diffusion probabilistic models for character control with real-time capabilities

### 1.4 Motion Editing and Manipulation
- **[Human Motion Diffusion as Generative Prior](https://openreview.net/forum?id=dTpbEdN9kr)** - Shafir et al., 2024
  - Using motion diffusion models as priors for various motion synthesis tasks

- **[EDGE (Editable Dance Generation)](https://arxiv.org/abs/2211.10658)** - Tseng et al., 2023
  - Editable dance generation from music using diffusion models

- **[Flexible Motion In-betweening](https://arxiv.org/abs/2405.11126)** - Cohan et al., 2024
  - Motion in-betweening using diffusion models for flexible interpolation

- **[Iterative Motion Editing with Natural Language](https://arxiv.org/abs/2312.11538)** - Goel et al., 2024
  - Natural language-driven iterative motion editing framework
FIXME
- **[Optimizing Diffusion Noise as Motion Priors](https://arxiv.org/abs/2312.11509)** - Karunratanakul et al., 2024
  - Universal motion priors through diffusion noise optimization

## 2. Diffusion Models for Object Interaction

### 2.1 Human-Object Interaction (HOI)
- **[THOR](https://arxiv.org/abs/2403.11208)** - Wu et al., 2024
  - Text to human-object interaction diffusion via relation intervention

- **[HOI-Diff](https://arxiv.org/abs/2312.06553)** - Peng et al., 2023
  - Text-driven synthesis of 3D human-object interactions

- **[Generating Human Interaction Motions in Scenes](https://arxiv.org/abs/2404.10685)** - Yi et al., 2024
  - Text-controlled human interaction motion generation in scenes

- **[Move As You Say, Interact As You Can](https://arxiv.org/abs/2403.18036)** - Wang et al., 2024
  - Language-guided human motion generation with scene affordance

### 2.2 Human-Scene Interaction (HSI)
FIXME
- **[Generating Human Motion in 3D Scenes](https://arxiv.org/abs/2405.11154)** - Cen et al., 2024
  - Generating human motion in 3D scenes from text descriptions

- **[GenZI (Zero-shot 3D Human-Scene Interaction)](https://arxiv.org/abs/2311.17737)** - Li & Dai, 2024
  - Zero-shot generation of 3D human-scene interactions

- **[NIFTY (Neural Object Interaction Fields)](https://arxiv.org/abs/2307.07511)** - Kulkarni et al., 2024
  - Neural object interaction fields for guided human motion synthesis

### 2.3 Physics-Based Scene Interaction
FIXME
- **[Diffusion-based Generation in 3D Scenes](https://arxiv.org/abs/2301.00398)** - Huang et al., 2023
  - Diffusion-based generation, optimization, and planning in 3D scenes

## 3. Text-Controlled Simulated Characters

### 3.1 Language-Directed Physics Control
- **[PADL (Physics And Deep Learning)](https://doi.org/10.1145/3550469.3555391)** - Juravsky et al., 2022
  - Language-directed physics-based character control with simple instructions
FIXME
- **[SuperPADL](https://arxiv.org/abs/2401.11238)** - Juravsky et al., 2024
  - Scaling language-directed physics control with progressive supervised distillation

- **[MoConVQ](https://arxiv.org/abs/2310.10198)** - Yao et al., 2024
  - Unified physics-based motion control via scalable discrete representations and VQ-VAE

### 3.2 LLM-Based Control
- **[UniHSI (Unified Human-Scene Interaction)](https://openreview.net/forum?id=1vCnDyQkjg)** - Xiao et al., 2024
  - Unified human-scene interaction via prompted chain-of-contacts using LLMs

- **[InsActor](https://arxiv.org/abs/2312.17135)** - Ren et al., 2023
  - Instruction-driven physics-based characters

### 3.3 Offline Learning Approaches
- **[PDP (Physics-based Character Animation via Diffusion Policy)](https://arxiv.org/abs/2406.00960)** - Truong et al., 2024
  - Learning from offline humanoid motion imitation dataset with diffusion policy

### 3.4 Trajectory Planning
- **[Trace and Pace](https://arxiv.org/abs/2304.01893)** - Rempe et al., 2023
  - Controllable pedestrian animation via guided trajectory diffusion

- **[Hierarchical Planning for Box Loco-Manipulation](https://arxiv.org/abs/2302.13857)** - Xie et al., 2023
  - Using diffusion as reference for limited-data box manipulation tasks

## 4. Humanoid Motion Imitation

### 4.1 Deep Reinforcement Learning for Imitation
- **[DeepMimic](http://doi.acm.org/10.1145/3197517.3201311)** - Peng et al., 2018
  - Example-guided deep RL for physics-based character skills with single-clip tracking
FIXME
- **[Trajectory Optimization for Full-Body Movements](https://ieeexplore.ieee.org/document/6095523)** - Al Borno et al., 2012
  - Early work on trajectory optimization with complex contacts
FIXME
- **[Physics-Based Motion Capture Imitation](https://dl.acm.org/doi/10.1145/3281659)** - Chentanez et al., 2018
  - Physics-based motion capture imitation with deep RL

### 4.2 Large-Scale Motion Tracking
FIXME
- **[A Scalable Approach to Control Diverse Behaviors](https://dl.acm.org/doi/10.1145/3386569.3392381)** - Won et al., 2020
  - Scaling to larger datasets for physically simulated character control
FIXME
- **[PHC (Perpetual Humanoid Control)](https://arxiv.org/abs/2305.08716)** - Luo et al., 2023
  - Real-time simulated avatars with universal tracking policy on AMASS dataset (99% success rate)
FIXME: this is amp
- **[Supertrack](https://dl.acm.org/doi/10.1145/3450626.3459670)** - Fussell et al., 2021
  - Motion tracking for physically simulated characters using supervised learning

### 4.3 Specialized Motion Tracking
- **[Dynamics-Regulated Kinematic Policy](https://arxiv.org/abs/2106.05969)** - Luo et al., 2021
  - Egocentric pose estimation with dynamics regulation
FIXME
- **[Embodied Scene-Aware Human Pose Estimation](https://arxiv.org/abs/2206.03694)** - Luo et al., 2022
  - Scene-aware pose estimation for embodied agents

- **[Residual Force Control](https://arxiv.org/abs/2006.07364)** - Yuan & Kitani, 2020
  - Agile human behavior imitation and extended motion synthesis

- **[UniCon (Universal Neural Controller)](https://arxiv.org/abs/2011.15119)** - Wang et al., 2020
  - Universal neural controller for physics-based character motion

### 4.4 Adversarial and Compositional Methods
- **[AMP (Adversarial Motion Priors)](http://doi.acm.org/10.1145/3450626.3459670)** - Peng et al., 2021
  - Stylized physics-based character control with adversarial motion priors

- **[MCP (Multiplicative Compositional Policies)](https://arxiv.org/abs/1905.09808)** - Peng et al., 2019
  - Learning composable hierarchical control

- **[ASE (Adversarial Skill Embeddings)](https://dl.acm.org/doi/10.1145/3528223.3530110)** - Peng et al., 2022
  - Large-scale reusable adversarial skill embeddings

## 5. Datasets and Benchmarks

- **[AMASS (Archive of Motion Capture as Surface Shapes)](https://arxiv.org/abs/1904.03278)** - Mahmood et al., 2019
  - Large-scale unified motion capture dataset used for training universal controllers
FIXME
- **[HumanML3D](https://arxiv.org/abs/2203.08063)** - Guo et al., 2022
  - Text-to-motion benchmark with diverse natural 3D human motions and text descriptions

## 6. Foundation Models and Encoders
FIXME
- **[CLIP (Contrastive Language-Image Pre-training)](https://arxiv.org/abs/2103.00020)** - Radford et al., 2021
  - Learning transferable visual models from natural language supervision

- **[BERT](https://arxiv.org/abs/1810.04805)** - Devlin, 2018
  - Pre-training of deep bidirectional transformers for language understanding

- **[DistilBERT](https://arxiv.org/abs/1910.01108)** - Sanh, 2019
  - Lighter version of BERT used in CLoSD for text encoding

- **[SMPL (Skinned Multi-Person Linear Model)](https://dl.acm.org/doi/10.1145/2816795.2818013)** - Loper et al., 2015
  - Standard human body model used for physics simulation

## 7. Core Techniques

### 7.1 Diffusion Models
- **[DDPM (Denoising Diffusion Probabilistic Models)](https://arxiv.org/abs/2006.11239)** - Ho et al., 2020
  - Foundation of diffusion-based generative models
FIXME
- **[Score-Based Generative Models](https://arxiv.org/abs/1907.05600)** - Sohl-Dickstein et al., 2015
  - Deep unsupervised learning using nonequilibrium thermodynamics

- **[Improved Techniques for Training Score-Based Models](https://arxiv.org/abs/2006.09011)** - Song & Ermon, 2020
  - Enhanced training techniques for score-based generative models

### 7.2 Image and Video Diffusion
- **[Latent Diffusion Models](https://arxiv.org/abs/2112.10752)** - Rombach et al., 2022
  - High-resolution image synthesis with latent diffusion

- **[Imagen Video](https://arxiv.org/abs/2210.02303)** - Ho et al., 2022
  - High definition video generation with diffusion models

### 7.3 Reinforcement Learning
FIXME
- **[PPO (Proximal Policy Optimization)](http://dblp.uni-trier.de/db/journals/corr/corr1707.html#SchulmanWDRK17)** - Schulman et al., 2017
  - Policy optimization algorithm used for training tracking controllers

- **[Isaac Gym](https://arxiv.org/abs/2108.10470)** - Makoviychuk et al., 2021
  - High-performance GPU-based physics simulation for robot learning

### 7.4 Evaluation Methods
- **[PhysDiff Metrics](https://arxiv.org/abs/2212.02500)** - Yuan et al., 2023
  - Physics-guided evaluation metrics: penetration, floating, and skating

- **[TEMOS Evaluation](https://arxiv.org/abs/2204.14109)** - Petrovich et al., 2022
  - Generating diverse human motions from textual descriptions with evaluation metrics

## 8. Specific Task Benchmarks

### 8.1 Object Interaction Tasks
- **[Synthesizing Physical Character-Scene Interactions](https://doi.org/10.1145/3588432.3591525)** - Hassan et al., 2023
  - Benchmark for sitting tasks (InterPhys) with 76% success rate baseline

