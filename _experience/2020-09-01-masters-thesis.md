---
title: "Learning from demonstrations: Applications to Autonomous UAV Landing and Minecraft"
collection: experience
date: 2020-11-01
permalink: /experience/masters-thesis
author_profile: false
use_image: true
image: images/airsim.PNG
excerpt: "Master's Thesis under Dr. Dileep Kalathil, Oct 2019 - Oct 2020."
github: 'https://github.com/prabhasak/masters-thesis'
tags:
  # - Generative Adversarial Imitation Learning
  - Imitation Learning
  - Microsoft AirSim
  # - MuJoCo
  # - OpenAI Gym
  - Python
  - Reinforcement Learning
  - Stable Baselines
  - TensorFlow
  - Master's Thesis
---

<!-- Abstract -->
<!-- ====== -->

<div style="text-align: justify">

As robots and other intelligent agents move from simple environments to more complex, unstructured settings, modern deep reinforcement learning (RL) systems require an exponentially increasing number of samples for learning. This sample-inefficiency is not practical, especially for many real-world tasks when environment samples and compute are expensive. Sample-efficient methods like imitation learning (IL) leverage human demonstrations to generate the desired behavior. IL has proven to be effective in problems with singular tasks, especially on tasks related to robotic manipulation and autonomous vehicles. I use sample-efficient IL methods to learn behaviors of two sparsely rewarded systems: Unmanned Aerial Vehicles (UAVs) and Minecraft. Here, I will talk about IL's application to UAVs. Details on the second application of my thesis can be found on the Projects page <a href="http://prabhasak.github.io/projects/minecraft">here</a>. <br><br>

Current control systems do not capture the intuition and decision-making skills behind a pilot's maneuvers, which can be crucial for landing under uncertainties. I helped design a novel method of autonomous UAV landing using only human demonstrations and a visual cue for positioning. Specifically, I applied Generative Adversarial Imitation Learning (GAIL) on demonstrations of the task, as opposed to learning behavior purely from RL. I demonstrate sample-efficient imitation and comment on the need for `smooth' experts for learning optimal landings. <br><br>

To summarize, a model was designed to capture a pilot’s intuition to navigate and land drones on a simulated ship deck. The learned model achieved an imitation accuracy of 84% with just 10 human demonstrations, demonstrating the sample efficiency of imitation learning methods (GAIL). A short video of training is available <a href="https://youtu.be/oj4y8GOq4gk">here</a>. Performance metrics were visualized with Weights & Biases, and the reports are available <a href="https://wandb.ai/prabhasak/masters-thesis/reportlist?workspace=user-prabhasak">here</a>. <br><br>

<b> Slides for this application can be accessed <a href="https://prabhasak.github.io/files/Masters_Thesis_Prabhasa_Kalkur_Slides_pdf_friendly_1.pdf">here</a>. Codebase for the first half of this work can be found <a href="https://github.com/prabhasak/masters-thesis">here</a>.<b>. For the more patient folks, my thesis is also publicly available <a href="https://prabhasak.github.io/files/Masters_Thesis_Prabhasa_Kalkur.pdf">here</a>. <br><br> <br><br>


<!-- </div> -->

<!-- <figure>
  <img src="https://prabhasak.github.io/files/AirSim.gif" alt="AirSim" width=100/>
  <figcaption>Autonomous UAV navigation and landing in Microsoft AirSim.</figcaption>
</figure> -->

<p align="center">
<img src="https://prabhasak.github.io/files/AirSim.gif" alt="AirSim"/>
</p>