---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

The PDF version is coming soon.

Education
======
* **Ph.D. in Aeronautics and Astronautics, Stanford University, CA, USA, September 2021**
  * Graduate Research Assistant, [Multi-Robot Systems Lab](https://msl.stanford.edu), January 2017 – September 2021
* **M.S. in Aeronautics and Astronautics, Stanford University, CA, USA, June 2017**
  * GPA: 4.04/4.00
* **B.Eng. in Aeronautics and Astronautics, The University of Tokyo, Tokyo, Japan, March 2015**


Scholarships & Awards
=====
* **[Masason Foundation](https://masason-foundation.org/en/) Fellowship, Tokyo, Japan**
  * Associate member, July 2018 – June 2019
  * Member, July 2019 – March 2022 (expected)
* **[JASSO](https://www.jasso.go.jp/en/index.html) Student Exchange Support Program, Tokyo, Japan**
  * Two-year graduate scholarship for Master's students, September 2015 – June 2017
  * Three-year graduate scholarship for Ph.D. students, September 2017 – August 2020
  

Professional Experience
======
* **[Toyota Research Institute](https://www.tri.global/), CA, USA, June 2018 – September 2018**
  * Intern, Object Perception
    * Contributed to offline object tracking pipeline in autonomous driving software for post-processing simulation and 
      test-driving results.

* **[Honda Aircraft Company](https://www.hondajet.com/), NC, USA, June 2016 – September 2016**
  * Intern, Systems Integration
    * Improved offline flight simulation tool for non-linear aircraft analyses. Performed simulations to 
      study characteristics of Automatic Flight Control System on HA-420 Honda Jet during approach procedure.
  

Research Interests
=====
* Enabling autonomous agents to actively perceive surrounding environment for information gathering.
* Developing reliable and efficient uncertainty-aware planning algorithms for real-world robotic applications.
* Designing risk-aware and robust trajectory planning methods for safety-critical autonomous systems.
* Extending model-based control techniques to interface with modern data-driven perception and prediction modules.


Research Experience
=====
* **Multi-Robot Systems Lab (Advisor: Prof. [Mac Schwager](https://web.stanford.edu/~schwager/)), Stanford University, 
  September 2016 – September 2021**
  * Distributionally-Robust Trajectory Planning for Nonlinear Non-Gaussian Systems ([RA-L 2021]({% link _publications/2021_ral.md %}))
    * Proposed distributionally-robust model predictive control algorithm for nonlinear dynamical systems with a 
      Kullback-Leibler divergence constraint.
    * Augmented iterative linear-exponential-quadratic-Gaussian algorithm for risk-sensitive optimal control with
      dynamic risk-sensitivity parameter adjustment to achieve desired level of distributional robustness.
  * Fast Risk-Sensitive Planning with Deep-learned Probabilistic Prediction Models ([IROS 2020]({% link _publications/2020_iros.md %}))
    * Proposed efficient nonlinear model predictive control algorithm to perform risk-sensitive optimal control under 
      arbitrary generative prediction models.
    * Demonstrated safe robot navigation among many mutually-interactive humans via combination of model-based
      stochastic control and data-driven probabilistic human trajectory forecasting.
  * Fast Approximate Belief Space Planning via Stochastic Sequential Action Control ([WAFR 2018]({% link _publications/2018_wafr.md %}), 
    [IJRR 2021]({% link _publications/2021_ijrr.md %}))
    * Developed near real-time belief space planning algorithm for control-affine nonlinear dynamical systems with 
      stochastic jump transitions.
    * Applications include information-theoretic active sensing and model-based Bayesian reinforcement learning.  
  * Active Vision-Based Intent Inference for Robots with Monocular Vision ([ICRA 2018]({% link _publications/2018_icra.md %}))
    * Designed online Bayesian estimation algorithm to perform monocular vision-based intent inference for motion-based
      communication between two mobile robots.
    * Implemented search-based belief space planning algorithm based on Monte Carlo Tree Search to plan successive 
      camera poses to maximally reduce uncertainty in intent estimate.
* **Space Application Laboratory (Advisor: Prof. [Takehisa Yairi](https://www.rcast.u-tokyo.ac.jp/en/research/people/staff-yairi_takehisa.html)),
  The University of Tokyo, April 2014 – November 2014**      
  * Aerial Simultaneous Localization and Mapping for Indoor Monitoring (Bachelor Thesis Project)
    * Implemented monocular vision-based simultaneous localization and mapping algorithm with Extended Kalman Filter
      for Parrot AR.Drone 2.0.
    * Demonstrated feasibility of life-logging and indoor monitoring using only generated feature-based map. 


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>


Talks & Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>


Press & Media
======
* **[A framework to increase the safety of robots operating in crowded environments](https://techxplore.com/news/2020-10-framework-safety-robots-crowded-environments.html)**, 
  TechXplore, October 2020
  

Publication Reviewing
======
* **Journals**: IEEE Transactions on Robotics, IEEE Robotics and Automation Letters, 
  IEEE Transactions on Automation Science and Engineering, Journal of Aerospace Information Systems, 
  Autonomous Robots
* **Conferences**: IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 
  IEEE International Conference on Robotics and Automation (ICRA), IEEE Conference on Decision and Control (CDC),
  American Control Conference (ACC)


Skills
======
* **Software**: MATLAB, Simulink, Autodesk Inventor, Autodesk 3ds Max Design
* **Hardware**: PIC Microcontrollers, Atmel AVR, Odroid
* **Programming Languages**: Julia, Python, C++, PIC Assembly Language
* **Libraries and Tools**: Pytorch, Docker, ROS, Gazebo, AirSim, Open AI Gym
* **Soft Skills**: Science and engineering lesson design based on learning sciences
  
Teaching
======
* **Creative Engineering Project I・III, The University of Tokyo, April 2015 – July 2015**
  * Teaching Assistant for LETS: Learn Engineering with Tokyo University Students (Instructor: Prof. Shinji Suzuki)
    * Helped teams of undergrads and grad students design and deliver science lessons to children in public elementary
      school in local Tokyo area.
    * Gave feedback to teams based on effectiveness of lecture and experimentation design proposals as measured by 
      knowledge transferability (concept in learning sciences).

Service and Leadership
======
* **Stanford Japanese Association, Stanford University, CA, USA**
  * Officer, September 2018 – August 2020
* **LETS: Learn Engineering with Tokyo University Students, The University of Tokyo, Tokyo, Japan**
  * Project Member, April 2013 – July 2014
* **Consortium for Renovating Education of the Future, The University of Tokyo, Tokyo, Japan**
  * Science Workshop Planner, March 2014
* **Star Watching Class in Oshika, Miyagi, Japan**
  * Project Leader, September 2013 – December 2013
* **Non-Governmental Organization JEN, Miyagi, Japan** 
  * Volunteer, 2011 Great Tohoku Earthquake Reconstruction Assistance Program, November 2011 – October 2013
  
