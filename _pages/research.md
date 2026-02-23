---
layout: page
title: research
permalink: /research/
description: Research interests and projects.
nav: true
nav_order: 3
---

My research focuses on **egocentric vision**, **visual representation learning**, and **perception and interaction in naturalistic environments**. I use large-scale egocentric video, computer vision, and behavioral experiments to understand how infants’ everyday visual experience shapes early concept development. Below are key research directions and representative work.

## characterizing infant visual experience

What do infants actually see in their daily environments? How does that distribution of experience compare to the data that drives modern computer vision? I work with naturalistic egocentric video (e.g., the [BabyView dataset](https://doi.org/10.48550/arXiv.2406.10447)) to quantify objects, scenes, and activities in infants’ view, and to compare those statistics to standard vision datasets.

With [Quantifying infants’ everyday experiences with objects in a large corpus of egocentric videos](https://2025.ccneuro.org/abstract_pdf/Yang_2025_Quantifying_infants_everyday_experiences_objects_large.pdf) (CCN 2025), we used automated object detection over 868+ hours of infant headcam video to characterize the objects infants encounter. In [Characterizing the inputs to infants’ object category representations](/publications/) (VSS 2026), we extend this line of work to ask how these inputs relate to the structure of early object categories. We also extracted CLIP and DINO embeddings to compare infant visual experience to datasets like THINGS.

## visual–linguistic alignment in development

Infants learn from both what they see and what they hear. A central question is how well the visual and linguistic streams are aligned in naturalistic settings. I use multimodal models (e.g., CLIP) to measure that alignment in egocentric infant data.

In [Assessing the alignment between infants’ visual and linguistic experience using multimodal language models](https://arxiv.org/abs/2511.18824) (Tan, Yang, et al., 2025), we use vision–language models to assess how well the visual and linguistic inputs to infants align over time. This work is part of a broader effort to understand what makes naturalistic multimodal input learnable for both humans and machines.

## attention, action, and learning from naturalistic input

I am also interested in how **attention and action** structure learning—for example, how manual actions create visual saliency and support sustained and joint attention, and how real-time attention relates to the language infants hear.

In [Using manual actions to create visual saliency](https://escholarship.org/uc/item/0wv2f31h) (CogSci 2023), we showed that manual actions can create visual saliency and support joint attention from an “outside-in” perspective. In [Learning semantic knowledge based on infant real-time attention and parent in-situ speech](https://escholarship.org/uc/item/48w894zd) (CogSci 2024), we linked infant gaze and parent speech in naturalistic settings to ask how attention shapes which semantic information is available during learning.

## methods and open science

I rely on **computer vision** (object detection, pose estimation, multimodal embeddings), **multimodal data fusion** (head-mounted eye trackers, cameras, microphones), and **behavioral experiments** (e.g., eye-tracking) to study these questions. I am committed to open science and to making developmental psychology more data-driven and ecologically valid by using large-scale, naturalistic data and reproducible pipelines.
