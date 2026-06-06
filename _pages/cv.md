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
* **BEng in Electrical and Electronic Engineering**, University of Nottingham, Nottingham, United Kingdom, 2025--2027
* **BEng in Electrical and Electronic Engineering**, University of Nottingham Ningbo China, Ningbo, China, 2023--2027

Experience
======
* **Research Assistant (Remote)**, Tsinghua University, Department of Automation, Beijing, China, Sep. 2025--Feb. 2026
  * Supervisor: Prof. Keyou You
  * Developed and evaluated a deep reinforcement learning framework for autonomous robotic harvesting / flower-picking tasks in unstructured environments, using MuJoCo and a Franka Panda manipulator for pick-and-place simulation.
  * Built and debugged MuJoCo-based robotic manipulation environments for training and evaluating harvesting-oriented control policies under simulated task settings.
  * Trained and compared Soft Actor-Critic (SAC) and Truncated Quantile Critics (TQC) policies, focusing on training stability, robustness, and generalisation across simulated manipulation scenarios.
  * Achieved a 100% success rate with 25+ cumulative reward after approximately 1M training steps in a defined MuJoCo simulation evaluation task, validating the effectiveness of the training pipeline under the tested setting.
  * Observed catastrophic forgetting patterns in SAC under selected training configurations, motivating comparative analysis of policy stability, retention, and robustness.
  * Developed a custom 2-DOF robotic arm environment for sim-to-sim transfer exploration, and analysed deployment bottlenecks caused by limited motion-capture support, including constraints on motion tracking, policy evaluation, and transfer validation.

* **Visiting Undergraduate Student**, Shenzhen Research Institute of Big Data, Shenzhen, China, Jun. 2025--Aug. 2025
  * Supervisor: Assoc. Prof. Ruoyu Sun
  * Surveyed recent LLM post-training paradigms, with emphasis on synthetic continued pre-training and catastrophic forgetting in fine-tuning.
  * Studied EntiGraph for synthetic data generation and examined the MoFo optimiser as an approach to improving retention during fine-tuning.
  * Gained hands-on exposure to local deployment and inference workflows for open-source LLMs through experimentation with GPT-OSS.

* **Research Assistant (Onsite & Remote)**, Xi'an Jiaotong University, Bioinspired Engineering & Biomechanics Center, Xi'an, China, Jul. 2024--Jan. 2026
  * Supervisors: Prof. Feng Xu; Asst. Prof. Bin Li
  * Contributed to OsteoSight, a label-free virtual fluorescence staining and biophysics-anchored osteogenic fate inference system for conventional microscopy images.
  * Participated in the development and evaluation of a contrastive-learning-based virtual fluorescence staining pipeline to reconstruct YAP, F-actin, and nuclei signals from label-free microscopy images.
  * Supported model training, debugging, and qualitative/quantitative evaluation for image-to-image translation and virtual staining tasks, focusing on cellular morphology preservation, geometric consistency, and subcellular structure reconstruction.
  * Compared generated virtual staining results with image translation baselines such as CycleGAN, analysing differences in cell boundary preservation, visual fidelity, and morphology-aware translation quality.
  * Contributed to downstream evaluation of single-cell biophysical features and osteogenic fate inference, supporting analysis of protein localisation, cell morphology, local density, and interpretable model outputs.
  * The team's manuscript, "OsteoSight: Label-Free Virtual Fluorescence Staining for Biophysics-Anchored Osteogenic Fate Inference from Conventional Microscopy", is currently under submission/review; the system was evaluated on 1,276 paired confocal images and 2,106 phase-contrast images, achieving an F1 score of 90.69% for osteogenic fate inference.
  * Explored generative-model-based image preprocessing and enhancement methods, including Stable Diffusion and FLUX, and deployed an interactive FLUX.2 demo on Hugging Face Spaces for image enhancement and domain adaptation experiments.

* **Intern (Remote)**, University of Science and Technology of China, Hefei, China, May 2024--Jul. 2024
  * Supervisor: Prof. Wei Sun
  * Trained a ResNet-50 model for computer vision classification tasks, achieving over 80% accuracy through systematic parameter tuning and optimisation.
  * Implemented Deep Q-Network (DQN) methods for the CarRacing environment by converting the original continuous control task into a discrete action space, and trained an agent that achieved a peak mean reward of nearly 900.
  * Built a multimodal image retrieval workflow using Claude Sonnet 3, matching prompt queries to model-generated image descriptions to identify images satisfying user-defined requirements.

Research Output
======
* **OsteoSight: Label-Free Virtual Fluorescence Staining for Biophysics-Anchored Osteogenic Fate Inference from Conventional Microscopy**
  * Co-author; manuscript under submission/review

Awards
======
* **Scholarships**, University of Nottingham Ningbo China
  * University Academic Excellence Scholarship Winner (Provost's Scholarship), 2024--2025 and 2025--2026
  * Nominee for Zhejiang Provincial Scholarship, 2024

Skills
======
* **Languages & Tools**: Python, C/C++, MATLAB/Simulink, CMake, Git, Linux/Shell, Docker
* **AI Engineering**: PyTorch, Computer Vision, LLM Integration (APIs/Prompting), Applied Reinforcement Learning, NumPy, Pandas, Matplotlib, Scikit-learn, XGBoost
* **Embedded & Robotics**: STM32, ROS, Raspberry Pi, Arduino, LTspice, FPGA (Verilog), PID Control, MuJoCo
