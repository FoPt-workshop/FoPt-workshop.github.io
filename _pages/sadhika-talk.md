---
layout: page
permalink: /sadhika-talk
title: Failure Modes of Preference Learning
description: [Sadhika Malladi](https://fopt-workshop.github.io/speakers/)
nav: false
---

### Abstract

Preference learning algorithms, such as DPO, are frequently used to steer LLMs to produce generations that are more preferred by humans, but little is understood about how they modify model behavior. I will present theory and experiments that highlight two surprising failure modes of popular preference learning methods. First, I will show that commonly used preference learning schemes often fail to teach a model to assign higher likelihood to preferred responses over dispreferred ones. Our theoretical result attributes this failure to the difficulty of optimizing the objective. In the second half of the talk, I will focus on the widely observed phenomenon of likelihood displacement, whereby the probability of the preferred response decreases during training. Our theoretical analysis demonstrates that the model's embedding geometry drives likelihood displacement, and that the probability of undesirable sequences can increase during preference learning. For example, training the model to prefer a gentle "No" over a harsh "Never" can sharply increase the likelihood of a compliant "Yes". In real-world settings, we observe that likelihood displacement can result in unintentional unalignment, whereby a model begins to comply with unsafe requests it had previously denied. Our theory motivates the design of a data filtering metric that effectively mitigates likelihood displacement and the resulting unalignment.