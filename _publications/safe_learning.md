---
title: "Safe Reinforcement Learning via Shielding under Partial Observability"
collection: publications
permalink: /publication/safe_learning
excerpt: 'This paper is about utilizing formal models to ensure an RL agent will satisfy a temporal logic specification during and after learning'
date: 2022-08-23
venue: 'arXiv'
paperurl: 'http://stevencarrau.com/files/safe_learning.pdf'
citation: 'Carr, Steven et al. (2022). &quot; Safe Reinforcement Learning via Shielding under Partial Observability.&quot; <i>arXiv </i>. arXiv:2204.00755.'
---
Safe exploration is a common problem in reinforcement learning (RL) that aims to prevent agents from making disastrous decisions while exploring their environment. A family of approaches to this problem assume domain knowledge in the form of a (partial) model of this environment to decide upon the safety of an action. A so-called shield forces the RL agent to select only safe actions. However, for adoption in various applications, one must look beyond enforcing safety and also ensure the applicability of RL with good performance. We extend the applicability of shields via tight integration with state-of-the-art deep RL, and provide an extensive, empirical study in challenging, sparse-reward environments under partial observability. We show that a carefully integrated shield ensures safety and can improve the convergence rate and final performance of RL agents. We furthermore show that a shield can be used to bootstrap state-of-the-art RL agents: they remain safe after initial learning in a shielded setting, allowing us to disable a potentially too conservative shield eventually.

[Download paper here](http://stevencarrau.com/files/safe_learning.pdf)

Recommended citation: Carr, Steven, et al. "Safe Reinforcement Learning via Shielding under Partial Observability." <i>arXiv preprint </i> arXiv:2204.00755 (2022).