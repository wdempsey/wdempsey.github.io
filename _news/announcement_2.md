---
layout: post
title: Stratified MRT paper accepted at Annals of Applied Statistics
date: 2019-09-02 12:00:00-0400
inline: false
---

My paper on
[the stratified micro-randomized trial](https://arxiv.org/abs/1711.03587)
was just accepted at the Annals of Applied Statistics.  This paper was
written in collaboration with my postdoctoral mentor Susan Murphy.
The paper covers a wide range of topics.  The work was motivated by a recent
mobile health smoking cessation trial `Sense2Stop` which serves as a
running example in the paper. In this study, participants are
trained in stress reduction exercises prior to their smoking quit
date. Apps that can be used to guide the participant through the exer-
cises are installed on study-provided phone. These apps can be
accessed at any time by a participant. However, a common problem is
that at the very times at which practicing these exercises might be
most useful, participants do not do so. The scientific team is most
interested in understanding whether reminders to practice
stress-reduction exercises will be useful in reducing/preventing
future stress if the reminders are delivered at times the participant
is classified as stressed.

***

`Micro‐randomized trials` (MRTs) are trials in which participants are
randomly assigned a treatment from the set of possible treatment
actions at several times throughout the day. Thus each participant may
be randomised hundreds or thousands of times over the course of a
study. This is very different than a traditional randomised trial, in
which participants are randomised once to one of a handful of
treatment groups. `Stratified MRTs` are micro-randomized trials in
which an individual is randomized among treatments at times determined
by predictions constructed from outcomes to prior treatment and with
randomization probabilities depending on these outcomes.
Stratification is required to ensure sufficient treatment and
non-treatment occasions across risk strata.
In Sense2Stop, randomizations to treatment should occur at times of
stress and second the outcome of interest accrues over a period that
may include subsequent treatment. 

#### Topics covered
The paper covers a wide range of topics:
<ul>
    <li>Experimental design</li>
    <li>Causal inference</li>
    <li>Simulation design for power calculations </li>
</ul>

The causal calculus highlights the difficulty in expressing the
primary scientific hypothesis in terms of a causal effect.
The design accounts for the fact that online monitoring of the
stratification variable was required.
The primary analysis method is based on a weighted-centered approach
that is quite general.
The power calculations require a simulation-based approach that
leverages prior data in the simulation design.

***

The scientific question motivating the paper was:
> Is there an effect of the reminder treatment on near-term, proximal stress if the individual is currently experiencing stress? Does the effect of the reminder treatments vary with time in study?

Of course, the methods and design are general and should be useful to
applied health scientists interested in scientific questions regarding
nested causal effects of time-varying treatments.
I hope you enjoy the paper; if you have any comments or questions,
please feel to reach out to me via e-mail.
