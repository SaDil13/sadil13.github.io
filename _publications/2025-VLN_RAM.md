---
title: "Unseen from Seen: Rewriting Observation-Instruction Using Foundation Models for Augmenting Vision-Language Navigation"
collection: publications
category: manuscripts
permalink: /publication/2025-VLN_RAM
excerpt: 'Vision Language Navigation, Embodied AI'
date: 2025-03-23
venue: 'Under Review'
slidesurl: # 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/pdf/2503.18065'
citation: 'https://sadil13.github.io/assets/bibtex/vlnram.bib'
---

Data scarcity is a long-standing challenge in the Vision-Language Navigation (VLN) field, which extremely hinders the generalization of agents to unseen environments. Previous works primarily rely on additional simulator data or web-collected images/videos to improve the generalization. However, the simulator environments still face limited diversity, and the web-collected data often requires extensive labor to remove the noise. In this paper, we propose a Rewriting-driven AugMentation (RAM) paradigm for VLN, which directly creates the unseen observation-instruction pairs via rewriting human-annotated training data. Benefiting from our rewriting mechanism, new observation-instruction can be obtained in both simulator-free and labor-saving manners to promote generalization. Specifically, we first introduce Object-Enriched Observation Rewriting, where we combine Vision-Language Models (VLMs) and Large Language Models (LLMs) to derive rewritten object-enriched scene descriptions, enabling observation synthesis with diverse objects and spatial layouts via Text-to-Image Generation Models (T2IMs). Then, we propose Observation-Contrast Instruction Rewriting, which generates observation-aligned rewritten instructions by requiring LLMs to reason the difference between original and new observations. We further develop a mixing-then-focusing training strategy with a random observation cropping scheme, effectively enhancing data distribution diversity while suppressing augmentation data noise during training. Experiments on both the discrete environments (R2R, REVERIE, and R4R datasets) and continuous environments (R2R-CE dataset) show the superior performance and impressive generalization ability of our method.