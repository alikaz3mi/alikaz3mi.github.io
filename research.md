---
layout: default
title: Research Statement
permalink: /research/
---

# Research Statement

I want to do a PhD at the point where biomedical engineering, computational neuroscience, and machine learning meet. That is where my training and my instincts already are: my M.Sc. was in neural-signal and brain-image modeling, my independent project applies modern ML to brain data, and six years of engineering taught me to turn a research idea into an experiment that actually runs and produces a defensible number.

## Where I come from

My M.Sc. thesis modeled the development of perisylvian language pathways in the brains of term neonates using diffusion tensor imaging (DTI). The work was about reading microstructure from noisy, low-sample medical data and saying something quantitative about how the brain wires itself early in life. It taught me the things that don't transfer from a textbook: how fragile biomedical data is, how much of the result lives in the preprocessing, and how careful you have to be before claiming an effect is real. A paper from this line of work is in progress.

Alongside it, I built [Mind2Text](https://github.com/alikaz3mi/mind2text), an independent project that decodes cognitive states from EEG using large language models with symbolic tokenization and LoRA fine-tuning. It reached 78.2% accuracy and beat CNN and SVM baselines. I started it to answer a specific question — whether transformer models, which were built for language, can read structure in brain signals — and the answer was interesting enough that I want to keep pulling on it.

In parallel I spent six years building production machine learning systems. That work is not biomedical, but it is where I learned to do research at scale: fine-tuning models on 49M+ images to 99.97% accuracy, running structured model-evaluation studies, cutting inference cost by 96%, and building the pipelines and evaluation harnesses that let a result be reproduced rather than just reported. A lot of biomedical AI stalls not on ideas but on engineering. That is the part I am good at.

## What I want to work on

Three threads, in rough order of how close they are to my heart:

**Neural-signal analysis and brain–computer interfaces.** Deep learning for EEG and electrophysiology — decoding, spike sorting, and the messy reality of recordings that vary by subject, session, and hardware. Mind2Text is the seed; I want to study how far foundation-model ideas (pretraining, tokenization, transfer) carry into neural data, where labels are scarce and noise is structured.

**Medical imaging and biomedical data science.** Extending my DTI work toward deep-learning methods for medical images and clinical signals — segmentation, modeling development or disease progression, and the recurring problem of small, heterogeneous clinical datasets. I care about methods that a clinician could actually trust, not just ones that win on a benchmark.

**Machine learning and LLMs, with an eye on reliability.** Efficient inference and fine-tuning, retrieval-augmented and agentic systems, and reducing hallucination. This is where most of my applied work lives, and it matters most exactly where I want to apply it: in clinical and resource-constrained settings, where a wrong-but-confident answer is not acceptable.

I am genuinely open across this range. A computational-neuroscience or medical-imaging group is as good a fit for me as an AI lab — the work I am proudest of has always been where the two sides meet.

## How I work

I run controlled experiments and I do not make claims I can't back with a number. I write code that other people can rerun. I think the bottleneck in a lot of applied research is not the model but the infrastructure around it — the data handling, the evaluation, the reproducibility — and that is the part I bring without being asked. I would rather report a smaller, real effect than a larger one I can't defend.

## On publications

My published record is still short: a manuscript in preparation from my M.Sc. work and a paper I am actively writing, plus the open Mind2Text project. I treat that as the next thing to fix, not something to hide. The point of a PhD, for me, is to convert the research I can clearly do into work that is reviewed and published — and I am already moving on it.

---

*Want to talk about a fit? [Email me](mailto:alikazemi@ieee.org) or see my [CV](/resume/) and [research & projects](/projects/).*
