---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
For a PDF version of my CV, click [here](https://kumar-ashwin.github.io/files/CV_Feb2023.pdf).

See my [Resume](https://kumar-ashwin.github.io/files/Resume_May2024.pdf) to see a shorter version.

Education
======
* B.S. in Mechanical Engineering, Shiv Nadar University, 2019
* M.S. in Computer Science, Washington University in St. Louis, 2022
  * Graduate Certificate in Data Mining and Machine Learning
* Ph.D in Computer Science, Washington University in St. Louis, 2025 (expected)

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Work experience
======
* **Fall 2023: Research Scientist Intern (Meta Platforms, Inc., Menlo Park, CA)**

  <details>
  <summary><strong>Bias in LLM Reward Models</strong></summary>
  
  - Designed metrics to detect bias in reward models used in the RLHF pipeline.
  - Evaluated multiple open-source datasets and LLM architectures for the presence of this bias to build understanding and guide mitigations.
  - Used active learning techniques to identify useful data points to be labeled for RLHF, to minimize labeling costs.
  </details>

* **Summer 2022: Research Scientist Intern (Meta Platforms, Inc., New York, NY)**

  <details>
  <summary><strong>Bias Feedback Loop Detection in Continual Active Learning</strong></summary>
  
  - Designed methods to detect bias feedback loops in content classifiers using Model Assisted Sampling for data review.
  - Measured bias propagation to future models when a biased model is used in sampling, and developed strategies to mitigate bias bootstrapping and accelerate recovery.
  - Collaborated with multiple product teams to identify techniques and generalize experimental findings.
  </details>

* **Spring 2022: Assistant in Instruction (Department of Computer Science, Washington University in St. Louis, St Louis, MO)**

  <details>
  <summary><strong>Course: Introduction to Artificial Intelligence</strong></summary>
  
  - Provided one-on-one assistance to over 130 students on coursework and assignments related to algorithms, Markov models, reinforcement learning, and logic.
  - Graded homework assignments and exams.
  - Delivered lectures on Reinforcement Learning and led problem-solving sessions on Logic and Markov Decision Processes (MDPs).
  </details>

* **Summer 2018: Research Intern (Indian Institute of Science, Bengaluru, India)**

  <details>
  <summary><strong>Dimensionality Reduction for Hyper-Elastic Strip Geometry</strong></summary>
  
  - Performed dimensionality reduction of strain energy expressions for hyper-elastic strip geometry using symbolic tools like Mathematica.
  - Utilized the Variational Asymptotic Method (VAM) to develop a geometrically and materially non-linear beam theory, applied to helicopter rotor blades for vibration reduction.
  </details>

* **Summer 2017: Design and Engineering Intern (Bubblefly Technologies Pvt. Ltd., Delhi, India)**

  <details>
  <summary><strong>Ergonomic Design for UAV Avionics Bay</strong></summary>
  
  - Designed an ergonomic fixed enclosure system for the avionics bay of Unmanned Aerial Vehicles (UAVs).
  - Conducted research and developed an adaptable battery mount for easier installation and removal.
  </details>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Program Committee member for NeurIPS 2024
* Program Committee member for ICAPS 2024
* Program Committee member for IJCAI 2024
* Reviewer for the Human-Aware Explainable Planning (HAXP) workshop, ICAPS 2023
* Reviewer for the eXplainable AI Planning (XAIP) workshop, ICAPS 2022

## Skills

<details>
  <summary><strong>Coding</strong></summary>

  - Data structures and algorithms
  - Object-oriented programming
  - Git/Version control
</details>

<details>
  <summary><strong>Python</strong></summary>

  - Data analysis: pandas, numpy, scipy, scikit-learn
  - Machine learning: scikit-learn, tensorflow, pytorch
  - Optimization: cplex, gurobi
  - Web design: flask, d3.js, CSS, HTML
</details>

<details>
  <summary><strong>Machine Learning</strong></summary>

  - **Reinforcement Learning**
    - MDPs and POMDPs
    - Deep Q-Networks
    - Policy Gradient Methods
    - Actor-Critic Methods
  - **Supervised Learning**
    - Regression
    - Gradient Boosted Trees
    - Neural Networks
  - **Adversarial Machine Learning**
</details>

<details>
  <summary><strong>Natural Language Processing</strong></summary>

  - Word embeddings
  - Sequence to sequence models
  - Transformers
  - Attention mechanisms
</details>

