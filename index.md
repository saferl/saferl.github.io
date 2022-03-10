---
title: Safe Reinforcement Learning
description: A Tutorial
---


Safety is a paramount requirement for the deployement of reinforcement learning (RL).
This tutorial provides an extensive overview of the different perspectives of safe RL.
We highlight critical issues common to any approach to safe RL and pose the following questions:

- What is the specific understanding of safety?
- Which type of prior knowledge is needed to reason about the uncertainty of an agent’s environment?
- How safe is safe RL ultimately?

This page contains material that will be used for the tutorial.

## Presentations

The following slides will serve as the basis for the tutorial.

| [![Octocat](/assets/slides/safe_rl_lecture_2021_TUDelft_Thumbnail.png){: width="250" }](/assets/slides/safe_rl_lecture_2021_TUDelft.pdf) <br /> Lecture for Algorithms for Intelligent Decision Making course at Delft University of Technology|
| [![Octocat](/assets/slides/AI_Safety_2021_Thumbnail.png){: width="250" }](/assets/slides/AI_Safety_2021.pdf) <br /> Lecture fo Model Checking course at Radboud University, Nijmegen|
| [![Octocat](/assets/slides/NFM_AI_Safety_2020_Thumbnail.png){: width="250" }](/assets/slides/NFM_AI_Safety_2020.pdf) <br /> Talk at the [NFM AI-SAFETY 2020 workshop](https://sites.google.com/stanford.edu/nfm-ai-safety-20/speakers)|
| [![Octocat](/assets/slides/SNR_2021_Thumbnail.png){: width="250" }](/assets/slides/SNR_2021.pdf) <br /> Talk at [QONFEST 2021](https://qonfest2021.lacl.fr/speakers.php)|


## Demos

The following videos show a set of applications using safe RL algorithms.

### Robot Navigation

Pessimistic Constrained RL using Worst-Case Soft Actor Critic
<div class="text-center" style="max-width: 600px; max-height: 600px">
	<iframe width="600" height="370" src="https://www.youtube.com/embed/OR9xD1_4_aU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
	</iframe>
</div>

### Trafic Light Controller

Adaptive Shielding under Uncertainty
<div class="text-center" style="max-width: 600px; max-height: 600px">
    <video tabindex="0" controls="" preload="none" style="width: 100%    !important; height: auto   !important;" poster="{{ site.baseurl }}/assets/videos/Adaptive_Shielding_01_Thumbnail.png">
        <source src="https://surfdrive.surf.nl/files/index.php/s/IJwEZwF0EZvntoq/download" type="video/mp4">
    </video>
</div>


### Robot Sampling with Charging Constraints

Safe Policies for Factored Partially Observable Stochastic Games
<div class="text-center" style="max-width: 600px; max-height: 600px">
    <video tabindex="0" controls="" preload="none" style="width: 100%    !important; height: auto   !important;" poster="{{ site.baseurl }}/assets/videos/SafePoliciesFactoredPOSGs_Thumbnail.png">
        <source src="https://surfdrive.surf.nl/files/index.php/s/qGxwHaI8FN9W3oT/download" type="video/mp4">
    </video>
</div>

### Partially Observable Problem

Safe RL via Shielding for POMDPs
<div class="text-center" style="max-width: 600px; max-height: 600px">
    <video tabindex="0" controls="" preload="none" style="width: 100%    !important; height: auto   !important;" poster="{{ site.baseurl }}/assets/videos/SafeRL_POMDPs_Thumbnail.png">
        <source src="https://surfdrive.surf.nl/files/index.php/s/NYS5ZKjK84IdoGp/download" type="video/mp4">
    </video>
</div>


### Pac-Man

Shield helping Pac-Man avoid the ghosts
<div class="text-center" style="max-width: 600px; max-height: 600px">
	<video controls="" width="560" height="315">
	    <source src="http://www.cs.ru.nl/personal/nilsjansen/subs/shield_rl/videos/pacman/originalClassic.mp4" type="video/mp4">
	    Your browser does not support the video tag.
	</video> 
</div>
