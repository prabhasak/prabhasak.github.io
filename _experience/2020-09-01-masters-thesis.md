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
  - MuJoCo
  - OpenAI Gym
  - Python
  - Reinforcement Learning
  - Stable Baselines
  - TensorFlow
  - Master's Thesis
---

<!-- Abstract -->
<!-- ====== -->

<div style="text-align: justify">

As robots and other intelligent agents move from simple environments to more complex, unstructured settings, modern deep reinforcement learning (RL) systems require an exponentially increasing number of samples for learning. This sample-inefficiency is not practical, especially for many real-world tasks when environment samples and compute are expensive. One way to address these limitations is to use sample-efficient methods like imitation learning (IL), that leverage human demonstrations to generate the desired behavior. IL has proven to be effective in problems with singular tasks, especially on tasks related to robotic manipulation and autonomous vehicles. <br><br>

I used sample-efficient IL methods to learn behaviors of two sparsely rewarded systems: Unmanned Aerial Vehicles (UAVs) and Minecraft. Current control systems do not capture the intuition and decision-making skills behind a pilot's maneuvers, which can be crucial for landing under uncertainties. We designed a novel method of autonomous UAV landing using only human demonstrations. Specifically, we applied Generative Adversarial Imitation Learning on demonstrations of the task, as opposed to learning behavior purely from RL. We demonstrate sample-efficient imitation and comment on the need for `smooth' experts for learning optimal landings. <br><br>

To summarize, we captured a pilot’s intuition to navigate and land drones on a simulated ship deck, demonstrating the sample efficiency of Imitation Learning methods (GAIL). We achieved an imitation accuracy of 84% with just 10 human demonstrations. A short video of training is available <a href="https://youtu.be/oj4y8GOq4gk">here</a>. We visualized results with Weights & Biases, the reports are available <a href="https://wandb.ai/prabhasak/masters-thesis/reportlist?workspace=user-prabhasak">here</a>. Details on the second application of my thesis can be found on the Projects page <a href="http://prabhasak.github.io/projects/minecraft">here</a>. <br><br>

<b> Slides from my thesis defense can be accessed <a href="https://prabhasak.github.io/files/Thesis_final.pdf">here</a>. For the more patient folks, my thesis is also publicly available <a href="https://prabhasak.github.io/files/Thesis_Prabhasa_Kalkur.pdf">here</a>. Codebase for the first half of this work can be found <a href="https://github.com/prabhasak/masters-thesis">here</a>.<b>
<!-- GitHub for this work can be found at <h1>{{ page.github }}</h1>. -->

<img src="https://prabhasak.github.io/files/AirSim.gif" alt="Autonomous UAV navigation and landing in Microsoft AirSim" />

</div>