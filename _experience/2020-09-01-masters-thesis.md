---
title: 'Learning from demonstrations: A case study on Autonomous UAV Landing'
collection: experience
date: 2020-09-01
permalink: /experience/masters-thesis
author_profile: false
use_image: true
image: images/airsim.PNG
excerpt: "Master's Thesis under Dr. Dileep Kalathil, Oct 2019 - Present."
github: 'https://github.com/prabhasak/masters-thesis'
tags:
  - Python
  - Microsoft AirSim
  - Stable Baselines
  - OpenAI Gym and MuJoCo
  - Reinforcement Learning
  - Imitation Learning
---

Abstract
======

<div style="text-align: justify">

As robots and other intelligent agents move from simple environments to more complex, unstructured settings, manually programming their behavior has become increasingly challenging and expensive. However, modern deep reinforcement learning (RL) systems also require an exponentially increasing number of samples. One way to address this limitation is to use sample-efficient methods like imitation learning (IL), that leverage only human priors and demonstrations to generate desired behavior. These methods have proven to be effective on problems with singular tasks, and are effective especially in tasks related to robotic manipulation and autonomous vehicles. <br><br>

This Thesis studies the sample-efficiency of an existing IL-based algorithm: Generative Adversarial Imitation Learning (GAIL), a model-free method that tries to learn purely from expert demonstrations. To demonstrate the sample-efficiency of these algorithms, we consider a real-world system: Unmanned Aerial Vehicles (UAVs). We design a novel method of autonomous UAV maneuver & landing using Microsoft <a href="https://microsoft.github.io/AirSim/">AirSim</a> as an environment simulator. We answer questions related to GAIL’s imitation accuracy, data-efficiency, the parameters critical to learning, and comment on impact of cost function design on imitation. We also study the environment itself, by discussing design choices, potential bottlenecks, and attempt to address some practical challenges. We also present some preliminary results on GAIL’s sample-efficiency for some physics-based control tasks from OpenAI Gym and MuJoCo. <br><br>

</div>

To summarize, we trained a drone to land on a custom ship deck built on AirSim with just 10 expert trajectories, demonstrating GAIL's sample efficiency. A short video of the training process is available [here](https://youtu.be/oj4y8GOq4gk).

GitHub for this work can be found [here](https://github.com/prabhasak/masters-thesis).
<!-- GitHub for this work can be found at <h1>{{ page.github }}</h1>. -->