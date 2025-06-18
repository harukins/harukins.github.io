---
title: "Is Your Imitation Learning Policy Better than Mine? Policy Comparison with Near-Optimal Stopping"
collection: publications
permalink: /publication/2025_rss_david
venue: 'Robotics: Science and Systems (RSS)'
date: 2025-06-22
citation: 'David Snyder, Asher Hancock, Apurva Badithela, Emma Dixon, Patrick Miller, Rares Ambrus, Anirudha Majumdar, Masha Itkina, <b>Haruki Nishimura</b>'
paperurl: 'https://arxiv.org/pdf/2503.10966'
publisherurl: 'https://roboticsconference.org/program/papers/77/'
codeurl: 'https://tri-ml.github.io/step/'
---


## Abstract
Imitation learning has enabled robots to perform complex, long-horizon tasks in challenging
dexterous manipulation settings. As new methods are developed, they must be rigorously evaluated
and compared against corresponding baselines through repeated evaluation trials. However, policy
comparison is fundamentally constrained by a small feasible sample size (e.g., 10 or 50) due to
significant human effort and limited inference throughput of policies. This paper proposes a novel
statistical framework for rigorously comparing two policies in the small sample size regime.
Prior work in statistical policy comparison relies on batch testing, which requires a fixed,
predetermined number of trials and lacks flexibility in adapting the sample size to the observed
evaluation data. Furthermore, extending the test with additional trials risks inducing inadvertent
p-hacking, undermining statistical assurances. In contrast, our proposed statistical test is
sequential, allowing researchers to decide whether or not to run more trials based on intermediate
results. This adaptively tailors the number of trials to the difficulty of the underlying comparison,
saving significant time and effort without sacrificing probabilistic correctness. Extensive numerical
simulation and real-world robot manipulation experiments show that our test achieves near-optimal stopping,
letting researchers stop evaluation and make a decision in a near-minimal number of trials.
Specifically, it reduces the number of evaluation trials by up to 32% as compared to state-of-the art
baselines, while preserving the probabilistic correctness and statistical power of the comparison.
Moreover, our method is strongest in the most challenging comparison instances (requiring the most
evaluation trials); in a multi-task comparison scenario, we save the evaluator more than 160
simulation rollouts.

## Video
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
  <iframe src="https://tri-ml.github.io/step/videos/Anchor_Video_Border_Trimmed_Braked_v4.mp4" 
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" 
    frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen title="Video player">
  </iframe>
</div>

## BibTex
```
@inproceedings{snyder2025step,
  title = {Is Your Imitation Learning Policy Better Than Mine? Policy Comparison with Near-Optimal Stopping},
  author = {Snyder, David and Hancock, Asher James and Badithela, Apurva and Dixon, Emma and Miller, Patrick and Ambrus, Rares Andrei and Majumdar, Anirudha and Itkina, Masha and Nishimura, Haruki},
  booktitle={Proceedings of the Robotics: Science and Systems Conference (RSS) XXI},
  year = {2025},
}
```