---
layout: page
title: `impart`: Software for Flexible Randomized Trials & Covariate Adjustment
description: a project with a background image and giscus comments
img: assets/img/3.jpg
importance: 2
category: work
giscus_comments: true
---

Designing randomized trials that are efficient and ethical is a challenge.
Investigators need to collect enough data to identify meaningful benefits or harms
when they exist, but also avoid exposing more individuals than necessary to
experimental conditions.

The amount of data that needs to be collected often depends on characteristics
of the population and treatment that aren't well understood at the outset of a
study. Many studies are designed to use prior estimates, often from smaller
studies or different populations, to inform sample size requirements. If these
estimates are incorrect, studies may collect too much data, or not enough to
provide the precision needed to meaningfully answer scientific and clinical
questions.

Information monitoring allows investigators to use the data being collected to
determine when enough data has been collected to answer the primary aim of the
study. Rather than using prior estimates to determine sample size requirements,
such designs instead use the precision of the estimate to determine when data
accrual should stop. It can be viewed as a generalization of a type of study
known as an *event-driven trial* for studies with a time-to-event outcome.

`impart` allows investigators to plan, monitor, and analyze
information-monitored trials. It also can be used to ensure that covariate
adjusted analyses maintain appropriate type I error when used in trials
with interim analyses for efficacy and futility.