---
layout: page
title: Thesis
permalink: /thesis/
---

## *Exploring the vulnerabilities of commercial AI systems against adversarial attacks*.
Bit of a mouthful, right? But that's the way it usually is with paper/thesis titles :) 

Anyway, this is what I am currently working on.

**Here are some useful links:**
- [thesis github repo](https://github.com/kubic71/bachelors-thesis)
- [thesis pdf](https://github.com/kubic71/bachelors-thesis/blob/main/bp/en/thesis.pdf)

#### OrgPad
I was curious about organizing my thoughts in some other form that would complement plain written text. I discovered [OrgPad](https://orgpad.com/) - a tool that combines the power of mind-maps (or more generally concept maps), written text, images and videos, slides, collaboration, and much more. So I gave it a shot. Some explanations below leverage the ability to interconnect concepts and ideas, similar to how our brains structure and relate our experiences.

### What is an Adversarial attack?
If I am not to go too much into technical details, an adversarial attack takes input (image, sound, text), changes it slightly such that the change is imperceptible. This pertubed input is what we call an adversarial example and it fools the attacked neural network into making a mistake. I focus on a subset of deep neural networks that [classify images into categories](https://towardsdatascience.com/wtf-is-image-classification-8e78a8235acb), almost all of which use [CNN](https://en.wikipedia.org/wiki/Convolutional_neural_network) (convolutional neural net) architecture.

### Adversarial black-box attack
Adversarial attacks can be divided (among other different categorization criteria) into two categories
- White-box attacks
- Black-box attacks

#### White-box attacks
Attack scenario, in which the entire neural network with all its parameters (architecture, weights and biases) is available to the attacker. This type of attack is relatively easy to execute.

#### Black-box attacks
(Almost) Nothing about the neural network is known. The attacker can only query the resulting decision. I study these types of attacks because this is a much more realistic scenario in the real world. 

### Attacking live public services
Some online services provide API for image recognition and labeling.

### My motivations
<iframe frameBorder="0" width="800" height="600" style="border:0" src="https://orgpad.com/s/dGBbNV20_XY?embed=true"></iframe>
