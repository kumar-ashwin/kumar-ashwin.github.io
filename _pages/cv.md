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
* Ph.D in Computer Science, Washington University in St. Louis, 2024 (expected)

Work experience
======
* Fall 2023: Research Scientist Intern 
  * Meta Platforms, Inc., Menlo Park, CA
    * Designed metrics to detect bias in reward models used in the RLHF pipeline.
    * Evaluated multiple open-source datasets and LLM architectures for the presence of this bias to build understanding and guide mitigations.
    * Used active learning techniques to identify useful data points to be labeled for RLHF, to minimize labeling costs.

* Summer 2017: Design and Engineering Intern
  * Bubblefly Technologies Pvt. Ltd., Delhi, India
    *	Worked on designing an ergonomic fixed enclosure system for the avionics bay of Unmanned Aerial vehicles.
    * Conducted research on the design of an adaptable battery mount for ease of installation and removal.


* Summer 2018: Research Intern
  * Indian Institue of Science, Bengaluru, India
    * Performed dimensionality reduction of strain energy expression for hyper-elastic strip geometry using symbolic tools like Mathematica; solution using Variational Asymptotic Method (VAM) to develop a geometrically and materially non-linear beam theory. 
    * Applied to helicopter rotor blades for vibration reduction.


* Spring 2022: Assistant in Instruction
  * Department of Computer Science, Washington University in St. Louis, St Louis, MO
    * Provided one-on-one assistance to more than 130 students on coursework and homework assignments covering the mathematical foundations and application of algorithms for search, constraint satisfaction, Markov models, reinforcement learning and propositional and first order logic for the course Introduction to Artificial Intelligence.
    *	Graded homework assignments and exams.
	  * Delivered lectures on Reinforcement Learning and conducted problem-solving sessions on Logic and MDPs. 

* Fall 2022: Research Scientist Intern
  * Meta Platforms, Inc., New York, NY
    * Designed methods for detection of bias feedback loops in content classifiers which use Model Assisted Sampling to send data points for human review.
    * Measured the propagation of bias to future models if a biased model is used in the sampling process and worked on sampling strategies to mitigate bias bootstrapping and speed up recovery.
    * Worked with multiple product teams to identify different techniques and generalize experiments.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
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

Skills
======
* Coding
  * Data structures and algorithms
  * Object-oriented programming
  * Git/ version control
* Python
  * Data analysis (pandas, numpy, scipy, scikit-learn)
  * Machine learning (scikit-learn, tensorflow, pytorch)
  * Optimization (cplex, gurobi)
  * Web design (flask, d3.js, css, html)
* Machine Learning
  * Reinforcement Learning
    * MDPs and POMDPs
    * Deep Q-Networks
    * Policy Gradient Methods
    * Actor-Critic Methods
  * Supervised Learning
    * Regression
    * Gradient Boosted Trees
    * Neural Networks
  * Adversarial Machine Learning
* Natural Language Processing
  * Word embeddings
  * Sequence to sequence models
  * Transformers
  * Attention 
