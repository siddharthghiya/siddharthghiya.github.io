---
title: "Agent Probing Interaction Policy"
excerpt: "<br/><img src='/images/api/architecture.png'>"
collection: portfolio
---

* Proposed a novel approach to solve the problem of opponent modeling in multi-agent systems.
* Make an agent learn policies that help it identify the kind of opposite agent in the environment by observing the reaction of the opposite agent to the learned policy.
* Trained an LSTM based classifier to identify the type of the opposite agent using state trajectories and policy using Proximal Policy Optimization with the loss of the classifier as a reward.
* In the proposed toy environment, the agent was able to learn policies to correctly identify the kind of the opposite agent in the environment with an accuracy of 91%.