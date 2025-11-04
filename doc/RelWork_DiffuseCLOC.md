# Related Works for Diffuse-CLoC

## 1. Physics-Based Character Animation

### 1.1 Early Motion Tracking

- **[DeepMimic](https://doi.org/10.1145/3197517.3201311)** (Peng et al., 2018)
  - Early physics-based character animation focused on tracking single motion trajectories

### 1.2 Motion Distribution Capture

- **[AMP: Adversarial Motion Priors](https://doi.org/10.1145/3450626.3459670)** (Peng et al., 2021)
  - Captures motion distributions using adversarial training, though faced challenges with training stability and small datasets

### 1.3 Latent Skill Embeddings

- **[Physics-based Character Controllers using Conditional VAEs](https://doi.org/10.1145/3528223.3530067)** (Won et al., 2022)
  - Uses VAE trained on large datasets for latent skill embeddings

- **[ControlVAE](https://doi.org/10.1145/3550454.3555434)** (Yao et al., 2022)
  - Model-based learning of generative controllers for physics-based characters

- **[ASE: Large-scale Reusable Adversarial Skill Embeddings](https://doi.org/10.1145/3522636)** (Peng et al., 2022)
  - Large-scale reusable adversarial skill embeddings for physically simulated characters

- **[Neural Categorical Priors](https://doi.org/10.1145/3592120)** (Zhu et al., 2023)
  - Neural categorical priors for physics-based character control

- **[MoConVQ](https://doi.org/10.1145/3658136)** (Yao et al., 2024)
  - Unified physics-based motion control via scalable discrete representations

### 1.4 Recent Motion Tracking Controllers

- **[Perpetual Humanoid Control (PHC)](https://doi.org/10.1109/ICCV51070.2023.01000)** (Luo et al., 2023)
  - Real-time simulated avatars with perpetual humanoid control

- **[Universal Humanoid Motion Representations (PHC+)](https://openreview.net/forum?id=kmRJUBGCiB)** (Luo et al., 2024)
  - Universal humanoid motion representations for physics-based control

- **[VMP: Versatile Motion Priors](https://doi.org/10.1111/cgf.15175)** (Serifi et al., 2024b)
  - Versatile motion priors for robustly tracking motion on physical characters

### 1.5 Hierarchical Approaches (Kinematics + Tracking)

- **[Box Loco](https://dl.acm.org/doi/10.1145/3606031)** (Xie et al., 2023)
  - Hierarchical planning and control for box loco-manipulation

- **[CLoSD: Closing the Loop between Simulation and Diffusion](https://arxiv.org/abs/2410.03441)** (Tevet et al., 2024)
  - Multi-task character control closing the loop between simulation and diffusion

### 1.6 Fine-tuning Approaches

- **[RobotMDM](https://doi.org/10.1145/3680528.3687626)** (Serifi et al., 2024a)
  - Fine-tunes motion diffusion model using value function of RL tracker

- **[ReinDiffuse](https://arxiv.org/abs/2410.07296)** (Han et al., 2024)
  - Crafting physically plausible motions with reinforced diffusion model

- **[Morph](https://arxiv.org/abs/2411.14951)** (Li et al., 2024a)
  - Motion-free physics optimization framework for human motion generation

## 2. Diffusion in Physics-Based Control

### 2.1 Action-Only Diffusion Policies

- **[Diffusion Policy](https://doi.org/10.1177/02783649241273668)** (Chi et al., 2023)
  - Visuomotor policy learning via action diffusion for manipulation tasks

- **[PDP: Physics-Based Character Animation via Diffusion Policy](https://doi.org/10.1145/3680528.3687683)** (Truong et al., 2024)
  - Physics-based character animation using diffusion policy

- **[DiffuseLoco](https://openreview.net/forum?id=nVJm2RdPDu)** (Huang et al., 2024a)
  - Real-time legged locomotion control with diffusion from offline datasets

- **[Diffusion policies for bipedal robot locomotion](https://arxiv.org/abs/2407.05424)** (Mothish et al., 2024)
  - BiRoDiff for bipedal robot locomotion on unseen terrains

### 2.2 State-Action Co-Diffusion

- **[Diffuser: Planning with Diffusion](https://proceedings.mlr.press/v162/janner22a.html)** (Janner et al., 2022)
  - Planning with diffusion for flexible behavior synthesis, diffuses both states and actions

- **[Decision Diffuser](https://openreview.net/forum?id=sP1fo2K9DFG)** (Ajay et al., 2023)
  - Conditional generative modeling for decision-making, improves robustness over Diffuser

## 3. Kinematic Motion Diffusion Models

### 3.1 Text-Conditioned Generation

- **[Human Motion Diffusion Model (MDM)](https://openreview.net/forum?id=SJ1kSyO2jwu)** (Tevet et al., 2023)
  - Human motion diffusion model with text conditioning

### 3.2 Music-Conditioned Generation

- **[EDGE: Editable Dance Generation](https://doi.org/10.1109/CVPR52729.2023.00050)** (Tseng et al., 2023)
  - Editable dance generation from music

### 3.3 Partial State Conditioning

- **[Interactive Character Control with Auto-Regressive Motion Diffusion](https://doi.org/10.1145/3658140)** (Shi et al., 2024)
  - Motion synthesis through conditioning on partial states

### 3.4 Guided Motion Diffusion

- **[Guided Motion Diffusion (Guided-MDM)](https://doi.org/10.1109/ICCV51070.2023.00205)** (Karunratanakul et al., 2023)
  - Controllable human motion synthesis with classifier guidance and inpainting

### 3.5 Motion In-betweening

- **[Flexible Motion In-betweening](https://doi.org/10.1145/3641519.3657426)** (Cohan et al., 2024)
  - Flexible motion in-betweening with diffusion models

## 4. Steering and Conditioning Techniques

### 4.1 Classifier-Free Guidance

- **[Classifier-Free Diffusion Guidance](https://openreview.net/forum?id=qw8AKxfYbI)** (Ho & Salimans, 2021)
  - Enhances sample quality by interpolating between conditional and unconditional models

### 4.2 Classifier Guidance

- **[Diffusion Models Beat GANs](https://proceedings.neurips.cc/paper/2021/hash/49ad23d1ec9fa4bd8d77d02681df5cfa-Abstract.html)** (Dhariwal & Nichol, 2024)
  - Incorporates conditional information using gradient of pre-trained classifier

- **[Motion Planning Diffusion](https://ieeexplore.ieee.org/document/10160989)** (Carvalho et al., 2023)
  - Learning and planning of robot motions with diffusion models using cost functions

### 4.3 Reinforcement Learning for Planning

- **[Interactive Character Control with Auto-Regressive Motion Diffusion](https://doi.org/10.1145/3658140)** (Shi et al., 2024)
  - Uses RL as high-level planner to direct diffusion process

### 4.4 Trust Region Methods

- **[Constrained Diffusion with Trust Sampling](https://neurips.cc/virtual/2024/poster/93815)** (Huang et al., 2024b)
  - Constrained diffusion with trust region constraints

## 5. Inference Consistency and Speed

### 5.1 Action Chunking

- **[Learning Fine-Grained Bimanual Manipulation](https://doi.org/10.15607/RSS.2023.XIX.016)** (Zhao et al., 2023)
  - Averages predictions over time for consistency

### 5.2 Trajectory Selection

- **[Diffusion Predictive Control with Constraints](https://arxiv.org/abs/2412.09342)** (Römer et al., 2024)
  - Selects closest trajectory to previous one to avoid mode switching

### 5.3 Speedup Techniques

- **[One-Step Diffusion Policy](https://arxiv.org/abs/2410.21257)** (Wang et al., 2024)
  - Fast visuomotor policies via diffusion distillation

- **[AAMDM: Accelerated Auto-regressive Motion Diffusion](https://dl.acm.org/doi/10.1145/3641519.3657495)** (Li et al., 2024b)
  - Hybrid methods pairing fast architectures with slower fine-tuning

### 5.4 Rolling/Streaming Strategies

- **[TEDi: Temporally-Entangled Diffusion](https://doi.org/10.1145/3641519.3657515)** (Zhang et al., 2024)
  - Long-term motion synthesis with temporally-entangled diffusion

- **[Streaming Diffusion Policy](https://arxiv.org/abs/2406.04806)** (Høeg et al., 2024)
  - Fast policy synthesis with variable noise diffusion models

### 5.5 Addressing Compounding Errors

- **[Diffusion Forcing](https://arxiv.org/abs/2407.01392)** (Chen et al., 2024)
  - Next-token prediction meets full-sequence diffusion to address compounding errors

## 6. Core Diffusion Theory

- **[Denoising Diffusion Probabilistic Models (DDPM)](https://proceedings.neurips.cc/paper/2020/hash/4c5bcfec8584af0d967f1ab10179ca4b-Abstract.html)** (Ho et al., 2020)
  - Foundational work on denoising diffusion probabilistic models

- **[Score-Based Generative Modeling](https://openreview.net/forum?id=PxTIG12RRHS)** (Song et al., 2021)
  - Score-based generative modeling through stochastic differential equations

- **[Stochastic Langevin Dynamics](http://proceedings.mlr.press/v28/welling13.html)** (Welling & Teh, 2011)
  - Bayesian learning via stochastic gradient Langevin dynamics

## 7. Datasets

- **[AMASS: Archive of Motion Capture](https://doi.org/10.1109/ICCV.2019.00554)** (Mahmood et al., 2019)
  - Large-scale motion capture database used for training

This organization shows how Diffuse-CLoC builds upon and synthesizes ideas from multiple research directions to achieve its novel contribution of guided diffusion for physics-based character control.
