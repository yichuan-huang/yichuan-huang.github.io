---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **BEng in Electrical and Electronic Engineering**, University of Nottingham, Nottingham, United Kingdom, 2025--Present
* **BEng in Electrical and Electronic Engineering**, University of Nottingham Ningbo China, Ningbo, China, 2023--2025

Experience
======
* **Research Assistant (Remote)**, Tsinghua University, Department of Automation, Beijing, China, Sep. 2025--Feb. 2026
  * Supervisor: Prof. Keyou You
  * Developed a Deep Reinforcement Learning (DRL) framework for autonomous robotic harvesting (flower picking) in unstructured environments.
  * Trained and evaluated Soft Actor-Critic (SAC) and Truncated Quantile Critics (TQC) policies for pick-and-place tasks with a Franka Panda in MuJoCo, focusing on manipulation robustness and generalization across simulated scenes.
  * Observed signs of catastrophic forgetting in SAC under certain training settings, motivating comparative analysis of policy stability and retention.
  * Developed a custom 2-DOF robotic arm environment for sim-to-sim transfer research, and analyzed deployment bottlenecks arising from limited MoCap support, particularly its impact on accurate motion tracking, policy evaluation, and transfer validation.

* **Visiting Undergraduate Student**, Shenzhen Research Institute of Big Data, Shenzhen, China, Jun. 2025--Aug. 2025
  * Supervisor: Assoc. Prof. Ruoyu Sun
  * Surveyed recent LLM post-training paradigms, with emphasis on synthetic continued pre-training and catastrophic forgetting in fine-tuning.
  * Studied EntiGraph for synthetic data generation and examined the MoFo optimizer as an approach to improving retention during fine-tuning.
  * Gained hands-on exposure to local deployment and inference workflows for open-source LLMs through experimentation with GPT-OSS.

* **Research Assistant (Onsite & Remote)**, Xi'an Jiaotong University, Bioinspired Engineering & Biomechanics Center, Xi'an, China, Jul. 2024--Jan. 2026
  * Supervisors: Prof. Feng Xu; Asst. Prof. Bin Li
  * Designed and implemented a contrastive-learning-based virtual fluorescence staining framework for label-free, biophysics-anchored osteogenic fate inference from conventional microscopy images.
  * Demonstrated improved preservation of cellular structure, geometric consistency, and morphology-aware translation over CycleGAN-based baselines, while reducing computational cost through unidirectional training.
  * Conducted quantitative and qualitative evaluation of cellular morphology and visual fidelity, contributing to a co-authored manuscript currently under review at *Nature Methods*.
  * Explored generative-model-based preprocessing and enhancement methods, including Stable Diffusion and FLUX, and deployed an interactive FLUX.2 demo on Hugging Face Spaces for image enhancement and domain adaptation experiments.

* **Intern (Remote)**, University of Science and Technology of China, Hefei, China, May 2024--Jul. 2024
  * Supervisor: Prof. Wei Sun
  * Trained a ResNet-50 model for computer vision classification tasks, achieving over 80% accuracy through systematic parameter tuning and optimization.
  * Implemented Deep Q-Network (DQN) methods for the CarRacing environment by converting the original continuous control task into a discrete action space, and trained an agent that achieved a peak mean reward of nearly 900.
  * Built a multimodal image retrieval workflow using Claude Sonnet 3, matching prompt queries to model-generated image descriptions to identify images satisfying user-defined requirements.

Research Output
======
* **OsteoSight: Label-Free Virtual Fluorescence Staining for Biophysics-Anchored Osteogenic Fate Inference from Conventional Microscopy**
  * Co-author; manuscript under review at *Nature Methods*

Awards
======
* **University Academic Excellence Scholarship Winner (Provost's Scholarship)**, University of Nottingham Ningbo China, 2024--2025 and 2025--2026
* **Nominee for Zhejiang Provincial Scholarship**, University of Nottingham Ningbo China, 2024

Skills
======
* **Languages & Tools**: Python, C/C++, CMake, Git, Linux/Shell, Docker
* **AI Engineering**: PyTorch, Computer Vision, LLM Integration (APIs/Prompting), Applied Reinforcement Learning, NumPy, Pandas, Matplotlib, Scikit-learn, XGBoost
* **Embedded & Robotics**: STM32, ROS, Raspberry Pi, Arduino, LTspice, FPGA (Verilog), PID Control, Robotics Simulation (Isaac Sim / MuJoCo)