---
layout: page
title: research
permalink: /research/
description: Research interests and projects.
nav: true
nav_order: 3
---

I study how the visual input children actually receive shapes the object representations they build, and how that input compares to what vision models are trained on—using large-scale egocentric video, computer vision, and behavioral experiments.

---

### Characterizing infant visual experience

What do young children actually see, and how does it compare to the data that drives modern vision systems? I use naturalistic egocentric video (the [BabyView dataset](https://doi.org/10.48550/arXiv.2406.10447)) to quantify objects in the child’s view and compare those statistics to curated datasets such as THINGS.

- **[Variability in young children’s everyday visual experiences of object categories](/assets/pdf/ccn_2026_object_variability_camera_ready.pdf)** (CCN 2026, spotlight) — Global and local dispersion over 85 categories and 7,018 validated crops, separating viewpoint-driven from instance-driven variability. [Poster](/assets/pdf/object_variability_ccn_poster_07302026_44x33.pdf).
- **[Characterizing the visual representation of objects from the child’s view](https://arxiv.org/abs/2605.14990)** (under review) — Object frequency and representational geometry across 868+ hours of egocentric video from 31 families, compared with THINGS using CLIP and DINOv3.
- **[Characterizing the inputs to infants’ object category representations](/publications/)** (VSS 2026) — How these inputs relate to early object categories.
- **[Quantifying infants’ everyday experiences with objects in a large corpus of egocentric videos](https://2025.ccneuro.org/abstract_pdf/Yang_2025_Quantifying_infants_everyday_experiences_objects_large.pdf)** (CCN 2025) — Automated object detection over 868+ hours of infant headcam video.

---

### Visual–linguistic alignment

How well are the visual and linguistic streams aligned in naturalistic settings? I use multimodal models (e.g., CLIP) to measure that alignment in egocentric infant data.

- **[Assessing the alignment between infants’ visual and linguistic experience using multimodal language models](https://arxiv.org/abs/2511.18824)** (Tan, Yang, et al., 2025) — Vision–language models to assess alignment over time and what makes naturalistic multimodal input learnable.

---

### Attention, action, and learning

How do attention and action structure learning—e.g., how manual actions create visual saliency and support joint attention, and how real-time attention relates to language?

- **[Toddlers’ active gaze behavior supports self-supervised object learning](https://doi.org/10.1111/desc.70231)** (Yu, Aubret, Raabe, Yang, Yu, & Triesch, Developmental Science, 2026) — Toddlers’ gaze during dyadic play supports self-supervised learning of view-invariant object representations.
- **[Using manual actions to create visual saliency](https://escholarship.org/uc/item/0wv2f31h)** (CogSci 2023) — Manual actions create visual saliency and support joint attention from an “outside-in” perspective.
- **[Learning semantic knowledge based on infant real-time attention and parent in-situ speech](https://escholarship.org/uc/item/48w894zd)** (CogSci 2024) — Linking infant gaze and parent speech to ask how attention shapes which semantic information is available during learning.

---

### 3D shape and object experience

Do children and vision models converge on 3D object shape? I built **MOCHI Kids**, a developmental (ages 4–6) adaptation of the MOCHI shape-oddity benchmark, for direct human–model comparison on multiview object consistency. The web experiment (TypeScript, jsPsych, Express, MongoDB) is in piloting. In parallel, I am building a synchronized capture rig—head-mounted eye tracking, depth cameras, and a room camera—to measure how action and dyadic interaction change the object views children get.

---

### Methods and open science

**Methods:** Computer vision (object detection, pose estimation, multimodal embeddings), multimodal data fusion (head-mounted eye trackers, cameras, microphones), and behavioral experiments (web and in-lab, including human–model benchmarks).  
**Open science:** Reproducible pipelines for large-scale naturalistic data, including a BabyView Objects reproducibility capsule, a CCN 2026 object-variability analysis package, and a layer-wise embedding explorer.
