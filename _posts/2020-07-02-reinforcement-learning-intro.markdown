---
layout: post
title:  "Reinforcement Learning Intro"
date:   2020-07-02 14:00:00 +0200
categories: rl
---

# What?
Reinforcement Learning is an attempt to learn to do things by observing interactions with the world. Let's call the learner an **Agent**, and the world an **Environment**. By interacting with the Environment through **actions**, the Agent will receive information about the current **state** of the Environment, as well as a **reward** scalar signal. The reward is the only indicator that the Agent has available to it which it can use to improve its behaviour. So that's Reinforcement Learning, nothing more, nothing less. Anything else which falls under this topic is only specialising something to make the Agent learn faster, find stabler policies, etc.

# Books
The first book you should touch is the Sutton and Barto [bible][sutton&barto2017]. Here the basic terminology and mathematical principles required to describe RL are introduced, developed further and discussed.

[sutton&barto2017]: http://incompleteideas.net/book/bookdraft2017nov5.pdf
