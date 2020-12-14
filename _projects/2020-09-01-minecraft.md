---
title: "Learning to imitate tasks in Minecraft"
collection: projects
date: 2020-11-01
permalink: /projects/minecraft
author_profile: false
excerpt: "MineRL Competition - NeurIPS 2020, Aug 2020 – Nov 2020."
github: 'https://github.com/prabhasak/MineRL-NeurIPS-2020'
tags:
  - Imitation Learning
  - Microsoft Malmo  
  - Minecraft
  - MineRL
  - Python
  - PyTorch
  - Reinforcement Learning
---

Description
======

<div style="text-align: justify">

The goal is to develop sample-efficient Reinforcement Learning and Imitation Learning algorithms using human demonstrations, to perform tasks in Minecraft. The MineRL competition involves solving tasks in complex, hierarchical, sparse environments, with constraints on training time and compute. This necessitates the use of efficient exploration techniques and training with human priors. To address this, I used Deep Q-learning from Demonstrations (DQfD) for learning behaviors, which is essentially an RL algorithm paired with demonstration data from the <a href="https://minerl.io/docs/">MineRL</a> dataset. <br><br>

Specifically, I used DQfD for learning to chop trees and mine diamonds in Minecraft. as opposed to learning behavior purely from RL. For the task of chopping trees, RL algorithms trained on demonstrations (DQfD) performed 10x better than the plain RL equivalent of Deep-Q Networks (DQN). Slides for the project are available <a href="https://prabhasak.github.io/files/Masters_Thesis_Prabhasa_Kalkur_Slides_pdf_friendly_2.pdf">here</a>. The codebase is available <a href="https://github.com/prabhasak/MineRL-NeurIPS-2020">here</a>. Please feel free to reach me if you would like to know more about the competition :) <br><br>

</div>

<br><br> <br><br>

<p align="center">
<img src="https://prabhasak.github.io/files/minerl.gif" alt="MineRL" />
</p>