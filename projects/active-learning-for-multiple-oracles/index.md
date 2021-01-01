+++
title = "Active Learning for Multiple Oracles"
date = 2017-12-20T20:57:56-04:00
draft = false

tags = ["active-learning"]

summary = "An active learning algorithm that selects which oracles to query"
+++

This project was done as my course project for CS686 Introduction to Artificial Intelligence at [the University of Waterloo](https://uwaterloo.ca/). 

I extended the hybrid crowd-expert workflow proposed in the paper [Combining
Crowd and Expert Labels using Decision Theoretic
Active Learning](https://www.aaai.org/ocs/index.php/HCOMP/HCOMP15/paper/view/11567) by introducing the machine-crowd-expert workflow for oracle selection. The active learning agent uses a utility-maximization based approach to decide which oracles to query the unknown labels from. In particular, the agent has three choices at each decision step: query a machine oracle, which is a pre-trained machine learning classifier, ask the crowd oracle, which comprises of a group of crowd workers recruited from Amazon Mechanical Turk, to correct an instance previously labeled by the machine oracle or ask the expert oracle, which is played by a domain expert, to correct an instance previously labeled by the crowd oracle. 