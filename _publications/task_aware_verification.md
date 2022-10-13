---
title: "Task-aware Verifiable RNN-based Policies for Partially Observable Markov Decision Processes"
collection: publications
permalink: /publication/task_aware_verification
excerpt: 'This paper presents a method of verifying the behavior of an RNN-based policy'
date: 2021-11-01
venue: 'Journal of Artificial Intelligence Research '
paperurl: 'http://stevencarrau.com/files/task_aware_verification.pdf'
citation: 'Carr, Steven et al. (2021). &quot; Task-aware Verifiable RNN-based Policies for Partially Observable Markov Decision Processes.&quot; <i>Journal of Artificial Intelligence Research </i>. 72 (2021): 819-847.'
---
Partially observable Markov decision processes (POMDPs) are models for sequential decision-making under uncertainty and incomplete information. Machine learning methods typically train recurrent neural networks (RNN) as effective representations of POMDP policies that can efficiently process sequential data. However, it is hard to verify whether the POMDP driven by such RNN-based policies satisfies safety constraints, for instance, given by temporal logic specifications. We propose a novel method that combines techniques from machine learning with the field of formal methods: training an RNN-based policy and then automatically extracting a so-called finite-state controller (FSC) from the RNN. Such FSCs offer a convenient way to verify temporal logic constraints. Implemented on a POMDP, they induce a Markov chain, and probabilistic verification methods can efficiently check whether this induced Markov chain satisfies a temporal logic specification. Using such methods, if the Markov chain does not satisfy the specification, a by-product of verification is diagnostic information about the states in the POMDP that are critical for the specification. The method exploits this diagnostic information to either adjust the complexity of the extracted FSC or improve the policy by performing focused retraining of the RNN. The method synthesizes policies that satisfy temporal logic specifications for POMDPs with up to millions of states, which are three orders of magnitude larger than comparable approaches.

[Download paper here](http://stevencarrau.com/files/task_aware_verification.pdf)

Recommended citation: Carr, Steven, Nils Jansen, and Ufuk Topcu. "Task-aware verifiable RNN-based policies for partially observable Markov decision processes." <i>Journal of Artificial Intelligence Research</i> 72 (2021): 819-847.