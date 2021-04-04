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

There was an <a href="https://openai.com/blog/openai-five-defeats-dota-2-world-champions/">article</a> a few years ago on how an AI model was trained on > 11,000 years’ worth of DOTA gameplay to beat pro players. Why do machines require so many samples for learning? If we were to build AI models for equally complex, everyday tasks like a self-driving car for instance, how many samples would we need to learn? As it turns out, the answer is “a lot.” As robots and other intelligent agents move from simple environments to more complex, unstructured settings, modern deep reinforcement learning (RL) systems require an exponentially increasing number of samples for learning. For many real-world tasks where environment samples and compute are expensive, <b>sample-efficiency</b> is a practical bottleneck. <br><br>

Conventional AI models learn from conditioning- where behavior is encouraged via a reward or discouraged via punishment. Think of spraying water on your dog when he bites the couch or treating him for a job well done. Humans are better learners than AI for one major reason: we not only learn from conditioning but also learn from <u>observation</u>. You may have seen videos of cute babies trying to imitate their parents do things, or animals trying to mimic their owner’s actions. Cognitive Science and behavioral studies show that humans and animals fundamentally learn behavior through <u>imitation</u>, thanks to the brilliant coordination between our eyes and the brain. This isn’t just “monkey see, monkey do,” we internalize factors such as context, which results in the development of <b>intuition</b>. <br><br>

<p align="center">
<img src="https://prabhasak.github.io/files/E3-baby.jpg" alt="Baby"/>
</p>

Interestingly, many real-world problems have readily available human demonstration data for performing the task (self-driving cars, playing Chess, robots for day-to-day tasks, flying helicopters, etc.). In this data-centric era, <b>(i) can we leverage available demo data to reduce our sample requirements? and (ii) can conventional AI models learn context and capture intuition by referring to data of a human performing tasks?</b> Machine Learning (ML) techniques such as <b>imitation learning</b> do exactly this, while utilizing as few demo samples as possible. This 'sample-efficient' method of leveraging human demos to generate the desired behavior has proven to be effective in problems with singular tasks, especially on tasks related to robotic manipulation and autonomous vehicles. <br><br> 

<b>For my Thesis, I taught ML models to fly drones and perform tasks in a video game (both in simulation) by using human demonstrations of two real-world systems: Unmanned Aerial Vehicles (UAVs) and Minecraft</b>. The challenge for learning these behaviors was two-fold: (i) they are complex systems with hierarchical tasks, and (ii) the goals are sparsely rewarded, so it is hard to incentivize learning. Here, I will talk about IL's application to UAVs. Details on the second application of my thesis can be found on the Projects page <a href="http://prabhasak.github.io/projects/minecraft">here</a>. <br><br>

Current control systems do not capture the intuition and decision-making skills behind a pilot's maneuvers, which can be crucial for landing under uncertainties. For this, I helped design a novel method of autonomous UAV landing using only human demos and a visual cue for positioning. Specifically, I applied imitation learning algorithms on a trained pilot's point-to-point maneuvers of a drone in Microsoft AirSim, in order to learn an ML model that imitates the pilot's behavior. I demonstrated sample-efficient imitation by learning from as few as 10 pilot demonstrations of the task and comment on the need for 'smooth' experts for learning smooth landings. To summarize, an ML model was designed to capture a pilot’s intuition to navigate and land drones on a simulated ship deck. The learned ML model achieved a high imitation accuracy, demonstrating the sample efficiency of imitation learning methods.<br><br>

 <b>Slides</b> for this application can be accessed <a href="https://prabhasak.github.io/files/E3-Masters_Thesis_Prabhasa_Kalkur_Slides_pdf_friendly_1.pdf">here</a>. <b>Codebase</b> for the first half of this work can be found <a href="https://github.com/prabhasak/masters-thesis">here</a>. A short video of <b>training</b> the ML model is available <a href="https://youtu.be/oj4y8GOq4gk">here</a>. Performance metrics were visualized with Weights & Biases, and the <b>reports</b> are available <a href="https://wandb.ai/prabhasak/masters-thesis/reportlist?workspace=user-prabhasak">here</a>. I also made a short 3-minute <b>video</b> as part of a University competition, available <a href="https://vimeo.com/472405835">here</a>. For the more patient folks, my <b>thesis</b> is also publicly available <a href="https://prabhasak.github.io/files/E3-Masters_Thesis_Prabhasa_Kalkur.pdf">here</a>. <br><br>


<!-- </div> -->

<!-- <figure>
  <img src="https://prabhasak.github.io/files/AirSim.gif" alt="AirSim" width=100/>
  <figcaption>Autonomous UAV navigation and landing in Microsoft AirSim.</figcaption>
</figure> -->

<p align="center">
<img src="https://prabhasak.github.io/files/E3-AirSim.gif" alt="AirSim"/>
</p>