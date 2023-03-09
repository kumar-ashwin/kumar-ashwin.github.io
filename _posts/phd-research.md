---
title: 'Why fairness in temporal resource allocation?'
date: 2023-03-08
permalink: /posts/2023/08/phd-research/
tags:
  - motivation
  - research
---
Artificial Intelligence has become an inextricable part of the human experience. With ``smart'' tools embedded in almost every application, AI is going to make decisions for us whether we like it or not. This realization was the primary source of motivation for my research. If AI is going to be omnipresent, it is imperative to develop techniques to allow its seamless integration into society while maintaining accountability. When algorithms are used to make decisions that can affect real people[1]], the analysis of their disparate impact becomes necessary for ensuring fairness.
Following this thought, I started off my Ph.D. with a broad vision of improving AI transparency and fairness. In one of my initial projects, I got to examine a state-of-the-art ridesharing matching model called NeurADP[5]. NeurADP used approximate dynamic programming to efficiently match passengers to taxis with high capacity, allowing them to share rides with others. It was highly competitive, and able to service a much higher fraction of the people wanting rides. While analyzing the dynamics of this system, we discovered a large disparity in how well different regions of a city were served, with suburbs being disproportionately under-served. This, of course, raised the question: What was an acceptable trade-off for efficiency?

At its core, rideshare matching is a resource allocation problem: match drivers and passengers to maximize some utility. There were many parallels across different fields, all of which were using algorithmic decision making to allocate resources, such as kidney exchange, school choice, network bandwidth allocation and refugee shelter allocation. Fairness in resource allocation had been studied for decades, and it was getting more popular with this increase in the use of algorithmic techniques.

An important cog in recent work on resource allocation, and a major influence on my research, was the seminal work by Mnih et al. on Deep Q-Networks (DQNs)[4]], which led to the boom of deep reinforcement learning. Rather than allocating resources based on the immediate value we could derive from them, non-myopic utility estimation allows us to make good long-term decisions. Deep reinforcement learning proved to be the way forward, using neural networks to estimate future values of current states. 

Solutions like NeurADP are complex, with a lot of moving parts, including something akin to a DQN value function. In domains with a temporal component, where agents could re-enter the system, ensuring fairness is a much harder problem. The two areas of algorithmic (ML) fairness and fair resource allocation had been mostly independent.
Fairness in resource allocation was well-studied, but in the context of knowing the correct utilities. Further, repeated allocations were a lesser-known subset of this class of problems.
On the other hand, there was a huge body of prior work on fairness in machine learning that could be applied to value function estimation, but it focused on classification and regression problems rather than resource allocation. There was a clear gap at the intersection of these ideas.

Solving the fairness problem in NeurADP required combining concepts from resource allocation, fair allocation, deep reinforcement learning and algorithmic fairness, forming the crux of my thesis research. The ideas of statistical parity[3,2] and max-min fairness informed my approach to fairness in my research, where I attempted to marry these schools of thought. My initial approach of using incentives to guide the allocation towards fairness saw success, both at improving fairness and allowing the easy tuning of the fairness-efficiency trade-off. This approach also translated to a variety of problem instances apart from ridesharing. 

Influenced by all of the above, my research focus is on improving the long-term fairness and efficiency in this intersectional field. I aim to use techniques from the algorithmic fairness literature and develop a three-pronged take on fair allocation, by looking at fairness interventions before, during and after the learning of the value function estimator.

References
======
[1] Julia Angwin, Jeff Larson, Surya Mattu, and Lauren Kirchner. 2016. Machine bias. In Ethics of data and analytics. Auerbach Publications, 254–264.
[2] Sam Corbett-Davies, Emma Pierson, Avi Feller, Sharad Goel, and Aziz Huq. 2017. Algorithmic decision making and the cost of fairness. In KDD ’17. 797–806.
[3] Michael Feldman, Sorelle A. Friedler, John Moeller, Carlos Scheidegger, and Suresh Venkatasubramanian. 2015. Certifying and Removing Disparate Impact. In KDD’15. 259–268.
[4] Volodymyr Mnih, Koray Kavukcuoglu, David Silver, Alex Graves, Ioannis Antonoglou, Daan Wierstra, and Martin Riedmiller. 2013. Playing Atari with Deep Reinforcement Learning. arXiv preprint arXiv:1312.5602 (2013).
[5] Sanket Shah, Meghna Lowalekar, and Pradeep Varakantham. 2020. Neural Approximate Dynamic Programming for On-Demand Ride-Pooling. In Proceedings of the AAAI Conference on Artificial Intelligence. 507–515.
