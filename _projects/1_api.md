---
title: "Agent Probing Interaction Policy"
excerpt: "<img src='/images/api/architecture.png' height = '200' width='200'>"
collection: projects
---

<img src="/images/api/architecture.png">
* Proposed a novel approach to solve the problem of opponent modeling in multi-agent systems.
* Make an agent learn policies that help it identify the kind of opposite agent in the environment by observing the reaction of the opposite agent to the learned policy.
* Trained an LSTM based classifier to identify the type of the opposite agent using state trajectories and policy using Proximal Policy Optimization with the loss of the classifier as a reward.
* In the proposed toy environment, the agent was able to learn policies to correctly identify the kind of the opposite agent in the environment with an accuracy of 91%.

[Technical Report](https://drive.google.com/file/d/1Qe2UHwZfNhChEc9JBpAchXBfpSkOUZZn/view?usp=sharing "Technical Report")
[Presentation](https://drive.google.com/file/d/1UVbgkMb27mf0fzUyNAEfaOzIQEnaigr9/view?usp=sharing "Presentation")
[Video](https://www.youtube.com/watch?time_continue=1&v=6Y5fpdrQifA&feature=emb_logo "Video")

