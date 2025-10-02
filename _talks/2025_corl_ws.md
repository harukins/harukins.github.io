---
title: "From Failure Detection to Policy Debugging: Tracking Performance of Generative Imitation Policies"
collection: talks
type: "Workshop presentation"
permalink: /talks/2025_corl_ws
venue: "2nd Workshop on Safe and Robust Robot Learning for Operation in the Real World (SAFE-ROL, CoRL 2025)"
date: 2025-09-27
location: "Seoul, South Korea"
eventurl: 'https://sites.google.com/view/corl-2025-safe-rol-workshop'
---

Modern generative models have enabled robots to acquire challenging dexterous skills directly from human demonstrations. Yet, even the state-of-the-art learned policies, such as TRI's Large Behavior Model (LBM), often suffer unexpected failures during deployment. Moreover, the overall performance of the policies can drift over time (either deteriorating or improving) due to inevitable distribution shifts. The black-box and stochastic nature of such policies makes it particularly difficult to identify when and how these performance fluctuations occur. This talk provides an overview of the Trustworthy-Learning under Uncertainty (TLU) team within TRI's Robotics division, where we confront this challenge from multiple theoretical and algorithmic foundations: uncertainty quantification, modern statistical analysis, and data attribution. Together, these tools allow researchers and practitioners to detect failures in real time, rigorously verify performance fluctuations, and trace them back to specific training data. This not only enables timely detection of performance drops but also provides an effective framework for systematic policy improvement.