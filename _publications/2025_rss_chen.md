---
title: "Can We Detect Failures Without Failure Data? Uncertainty-Aware Runtime Failure Detection for Imitation Learning Policies"
collection: publications
permalink: /publication/2025_rss_chen
venue: 'Robotics: Science and Systems (RSS)'
date: 2025-06-22
citation: 'Chen Xu, Tony Khuong Nguyen, Emma Dixon, Christopher Rodriguez, Patrick Miller, Robert Lee, Paarth Shah, Rares Andrei Ambrus, <b>Haruki Nishimura</b>, Masha Itkina'
paperurl: 'https://arxiv.org/pdf/2503.08558'
publisherurl: 'https://roboticsconference.org/program/papers/73/'
codeurl: 'https://cxu-tri.github.io/FAIL-Detect-Website/'
---


## Abstract
Recent years have witnessed impressive robotic manipulation systems driven by advances in imitation learning and generative modeling, such as diffusion- and flow-based approaches. As robot policy performance increases, so does the complexity and time horizon of achievable tasks, inducing unexpected and diverse failure modes that are difficult to predict a priori. To enable trustworthy policy deployment in safety-critical human environments, reliable runtime failure detection becomes important during policy inference. However, most existing failure detection approaches rely on prior knowledge of failure modes and require failure data during training, which imposes a significant challenge in practicality and scalability. In response to these limitations, we present FAIL-Detect, a modular two-stage approach for failure detection in imitation learning-based robotic manipulation. To accurately identify failures from successful training data, we frame the problem as sequential out-of-distribution (OOD) detection. We first distill policy inputs and outputs into scalar signals that correlate with policy failures and capture epistemic uncertainty. FAIL-Detect then employs conformal prediction (CP) as a versatile framework for uncertainty quantification with statistical guarantees. Empirically, we thoroughly investigate both learned and post-hoc scalar signal candidates on diverse robotic manipulation tasks. Our experiments show learned signals based on adapted random networks and a novel flow-based density estimator to be most effective. Furthermore, our method detects failures more accurately and faster than state-of-the-art (SOTA) failure detection baselines. These results highlight the potential of FAIL-Detect to enhance the safety and reliability of imitation learning-based robotic systems as they progress toward real-world deployment.

## Video
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
  <iframe src="https://cxu-tri.github.io/FAIL-Detect-Website/Assets/video.mp4" 
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" 
    frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen title="Video player">
  </iframe>
</div>


## BibTex
```
@inproceedings{xu2025can,
  title={Can We Detect Failures Without Failure Data? Uncertainty-Aware Runtime Failure Detection for Imitation Learning Policies},
  author={Xu, Chen and Nguyen, Tony Khuong and Dixon, Emma and Rodriguez, Christopher and Miller, Patrick and Lee, Robert and Shah, Paarth and Ambrus, Rares and Nishimura, Haruki and Itkina, Masha},
  booktitle={Proceedings of the Robotics: Science and Systems Conference (RSS) XXI},
  year={2025}
}
```