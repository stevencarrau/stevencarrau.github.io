---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

---
**[Verifiable and Compositional Reinforcement Learning Systems](../_publications/2021_verifiable_and_compositional_rl.md)**

**Cyrus Neary**, Christos Verginis, Murat Cubuktepe, and Ufuk Topcu<br><span style="font-size:12pt">*The International Conference on Automated Planning and Scheduling (ICAPS) 2022*.</span>


<img 
src="/images/compositional_rl.gif" 
width=500 
style="float: right; margin-left: 10px; margin-right: 10px;">


We propose a framework for verifiable and compositional reinforcement learning (RL) in which a collection of RL sub-systems -- each of which learns to accomplish a separate sub-task -- are composed to achieve an overall task. By defining interfaces between the sub-systems, the framework enables automatic decompositons of task specifications, *e.g., reach a target set of states with a probability of at least 0.95*, into individual sub-task specifications, *i.e. achieve the sub-system's exit conditions with at least some minimum probability, given that its entry conditions are met*. This in turn allows for the independent training and testing of the sub-systems; if they each learn a policy satisfying the appropriate sub-task specification, then their composition is guaranteed to satisfy the overall task specification.

[Read More](../_publications/2021_verifiable_and_compositional_rl.md) \| [Paper](https://arxiv.org/abs/2106.05864) \| [Code](https://github.com/cyrusneary/verifiable-compositional-rl)

---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
